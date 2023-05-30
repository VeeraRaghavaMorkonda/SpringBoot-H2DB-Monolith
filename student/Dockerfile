FROM openjdk:17-alpine
COPY ./build/libs/student-0.0.1-SNAPSHOT.jar /usr/local/app/student-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java"]
CMD ["-jar", "/usr/local/app/student-0.0.1-SNAPSHOT.jar"]
EXPOSE 8080
