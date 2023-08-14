# Read: Class 08

## API Design Best Practices  

1. What does REST stand for?  
  *Representational State Transfer*  

2. REST APIs are designed around a ____.  
  *resource*  

3. What is an identifier of a resource? Give an example.  
  *An identifier of a resource is a URI that uniquely identifies that resource. An example of this is `https://superguy.com/profile` with 'profile' being the identifier.*  

4. What are the most common HTTP verbs?  
  *The most common HTTP verbs are `GET`, `PUT`, `POST`, `PATCH`, and `DELETE`.*  

5. What should the URIs be based on?  
  *URIs should be based on nouns or the resource, not verbs or the operations on the resource.*  

6. Give an example of a good URI.  
  *An example of a good URI is `https://superguy.com/blog` as opposed to `https://superguy.com/createblog`. This is because the resource 'blog' is a noun while 'createblog' is a verb.*  

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?  
  *Having a 'chatty' web API means that it gives off a ton of requests imposing a load on the web server, which exposes a large number of small resources. It is a bad thing because it may require a client application to send multiple requests to find all the data that it requires.*  

8. What status code does a successful `GET` request return?  
  *A successful `GET` request returns a 200.*  

9. What status code does an unsuccessful `GET` request return?  
  *An unsuccessful `GET` request returns a 404.*  

10. What status code does a successful `POST` request return?  
  *A successful `POST` request returns a 201.*  

11. What status code does a successful `DELETE` request return?  
  *A successful `DELETE` request returns a 204.*  
