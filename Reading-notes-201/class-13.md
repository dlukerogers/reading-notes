# Read: Class 13  

## Local Storage and How To Use It On Websites  

1. Why would a developer use local storage for a web application?  
  *A developer would use local storage for a web application because HTTP over the web is stateless, meaning that when an application is closed on the web, it will reset the next time a user opens it. With local storage, a user can go into an application and see the information that was there before the application was closed. This is because the information is stored on the developer's local computer.*  

2. What information should not be stored in local storage?  
  *Personally identifiable information, authentication tokens, user locations, and API keys should not be stored in local storage in order to prevent the risk of potential access by malicious actors.*  

3. Local storage can store what type of data? How would you convert it to that type before storing?  
  *Local storage can only store strings. I would convert it to a string if it isn't one already by using the native `JSON.stringify()` and `JSON.parse()` methods.*  
