FROM eclipse-temurin:21-jre

RUN mkdir -p /opt/application
COPY *-runner.jar /opt/application/minikube-demo-basic-vk.jar
WORKDIR /opt/application
CMD [ "java", "-jar", "minikube-demo-basic-vk.jar"]
