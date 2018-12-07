Spring Boot AOP examples
=
Two examples of how to log some method's parameter using aspects - before and after.

Use SwaggerUI for testing these aspects:
```
http://localhost:8080/swagger-ui.html
```
Post some test object, and see the logs.

Also added configurable by property `@Around` aspect to log execution time of the method.

Use `PUT` endpoint from Swagger UI to test it.