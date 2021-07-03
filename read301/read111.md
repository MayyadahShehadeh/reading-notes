# Authentication

### 1. What is OAuth?
* OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.

### 2. Give an example of what using OAuth would look like.
* When you are logging in and there is an option to log in from a different site, the other site would then authenticate you and reroute you to the original site, logged in.
### 3. How does OAuth work? What are the steps that it takes to authenticate the user?
* (in this example, the user is already logged into the website A)

* Website A connects to website B on behalf of the user, providing the user's verified ID

* Website B generates a one time token, and a one time secret unique for the user Website A gives

* the client this token and unique

* The client provides these to the authorization provider

* The client must authenticate to website B, then approve the action on website B

* The client approves a particular transaction type from website A

* The client receives an approved access token

* The client sends website A this approved access token

* Website A sends the access token to website B on behalf of the user

* Website B allows website A access to their site on behalf of the user

* The user sees transaction working

### 4. What is OpenID?
* OpenID is for authentication, opposed to OAuth which is used for authorization
--------------------------------------------------------------------

### 1. What is the difference between authorization and authentication?
* Authentication: determines if users are who they say, done before authorization, transmits info through an ID token, challenges the user to provide credentials
### 2. What is Authorization Code Flow?
* This is the exchange of an Authorization Code for an access token

### 3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
* OAuth 2.0 provides additional security measures, sometimes required for mobile and native applications, as well as "special challenges" that single page applications sometimes have

### 4. What is Implicit Flow with Form Post?
This is a more outdated version of OAuth's code flow which may work at the bare basic level, and will not provide additional security measures, which can be an issue in some cases (bad practice)
### 5. What is Client Credentials Flow?
* This is used in cases for back end applications, where the system authenticates and authorizes the app instead of the user

### 6. What is Device Authorization Flow?
* This is for devices which may not have an easy to use text UI, so they send the Client ID to a different device of the users to provide authentication and authorization
### 7. What is Resource Owner Password Flow?
* This is not recommended unless very strict and specific conditions are met. This is when the user sends strict username and password data to the back end, this could potentially be stored

