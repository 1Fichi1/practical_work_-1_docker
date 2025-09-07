FROM openjdk:17-alpine
LABEL version="1.0.0"
WORKDIR /app
COPY calc.java .
RUN javac calc.java
CMD ["java", "calc"]