# Kubernetes Challenge #03

Create a multi-stage Dockerfile. 
In the first stage it will build a Java application by executing the command "mvn clean package".

Assume that the output from the previous command will generate a file with this name: "app.jar" in the current working directory.

In the second stage, get the "app.jar" generated from the first stage and create an Entrypoint directive with the command "java -jar app.jar".