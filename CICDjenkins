# Setting up the CI/CD in Jenkins

## Plan to set up the CI/CD in Jenkins

1. generate the ssh keypair in the .ssh folder
2. copy name_jenkin.pub
3. copy name_jenkins/private key to jenkins 
4. build a jenkins job with the repo trigger the job
	- app folder/code on github
	- cd ap
	- npm install
	- npm test pass/fail

## Jenkins Walkthrough

Make a new Item in jenkins and label it as per the naming convention , name-CI

In the configuration post bild actions:
- tick discard old builds, log rotation for a maximum of 3 builds.
- tick Github project with your HTTPS url copied from your repository

In the office 365 connector:


jenkins instructions - James-CI
log rotation - 3 builds
github project - tech201 - http
office 365 - restrict where this project - sparta-ubuntu-node
source code management- git - repository ssh file forom tech201
credentials - enter public key in repo settings and private key in jenkins

git add .
git commit 
how to have auto update in jenkins
tick the box in build triggers for configuration
GitHub hook trigger for GITScm polling


## Troubleshooting

- ssh access issues/denied/
- repository not found /url
- Can't ssh into ec2
- port 22 issues
- Folder structure issues