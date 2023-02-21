# Class 7 notes - Bearer Authorization

## Intro to JWT

**What is a JSON Web Token (JWT)?**
JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

**When should we use JSON Web Tokens?**
For authorization or information exchange.

**Claims are expected in which structural component of a JWT?**
the payload

## Are JWTs Secure?

**If I get a JWT and I can decode the payload, how can we call that secure?**
If the message is altered, the receiver will know.

**If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.**
the payload

**Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.**
If content is altered, the signature wont match and it will be rejected.

## JWTs Explained

**Why use JWT?**


**JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.**


**What are the three components (the structure) of a JWT signature?**

