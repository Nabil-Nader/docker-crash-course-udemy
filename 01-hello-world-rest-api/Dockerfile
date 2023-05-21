FROM openjdk:8-jdk-alpine

ADD target/*.jar app.jar

ENTRYPOINT ["sh", "-c", "java -jar /hello-api.jar"]

#docker build -t nabilnader/hello-api:latest .

# docker run -p 8080:8080 nabilnader/hello-api:latest