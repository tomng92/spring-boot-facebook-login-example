# Spring Boot Facebook Login example

This example is based on Spring Boot's Facebook login demo.

Here is Spring Facebook demo (https://spring.io/blog/2018/03/06/using-spring-security-5-to-integrate-with-oauth-2-secured-services-such-as-facebook-and-github).

(https://spring.io/guides/tutorials/spring-boot-oauth2/).

## Architecture
<img src="./images/architecture.png" alt="architecture" />

## Version
- Spring Boot 2.1.5
- Spring Security 2.1.5
- Spring OAuth2 Auto Configure 2.1.5
- Webjars Jquery 2.1.3

## Notes
- `http://localhost:8080/` - Will show the Login here option and authenticates and displays user information from Facebook
- `application.yml` - contains API information and can be changed for your Facebook API.
- `index.html` - contains the code for displaying the user information using Jquery.