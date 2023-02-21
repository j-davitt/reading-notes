# Class 6 notes - Authentication

## Securing Passwords

**Explain to a non-technical friend how you would safely hash and store a password.**
The benefit of hashing is that if someone steals the database with hashed passwords, they only make off with the hashes and not the actual plaintext passwords

**What is Bcrypt?**
Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.

**Why might you use something like Bcrypt?**
This method of hashing passwords is solid enough for most web applications that stores users' passwords and other sensitive data.

## Basic Auth

**What is Basic Authentication?**
a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request.

**What properties are necessary in the header of a Basic Auth request?**
Authorization header field

**How are username:password in Basic Auth encoded?**
encoded using a variant of Base64

## OWASP auth cheatsheet

**Define the authentication process to a non-technical recruiter.**
Authentication is the process of verifying that an individual, entity or website is whom it claims to be. Authentication in the context of web applications is commonly performed by submitting a username or ID and one or more items of private information that only a given user should know.

**How should your error messaging respond (both HTTP and HTML)? Why?**
In a generic manner so the error message cannot be used for the purposes of user ID and password enumeration.

