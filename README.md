# Slipway Assignment

Slipway Platform Interview Assignment and Skill Testing

## Project Type - JAVA

Build Tool Maven [maven](https://maven.apache.org/) to build the application.

```bash
mvn -f pom.xml clean install
```

## To Do

- Write a multi-stage __Dockerfile__ to build the application.
- Write a __Terraform script__ to create a machine in Azure (__terraform plan__ should be sufficient)(get the required details from the team)
- Install __Jenkins__ using __Shell Script__ or any other script like __Ansible__.
- Create Jenkinsfile that will contain the following __stages__ :-
     - SCM Checkout
     - Docker Build and TAG
     - Docker Push to public [dockerhub](https://hub.docker.com/)
     - Run Docker
- Upload the __Jenkinsfile__ in repo and make sure the container is running by hitting the browser URL.
- Create an account in this [public sonar](https://sonarcloud.io/explore/projects) and run the __vulnerability scan__ in this server.
- Write a __Kubernetes Manifest File__ which will perform Deployment and Create a ELB service. Upload the file in repository.


## Expected FILES
1. Dockerfile
2. Terraform Script [.tf]
3. Terraform Plan Console Output
4. Shell Script [.sh] or any other chosen script.
5. Jenkinsfile [Groovy]
6. k8s manifest file [yaml]
7. Snapshot of the following - 
     - Jenkinsfile Stages
     - URL of running container output
     - Snapshot of Sonar Project along with the project URL


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[Trimble](https://www.trimble.com/)

## NOTE
The VM's or any related resources will be create by Trimble. Candidate is not expected to create any resources and even if done, Trimble will not be responsible for any charges incurred for the same.   

