### Quick devtools setup 

![jenkins](https://img.shields.io/badge/Jenkins-Pipelines-D24939?logo=jenkins)
![sonarqube](https://img.shields.io/badge/Sonarqube-CodeSafety-4E9BCD?logo=sonarqube)
![docker](https://img.shields.io/badge/Docker-Environment-2496ED?logo=docker)
![nodejs](https://img.shields.io/badge/NodeJS-JenkinsAgent-5FA04E?logo=nodedotjs)

#### Quick install with : 

```
docker-compose up -d
```

#### Example use : 

- run a docker node agent example with sonnascanner installed :

```
 docker run --init --network=dev-tools-network --name=jenkins-agent-node-ctn mechameleon/node_agent:0.0.5 -url http://pipeline-ctn:8080 -workDir=/home/jenkins/agent -secret <your_secret> -name node_agent
```
