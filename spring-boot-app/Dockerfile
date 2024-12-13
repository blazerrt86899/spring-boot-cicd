FROM eclipse-temurin:17.0.13_11-jre-alpine

WORKDIR /app

COPY target/*.jar app.jar

EXPOSE 8080

CMD [ "java","-jar","app.jar" ]