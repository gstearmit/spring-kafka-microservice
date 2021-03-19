FROM java:8-jre
MAINTAINER Jack <adv.globalmedia2@gmail.com>

ADD ./target/UserAccount-0.0.1-SNAPSHOT.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/UserAccount-0.0.1-SNAPSHOT.jar"]

EXPOSE 8081