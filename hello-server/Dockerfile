FROM amazoncorretto:17

WORKDIR /app

COPY build/libs/*.jar /app/my-app.jar

EXPOSE 8080

CMD ["java", "-jar", "/app/my-app.jar"]