FROM openjdk:11

COPY ./target/MuzixAssignment-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8080

RUN sh -c 'touch app.jar'

ENTRYPOINT ["java","-jar","app.jar"]