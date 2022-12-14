# Reading

## API Design Best Practices

1. What does REST stand for?

Representational State Transfer 

2.  REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

3. What is an identifier of a resource? Give an example.

A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be: https://adventure-works.com/orders/1

4. What are the most common HTTP verbs?

The most common operations are GET, POST, PUT, PATCH, and DELETE.


5. What should the URIs be based on?

When possible, resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

6. Give an example of a good URI.

https://adventure-works.com/orders // Good https://adventure-works.com/create-order // Avoid

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

All web requests impose a load on the web server. The more requests, the bigger the load. Therefore, try to avoid "chatty" web APIs that expose a large number of small resources. 

8. What status code does a successful GET request return?

A successful GET method typically returns HTTP status code 200 (OK). 

9. What status code does an unsuccessful GET request return?

If the resource cannot be found, the method should return 404 (Not Found).

10. What status code does a successful POST request return?

If a POST method creates a new resource, it returns HTTP status code 201 (Created). 

11. What status code does a successful DELETE request return?

If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content)

## Things I want to know more about

Whats the best way to practice using HTTP requests
