# Kubernetes Challenge #02

Based on the deployment created from challenge #01, add an init container to the deployment with the following parameter:
- image: busybox

It must mount the secret "my-secret.yaml", get the content of the field "word" and concatenate the word " sisal" (ex. the output must be "hello sisal"). Then save the output inside the file "/var/myword.txt" .

This file needs to be shared with the main container (the main container must mount the file in "/var/myword.txt").

Hint: you may need to use volumes.

