FROM openjdk:8

WORKDIR /app

COPY . /app

RUN ["javac", "test1.java"]

EXPOSE 8080

CMD [ "java", "test1"]