# Reading Notes Class 315


- What is OAuth? OAuth doesn't share password data but instead uses authorization tokens to prove an identity between consumers and service providers. OAuth is an authentication protocol that allows you to approve one application interacting with another on your behalf without giving away your password.
- Give an example of what using OAuth would look like. It would be somthing like asking for you username and password in order to get into your email or look at your account for internet, being able to pay bills, change what tpye of plan you have etc. 
- How does OAuth work? What are the steps that it takes to authenticate the user? OAuth 2.0, which stands for “Open Authorization”, is a standard designed to allow a website or application to access resources hosted by other web apps on behalf of a user.
Step 1 – The User Shows Intent.
Step 2 – The Consumer Gets Permission.
Step 3 – The User Is Redirected to the Service Provider.
Step 4 – The User Gives Permission.
Step 5 – The Consumer Obtains an Access Token.
Step 6 – The Consumer Accesses the Protected Resource.

- What is OpenID? OpenID allows you to use an existing account to sign in to multiple websites, without needing to create new passwords. You may choose to associate information with your OpenID that can be shared with the websites you visit, such as a name or email address.


What is the difference between authorization and authentication? Authentication and authorization are two vital information security processes that administrators use to protect systems and information. Authentication verifies the identity of a user or service, and authorization determines their access rights.
What is Authorization Code Flow? The OAuth 2.0 authorization code grant type, or auth code flow, enables a client application to obtain authorized access to protected resources like web APIs. The auth code flow requires a user-agent that supports redirection from the authorization server (the Microsoft identity platform) back to your application.
What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)? The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users. This flow is considered best practice when using Single Page Apps (SPA) or Mobile Apps. PKCE, pronounced “pixy” is an acronym for Proof Key for Code Exchange.
What is Implicit Flow with Form Post? Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.
What is Client Credentials Flow? The Client Credentials flow is a server to server flow. There is no user authentication involved in the process. In fact there is no user at all, the resulting access tokens will not contain a user, but will instead contain the Client ID as subject (if not configured otherwise).
What is Device Authorization Flow? The OAuth 2.0 Device Authorization Grant (formerly known as the Device Flow) is an OAuth 2.0 extension that enables devices with no browser or limited input capability to obtain an access token. This is commonly seen on Apple TV apps, or devices like hardware encoders that can stream video to a YouTube channel.
What is Resource Owner Password Flow? The Resource Owner Password Credentials flow allows exchanging the username and password of a user for an access token and, optionally, a refresh token. This flow has significantly different security properties than the other OAuth flows.

## Additonal Information


