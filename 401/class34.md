# Class 34 notes - API Integration

## Review API Server Build

**Explain the different between a query string parameter and a path parameter.**
Path parameters are used to identify a specific resource. Query string parameters are used to filter the results of a query.

**What would our API URL with a path id parameter be given the following information:**
Domain: http://our-site.com
v3
model name: stuff
id: things

http://our-site.com/v3/stuff/things

**We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.**
You can hit an endpoint and give it a query string parameter to filter the results. You can also hit an endpoint and give it a path parameter to get a specific resource.

## Review Auth Server Build

**Describe how you would use middleware to implement basic and bearer auth.**
basic auth would be used to verify a user's credentials. bearer auth would be used to verify a user's token.

**Describe the handshake necessary to implement OAuth.**
the client sends a request to the server to get an authorization code. the server sends the client an authorization code. the client sends a request to the server to get an access token. the server sends the client an access token.

**Describe how Role Based Access Control works to a non-technical friend.**
role based access control is a way to limit access to certain resources based on a user's role.
