# Reading Notes Class 7

- What is a JSON Web Token (JWT)? JSON web token (JWT), pronounced "jot", is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.
- When should we use JSON Web Tokens? One of the most used authentication standards in web applications is the JSON Web Token standard. It is mostly used for authentication, authorization, and information exchange.
- Claims are expected in which structural component of a JWT? JSON web tokens (JWTs) claims are pieces of information asserted about a subject. For example, an ID token (which is always a JWT ) can contain a claim called name that asserts that the name of the user authenticating is "John Doe".

- If I get a JWT and I can decode the payload, how can we call that secure? Always Check the Issuer. If someone should send you a forged JWT, with their issuer in it, and you then download keys from that issuer, then your application would validate the JWTs and accept them as genuine.
- If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature. They both need the private password and key
- Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter. This is like have a chest with valuable information that you only want people you trust to have access to. You give someone the combination to that chest that you trust to share it. 

- Why use JWT? Information exchange: JWTs are a good way of securely transmitting information between parties because they can be signed, which means you can be certain that the senders are who they say they are. Additionally, the structure of a JWT allows you to verify that the content hasn't been tampered with.
- JWT is Compact and self-contained. Describe how this is useful to a non-technical friend. It is useful because it allows it to be sent in many diifferent ways, makes it less restrictive. 
- What are the three components (the structure) of a JWT signature? A header, payload, and signature.

## Additional Information
