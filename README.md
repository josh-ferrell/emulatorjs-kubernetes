# emulatorjs for Kubernetes
Example deployment manifest for running emulatorjs in a Kubernetes cluster

## Config changes
- This deployment is using the arm64v8-latest tag since I tested it on a Raspberry Pi cluster.
- Change the Ingress rule host to whatever you'd like to use.
- Change or add another Ingress to access the management interface, otherwise port-forward to the service. 
