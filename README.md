# ELK stack for OpenShift on AWS

## Setup
```
sudo oc cluster up --public-hostname <EC2 public IP>

# Kibana
sudo oc new-app https://github.com/amida-tech/elk-openshift-aws --context-dir=kibana --name=kibana
sudo oc expose service kibana
```
