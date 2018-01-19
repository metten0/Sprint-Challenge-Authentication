#Self Study Questions:
---
1. Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.

*_Middleware_* - Often referred to as "software glue", middleware is generally written to exist between applications and operating systems, for the purpose of improving/enabling interaction between them. Types of middleware include: application-level middleware, router-level middleware, and error-handling middleware.  Middleware can be written by the application's developer and function exclusively for one application or it can be developed by a third party for use by a wide range of applications. 

*_Sessions_* - A finite period of time in which a specific runtime state is stored and access across requests is allowed. Session information can be stored in a variety of ways, with the most popular including: application memory, cookies, memory cache and external database. 

*_bcrypt_* - Designed by Niels Provos and David Mazières, bcrypt is a one-way function that provides password hashing and salting in the interest of increasing security. bcrypt can also increase iteration time, causing brute-force search attacks to timeout before they are successful.

*_JWT_* - JWT stands for JavaScript Object Notation (JSON) Web Token. JWT is an open standard designed to securely transmit JSON objects between parties. A typical exchange involves a client providing credentials & requestng a signed token fromm the server, the server generating the token and sending it down to the client, and finally, the client sending back token authentication information with other requests.



2. What does bcrypt do in order to prevent attacks?

### *_Answer*_
---
As discussed above, bcrypt prevents rainbow table attacks, brute-force search attacks, et. al. by providing password hashing & salting, as well as increasing iteration time.


3. What are the three parts of the JSON Web Token?
### *_Answer*_
Header, Payload and Signature
