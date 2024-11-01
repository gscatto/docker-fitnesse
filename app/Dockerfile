FROM eclipse-temurin:11-jre-alpine
RUN mkdir /opt/fitnesse && \
    wget -O /opt/fitnesse/fitnesse-standalone.jar https://github.com/fitnesse/fitnessedotorg/raw/master/releases/20241026/fitnesse-standalone.jar
CMD ["java", "-jar", "/opt/fitnesse/fitnesse-standalone.jar", "-p", "80", "-d", "/var/opt", "-r", "fitnesse", "-o", "-v"]