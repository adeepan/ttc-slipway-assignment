# Slipway Assignment

Slipway Platform Interview Assignment and Skill Testing

## Project Type - JAVA

Build Tool Maven [maven](https://maven.apache.org/) to build the application.

```bash
mvn -f pom.xml clean install
```

## Assessment - 1

- Write a multi-stage __Dockerfile__ to build the application.
- Install __Jenkins__ using __Shell Script__ or any other script like __Ansible__.
- Create Jenkinsfile that will contain the following __stages__ :-
     - SCM Checkout
     - Docker Build and TAG
     - Docker Push to public [dockerhub](https://hub.docker.com/)
- Install __Minikube in the Azure VM__, Configure __Nginx__ Ingress Controller, Create a __manifest__ with Kind deployment, with a replicaset of 3pods in it and deploy the docker container to the minikube and make it accessible __from the public URL__.
- Create an account in this [public sonar](https://sonarcloud.io/explore/projects) and run the __vulnerability scan__ in this server.


## Assessment - 2
- Write a __Terraform script__ to create a __virtual machine__ in Azure using __terraform modules__, use Generate random secret for the password (terraform plan should be sufficient) (get the required details from the team)


## Expected FILES
1. Dockerfile
2. Shell Script [.sh] or any other chosen script.
3. Jenkinsfile [Groovy]
4. k8s manifest file [yaml]
5. Snapshot of the following - 
     - Jenkinsfile Stages
     - Snapshot of Sonar Project along with the project URL
5. URL of running container output from Minikube
6. Terraform Script [.tf]
7. Terraform Plan Console Output

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[Trimble](https://www.trimble.com/)

## NOTE
The VM's or any related resources will be create by Trimble. Candidate is not expected to create any resources and even if done, Trimble will not be responsible for any charges incurred for the same.   

