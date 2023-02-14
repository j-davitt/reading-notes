# Class 2 notes - Express, NPM, TDD, CI/CD

## An introduction to NodeJS and Express

**Explain middleware, answer as though I were a non-technical recruiter.**
Middlewarre acts as a middleman between the applications, data, and users.

**Express the most popular __ __ ____.**
Node web framework.

**Express is “unopinionated.” What does that mean?**
"You can insert almost any compatible middleware you like into the request handling chain, in almost any order you like. You can structure the app in one file or multiple files, and using any directory structure."

**What is a module and why is modularity useful to us as developers?**
A module is a JS library/file that can be imported into code. Modules are useful for duplicating functionality as well as troubleshooting.

## What is NPM?

**What version of npm are you running on your machine?**
9.4.0

**What command would you type to install a library/package called ‘jshint’ into your node project?**
npm i jshint

## What is TDD?

**Explain why tests are important. Please explain as though I were your non technical elder.**
Testing is important to ensure the application works as expected.

**What are three expected benefits of testing.**

- reduction in defect rates.

- reduction in efforts in final phases.

- improved design qualities in the code.

**Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.**

Typical individual mistakes include:

- forgetting to run tests frequently
- writing too many tests at once
- writing tests that are too large or coarse-grained
- writing overly trivial tests, for instance omitting assertions
- writing tests for trivial code, for instance accessors

Typical team pitfalls include:

- partial adoption – only a few developers on the team use TDD
- poor maintenance of the test suite – most commonly leading to a test suite with a prohibitively long running time
- abandoned test suite (i.e. seldom or never run) – sometimes as a result of poor maintenance, sometimes as a result of team turnover

## CI/CD

**What are three benefits of Continuous Integration?**
Ensure everyones changes will integrate, catch bugs, and reduce merge conflicts.

**What is the difference between Continuos Delivery and Continuous Deployment?**
Continuous Delivery- Developed to be released at any time.

Continuous Deployment- Deploy new features immediately with little or no downtime.

**Explain how GitHub fits into this process assuming the listener comes from a non-technical background.**
Devs make changes locally and push to github. Github then can send messages and test the build to ensure it can be integrated successfully.
