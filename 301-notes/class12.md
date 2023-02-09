# Readings: CRUD

Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:

- 100’s = Information status code to tell the client the header request is received and for the server to attempt to comply with the clients demand
- 200’s = Success code that tells the client is request has met all validation requirements but is not yet processed.
- 300’s = Redirection code that tells the client the resource they are requesting is not available
- 400’s = Client error code, invalid requests to the server
- 500’s = Server error code, problem with the server

2. What is a status code 202?

Accepted - Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. 

3. What is a status code 308?

Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. 

4. What code would you use if an update didn’t return data to a client?

204 No Content - A proper code for updates that don’t return data to the client,

5. What code would you use if a resource used to exist but no longer does?

410 Gone - This is like 404 but we know that the resource existed in the past, but it got deleted or somehow moved, and we don’t know where.

6. What is the ‘Forbidden’ status code?

403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

# Videos

## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

When we deploy our application we want to use somnething that is not our local host so we want to create an enviroment variable.

2. What is middleware?

Code runs when the server gets a request but before it gets passed to our routes.

3. What does app.use(express.json()) do?

It lets our server accept JSON as a body instead of a post or get element

4. What does the /:id mean in a route?

It is a parameter to give us access

5. What is the difference between PUT and PATCH?

PUT will update all the information at once and PATCH will update only based on what the user passes us

6. How do you make a default value in a schema?

Create a default key and assign it the default value you want.

7. What does a 500 error status code mean?

It means that there is an error on the server.

8. What is the difference between a status 200 and a status 201?

201 means successfully created an object. 200 is a more general success status.

## Things I want to know more about

I'd like to know what different types of middleware are and what they do
