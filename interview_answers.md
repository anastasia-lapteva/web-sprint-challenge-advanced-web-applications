# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. Explain what a token is used for.

An authentication token is used to securely transmit information about user identities between applications and websites. It allows internet users to access applications, services, websites, and application programming interfaces (APIs) without having to enter their login credentials each time they visit. Instead, the user logs in once, and a unique token is generated and shared with connected applications or websites to verify their identity. The user of the token is provided with an access token to a website until they log out or close the service.

An authentication token is formed of three key components: the header, payload, and signature.
(1) Header: The header defines the token type being used, as well as the signing algorithm involved.
(2) Payload: The payload is responsible for defining the token issuer and the token's expiration details. It also provides information about the user plus other metadata.
(3) Signature: The signature verifies the authenticity of a message and that a message has not changed while in transit.

2. What steps can you take in your web apps to keep your data secure?

To keep your data secure, you can:
-apply authentication
-apply role management
-apply access control
-encrypt your data

3. Describe how web servers work.

Web Servers are computer programs that dispense the web page when they are requested using the web client. Web Servers are run on machines usually called servers. The names web server and server are used interchangeably. 

After the user properly authenticates (properly logs in), the server returns a token.

4. Which HTTP methods can be mapped to the CRUD acronym that we use when interfacing with APIs/Servers.

C - create
R - read
U - update (put)
D - delete