# Spring Boot + Auth0

[Tutorial](https://auth0.com/blog/spring-boot-java-authorization-tutorial-secure-an-api/).

Clone the project in a directory called `menu-api`

```bash
git clone https://github.com/auth0-blog/menu-api-spring-boot-java.git springboot-api-auth0
cd springboot-api-auth0
```

Then, install the project dependencies using Gradle:

```bash
./gradlew --refresh-dependencies
```

Finally, open the `application.properties` file in `src/main/resources` and add:

```bash
server.port=7000
auth0.audience=https://menu-api.danny.com
auth0.domain=dev-ha2csa52.us.auth0.com
spring.security.oauth2.resourceserver.jwt.issuer-uri=https://${auth0.domain}/
```

Run the project by executing the following command:

```bash
./gradlew bootRun
```

## Test the API with the Demo Client

[WHATABYTE Dashboard](https://dashboard.whatabyte.app/home).
