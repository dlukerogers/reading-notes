# Read: Class 15

## What is OAuth  

1. What is OAuth?  
  *OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.*  

2. Give an example of what using OAuth would look like.  
  *When a user logs into an app, OAuth can be used to log them in using a second website that verifies their information.*  

3. How does OAuth work? What are the steps that it takes to authenticate the user?  
    1. *The second website provides the first website with the user's verified identity.*
    2. *The second website comes up with a one-time token and a one-time secret.*
    3. *The first website gives these to the client software.*
    4. *The client software presents these to the authorization provider.*
    5. *The client is asked to authenticate then to approve the authorization transaction to the second website.*
    6. *The user approves a transaction type on the first website.*
    7. *The user is given an approved access token.*
    8. *The user gives the token to the first website.*
    9. *The first website gives the token to the second website.*
    10. *The second website lets the first website access their site.*
    11. *The user sees a successfully completed transaction.*

4. What is OpenID?  
  *OpenID is a security technology that is about authentication. It served as a single sign-in, vouching for the identity of a user.*  

## Authorization and Authentication flows  

1. What is the difference between authorization and authentication?  
  *Authentication is the process of verifying who a user is. Authorization is the process of verifying what they have access to.*  

2. What is Authorization Code Flow?  
  *Authorization Code Flow exchanges an Authorization Code for a token.*  

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?  
  *Authorization Code Flow with Proof Key for Code Exchange (PKCE) is built on Authorization Code Flow and mitigates special challenges and security issues that come with single-page apps.*  

4. What is Implicit Flow with Form Post?  
  *The Implicit Flow with Form Post is intended for applications that are unable to securely store Client Secrets.*  

5. What is Client Credentials Flow?  
  *Client Credentials Flow is intended for machine-to-machine applications in which the system authenticates and authorizes the app rather than the user.*  

6. What is Device Authorization Flow?  
  *Device Authorization Flow is used with input-constrained devices that connect to the internet when the device asks the user to go to a link on their computer or smartphone and authorize the device.*  

7. What is Resource Owner Password Flow?  
  *The Resource Owner Password Flow is used by highly trusted applications to request that users provide credentials.*  
