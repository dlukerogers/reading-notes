# Read: Class 12

## Status Codes Based On REST Methods  

1. In your own words, describe what each group of status code represents:

    * *100’s = Information status codes which tells the client that the header has been received and the server will try to comply with a transmission command.*
    * *200’s = Success codes that tell the client that its information was accepted.*
    * *300’s = Redirection codes that tell the client that the information they are requesting is not available anymore at that location.*
    * *400’s = Client error codes that are invalid requests a client sent to the server.*
    * *500’s = Server error codes that happen when a server is overwhelmed or unreachable.*  

2. What is a status code 202?  
  *Status code 202 Accepted is a code that tells the client that the request was valid, but its processing will finish sometime in the future.*  

3. What is a status code 308?  
  *Status code 308 Permanent Redirect is a code the tells the client that they need to use a different URL to access the resource and the current URL doesn't work anymore.*  

4. What code would you use if an update didn’t return data to a client?  
  *204 No Content*  

5. What code would you use if a resource used to exist but no longer does?  
  *410 Gone*  

6. What is the ‘Forbidden’ status code?  
  *403 Forbidden*  

## Build A REST API With Node.js, Express, & MongoDB - Quick  

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?  
  *We need to pull our MongoDB database string out of our server and put it into our .env because when we deploy our application, we want to use something that is not our local host.*  

2. What is middleware?  
  *Middleware is code that runs when the server gets a request but before it gets passed to our routes.*  

3. What does `app.use(express.json())` do?  
  *It lets our server accept json as a body inside a post or get element.*  

4. What does the `/:id` mean in a route?  
  *It means that it is a parameter that we can access by typing in `req.params` which would give us access to the id the client types in after the first `/`.*  

5. What is the difference between `PUT` and `PATCH`?  
  *You use `PATCH` when you only want to update based on what the user passes us. `PUT` would update all the information all at once.*  

6. How do you make a default value in a schema?  
  *You make a default value in a schema by using the `default()` method of the Mongoose API on the SchemaType object*  

7. What does a `500` error status code mean?
  *A `500 Internal Server Error` means that the server found an unexpected condition that prevented it from going through with its request.*  

8. What is the difference between a status `200` and a status `201`?  
  *A status `200` means everything was successful while a status `201` means you successfully created an object. It is more specific.*
