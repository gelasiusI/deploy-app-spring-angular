FROM eclipse-temurin:11
VOLUME /tmp
EXPOSE 8081
ARG JAR_FILE=springboot/app/target/*.jar
ADD ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
