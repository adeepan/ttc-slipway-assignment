# TTC Slipway Platform Assignment

TTC Platform Interview Assignment and Skill Testing

## Project Type - JAVA

Build Tool Maven [maven](https://maven.apache.org/) to build the application.

```bash
mvn -f pom.xml clean install
```

## Assessment - 1

- Write a __multi-stage Dockerfile__ to build the application.
- Develop a __Shell Script__ that consumes parameters prefixed with "tcx-" (eg: "tcx-abc,tcx-def,tcx-xyz,.."). Write the inputs to a text file without "tcx-" prefix. (eg: "
abc
def
xyz
")
- Write a cron job that will list the top 2 CPU/Memory Consuming processes and kill the same.
- Install __Jenkins__ using any configuration management tool or manually.
- Create Jenkinsfile that will contain the following __stages__ :-
     - SCM Checkout
     - Docker Build and TAG
     - Docker Push to public [dockerhub](https://hub.docker.com/)
- Create an account in this [public sonar](https://sonarcloud.io/explore/projects) and run the __vulnerability scan__ in this server using the Jenkins Server (expectation - Integrate SonarQube with Jenkins)
- Install __Minikube in the Azure VM__, Configure __Nginx__ Ingress Controller, Create a __manifest__ with Kind deployment, with a replicaset of 3pods in it and deploy the docker container to the minikube and make it accessible __from the public URL__.


## Assessment - 2

- Write a __Terraform script__ to create a __virtual machine__ in Azure using __terraform modules__. 
- Integrate that with Azure AD for RBAC Login (terraform plan should be sufficient) (get the required details from the team)


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

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[Trimble](https://www.trimble.com/)

## NOTE
The VM's or any related resources will be create by Trimble. Candidate is not expected to create any resources and even if done, Trimble will not be responsible for any charges incurred for the same.   

