# Readings: Express, NPM, TDD, CI/CD 

## An introduction to NodeJS and Express

1. Explain middleware, answer as though I were a non-technical recruiter.

It is the middleman that helps two applications talk to each other.

2. Express the most popular Node web framework.

3. Express is “unopinionated.” What does that mean?

You can insert almost any compatible middleware you like into the request handling chain, in almost any order you like. You can structure the app in one file or multiple files, and using any directory structure.

4. What is a module and why is modularity useful to us as developers?

Modularity is important for resuability, testability, and debugging.

## What is NPM?

1. What version of npm are you running on your machine?

9.4.0

2. What command would you type to install a library/package called ‘jshint’ into your node project?

npm i jshint

## What is TDD?

1. Explain why tests are important. Please explain as though I were your non technical elder.

It's like when you take your car to a maintenance shop. They have tests they run on the cars systems to make sure things are working properly and components are present.

2. What are three expected benefits of testing

- Many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort
- The same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases
- Although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling


3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

- writing too many tests at once
- writing tests that are too large or coarse-grained
-partial adoption – only a few developers on the team use TDD
- poor maintenance of the test suite – most commonly leading to a test suite with a prohibitively long running time

## CI/CD

1. What are three benefits of Continuous Integration?

- Higher efficiency.
- Reduced risk of defects. 
- Faster product delivery. 

2. What is the difference between Continuos Delivery and Continuous Deployment?

Continuous delivery is the practice of developing software in such a way that it is ready for release at any time. It allows development of modular features in more managable increments.
Continuous deployment allows for the deatures to deploy immediately.

3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background

Continuous integration is done with github by allowing developers to sending code to the github servers. Github then checks if it is able to integrate the code with the current working project.
Continuous delivery can be done via github using a third party application. By setting the deployment to a specific github branch the latest features can be delivered.

Reflection
What are your learning goals after reading and reviewing the class README?

- What are some CI/CD processes teams use in the industry?
