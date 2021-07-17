# Spring Authentication

Spring security stands between client and application and gives possibility of configuring what data and functionalities are exposed to which users.

There are five concepts in spring security:

* Authentication: to confirm who you are.
* Authorization: it is the ability to see the data.
* Principal: currently logged in user.
* Granted authority: permission.
* Roles: group of permissions.

## Servlet Filter

It is used to perform filtering tasks such as conversion, logging, compression, encryption and decryption, input validation.
and its entry is defined in the xml file.

### Why we use servlet filter

* recording all incoming requests
* logs the IP addresses of the computers from which the requests originate
* conversion
* data compression
* encryption and decryption
* input validation.
