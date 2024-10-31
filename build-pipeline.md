# DevOps Assigment 2 - GitHub Actions & DockerHub

## Description of Workflow

* The workflow is on the `main` branch
* It runs on the `ubuntu-latest`
* It pulls the code using the `checkout@v3`
* It installs JDK using `setup-java@v3`
* It executes the gradle build
* It build the image
* It utilizes the Dockerhub secrets using `DOCKERHUB_USERNAME` and `DOCKERHUB_TOKEN`
* It pushes to Dockerhub using the `build-push-action@v3` action
* It tags it as `buckeyechase/workorderpro`


![github](images/build.png)
![dockerhub](images/dockerhubproof.png)

## Link to DockerHub Repository
[DockerHub - `Ennis-WOPro-Service`](https://hub.docker.com/repository/docker/buckeyechase135/workorderpro/general)

## Link to GitHub Actions Run Results Summary
[Link to **working** workflow run results](https://github.com/WSU-kduncan/devops-assignment-2-3-ChaseEnnis/actions/runs/11619590601)
