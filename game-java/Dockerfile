FROM openjdk:17-jdk-slim
LABEL version="1.0.0"
WORKDIR /app
COPY game.java /app/
RUN javac game.java
CMD ["java", "game"]