FROM openjdk:11
VOLUME /tmp
EXPOSE 8080
ADD ./target/spring-airline-1.0.0.jar app.jar
ENTRYPOINT [ "java", "-jar", "/app.jar" ]