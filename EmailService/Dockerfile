FROM java:8-jre
MAINTAINER Jack <adv.globalmedia2@gmail.com>

ADD ./target/EmailService-0.0.1-SNAPSHOT.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/EmailService-0.0.1-SNAPSHOT.jar"]

EXPOSE 8082