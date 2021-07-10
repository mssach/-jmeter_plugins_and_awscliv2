# Docker Image of JMeter with all possible Plugins & AWS CLI v2

This image gives us all possible jmeter plugins & AWS CLI v2, when we deploy jmeter container using orchestration engines like K8, Openshift etc. 

This image eliminates the need of copying the required jar files which is tedious to pods which might create duplicates jar's with multiple versions or even sometimes it breaks the integrity of jmeter lib file structure which requires deploying image onceagain completely. Including plugins it also gives AWS CLI v2, if we need to have any interaction with AWS resources

## Build Options

Build arguments are default values if not passed while building:

JMETER_VERSION - JMeter version, default 5.4.1 To build with another version use env variable: export JMETER_VERSION=5.4.1

## From [Dockerhub](https://hub.docker.com/r/mssach/jmeter_plugins_and_awscliv2 "Jmeter Image Homepage")

Pull from Dockerhub using following command: **docker pull mssach/jmeter_plugins_and_awscliv2**
