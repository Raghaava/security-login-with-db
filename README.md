# security-login-with-db-jwt

We are going to experiment with Spring Security. 

Let's have a mixed secured and unsecured REST endpoints. We are going to use JWT for authentication and authorization. 


One set of unsecured endpoints we have, are for generating JWT to access secured endpoints.

We have one end point(/protected) which can be accessed by users with Admin role.

Other endpoints, (/persions/**) and (/user) are unprotected.

Main objective of this project is understanding of how to integrate and configure spring security(ss) in a project.

1) We are informing ss that it can find user info with help of JwtUserDetailsService.
