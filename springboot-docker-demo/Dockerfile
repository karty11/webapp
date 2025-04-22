FROM eclipse-temurin:17

MAINTAINER karthik

WORKDIR /app

COPY target/springboot-docker-demo-0.0.1-SNAPSHOT  /app/springboot-docker-demo.jar

ENTRYPOINT ["java", "-jar", "springboot-docker-demo.jar"]