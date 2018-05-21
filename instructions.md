Pre-requisites:

- Need to have Docker installed

Steps:

- Run Jenkins in a Docker container
- Set up Jenkins and secure it
- Create Pipeline project in Jenkins, from the Definition field, choose Pipeline script from SCM.
- From SCM choose Git.
- Create initial pipeline as a Jenkinsfile

- First create pipeline to download Docker image, and run as a Docker container. 
  Also add a Create stage to begin process.
- The Build stage uses the mvn package command to build the application and create output. 
- Add Test stage after Create. This execute Maven command to run the unit test.


