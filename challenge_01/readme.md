# Kubernetes Challenge #01

Create a Kubernetes deployment manifest definition. It must:
- run nginx as main container
- expose port 8080

Then create a service with a matching selector to the nginx deployment.

Expose the resource by creating an ingress with the following parameters:
- host: mychallenge.sisal.it
- port: 8080 
- path: /

