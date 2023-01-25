# Class 12 notes - CRUD

## Status Codes

In your own words, describe what each group of status code represents:

**100’s =**
Sending information that the request was received.

**200’s =**
Success codes

**300’s =**
resource is not available at that location anymore.

**400’s =**
Invalid requests.

**500’s =**
Overwhelmed servers

**What is a status code 202?**
Accepted. Request is valid but is still processing.

**What is a status code 308?**
Permanent Redirect. Resource is now available at a new URL.

**What code would you use if an update didn’t return data to a client?**
404 Not Found

**What code would you use if a resource used to exist but no longer does?**
410 Gone

**What is the ‘Forbidden’ status code?**
403

## REST API

**Why do we need to pull our MongoDB database string out of our server and put it into our .env?**
So our application can use it

**What is middleware?**
code that runs when a server gets a request before it goes to routes.

**What does app.use(express.json()) do?**
Allows server to accept JSON

**What does the /:id mean in a route?**
it is a parameter.

**What is the difference between PUT and PATCH?**
PATCH only updates the information that is passed.

**How do you make a default value in a schema?**
by using default:

**What does a 500 error status code mean?**
Error on the server

**What is the difference between a status 200 and a status 201?**
201-Successfully created something. 200-Successful request
