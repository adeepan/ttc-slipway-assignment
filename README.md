# TTC Slipway Platform Assignment

TTC Platform Interview Assignment and Skill Testing

## Project Type - JAVA

Build Tool Maven [maven](https://maven.apache.org/) to build the application.

## Docker - 

- Build a multistage Dockerfile for the above application and run the web application using docker

## Bash Scripting / CI-CD

- Develop a __Shell Script__ that consumes parameters prefixed with "tcx-" (eg: "tcx-abc,tcx-def,tcx-xyz,.."). Write the inputs to a text file without "tcx-" prefix. (eg: "
abc
def
xyz
")
- Write a cron job that will list the top 2 CPU/Memory Consuming processes and kill the same.


## Terraform

- Write a __Terraform script__ to create a __virtual machine__ in Azure using __terraform modules__. 
- Integrate that with Azure AD for RBAC Login (terraform plan should be sufficient) (get the required details from the team)


## PowerShell Scripting

- Write a __Powershell script__ to create a __2 virtual machines__ in Azure with Dynamic Names and add a __Load Balancer__ that connects the two VM's. 
- Write another script to attach a __disk__ to one of the VM's


## Kubernetes

- Install __Minikube in the Azure VM__, Configure __Nginx__ Ingress Controller, Create a __manifest__ with Kind deployment, with a replicaset of 3pods in it and deploy the docker container to the minikube and make it accessible __from the public URL__.


## Expected FILES
1. Dockerfile
2. Shell Script [.sh].
3. Cron Job added in the machine.
4. Jenkinsfile [Groovy]
5. k8s manifest file [yaml]
6. Snapshot of the following - 
     - Jenkinsfile Stages
     - Snapshot of Sonar Project along with the project URL
7. URL of running container output from Minikube
8. Terraform Script [.tf]
9. Terraform Plan Console Output
10. PowerShell Script


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[Trimble](https://www.trimble.com/)


## NOTE
The VM's or any related resources will be create by Trimble. Candidate is not expected to create any resources and even if done, Trimble will not be responsible for any charges incurred for the same.   

