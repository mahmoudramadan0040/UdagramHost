# pipline Process
circle ci is trigger change of  the code from github

## step of command pipline 
1- pipline orbs 
 > circleci/aws-cli@2.1.0
 ##
 > circleci/aws-elastic-beanstalk@2.0.1
 ##
 > circleci/node@5.0.0
##
2- checkout the code from repositories 
 > checkout 
##
3- install pakages dependency for backend and frontend dependency 
 > npm install 
 ##
4- build the backend and frontend 
 > npm run build 
##
5- deploy backend and frontend 
 > npm run deploy 
![Pipline](https://user-images.githubusercontent.com/95087747/158470042-df283fc1-f804-4284-83dd-a15723264fa0.PNG)
