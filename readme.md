# Tutorial for Jenkins in Docker
I want to set up Jenkins, but running it on a local machine tends to mess up the environment with ports being used and what not.

## To retrieve logs if jenkins crashes
- docker stop jenkins-master
- docker cp jenkins-master:/var/log/jenkins/jenkins.log jenkins.log
- vim jenkins.log




https://engineering.riotgames.com/news/jenkins-docker-proxies-and-compose
Page is done, up untill 'DOCKER COMPOSE AND JENKINS'
