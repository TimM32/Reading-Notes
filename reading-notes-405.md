# Reading Notes for Class 6

- Explain to a non-technical friend how you would safely hash and store a password. I would encoded them using hashes and not the plaintext password. The ecoded hasdes is like a safe for your password so that in case someone tries to steal the entire database (place where we hold onto all the information given) they will not be able to get your actual password they would only have the safe that is protecting the password. This is much safer than just storing the actaul test of the password.

- What is Bcrypt? BCrypt Algorithm is used to hash and salt passwords securely. BCrypt permits building a password security stage that can advance nearby hardware innovation to guard against dangers or threats in the long run, like attackers having the computing power to guess passwords twice as quickly
- Why might you use something like Bcrypt? This is good for password hashing as it reduces the number of passwords by second an attacker could hash when crafting a dictionary attack. 

- What is Basic Authentication? HTTP basic authentication is a simple challenge and response mechanism with which a server can request authentication information (a user ID and password) from a client. The client passes the authentication information to the server in an Authorization header. The authentication information is in base-64 encoding.
- What properties are necessary in the header of a Basic Auth request?
  1. The username and password are combined with a single colon (:). This means that the username itself cannot contain a colon.
  2. The resulting string is encoded into an octet sequence. The character set to use for this encoding is by default unspecified, as long as it is compatible with US-ASCII, but the server may          suggest use of UTF-8 by sending the charset parameter.[9]
  3. The resulting string is encoded using a variant of Base64 (+/ and with padding).
  4. The authorization method and a space character (e.g. "Basic ") is then prepended to the encoded string.
- How are username:password in Basic Auth encoded? Base64 is a way to deliver binary data through a connection (or file) that limits what characters are allowed to be included. For example, e-mail attachments are encoded in base64 because the e-mail protocol only allows for plain text in an e-mail message. Highly active question.

- Define the authentication process to a non-technical recruiter. This is something that you do everyday when you log onto your email or social media website/app. The process is asking for information from you (that you hve given to it previously) to ensure that the person that is trying to access your information is actually you. This is done with a username and password but can be further authorized by having the program or the websitre send you a one time password via email or text to make sure that it is indeed you that is trying to login in. 
- How should your error messaging respond (both HTTP and HTML)? Why? You want to make sure that error message gives back a general message saying something like "Invalid username or Password" You dont want to specify which one because you don't want someone else trying to break into that account to know that they got any infromation correct. You also don't want to include anything like a code error or something that they can latch onto to get more information. You do want an error message back in case the person whose account it is might have mixed up some information from another account. 

## Additional Information
