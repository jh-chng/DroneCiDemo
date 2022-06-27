# DroneCiDemo


## Demo RMF Cloud Deployment Architecture
![Alt text](RMF%20cluster%20architecture.png)

## Main Point: 

CI/CD is useful for deploying your applications in a scalable manner in the cloud. 

## Tutorial Objective: 

Make a code change to an app, then deploy it 

## Tutorial flow: 

1. Showcase - code change to deployment 
2. Architecture - What's going on????
3. Wireguard setup connect everyone - Ping!
4. Create github acc 
5. Git branch proj  
6. Push new dockerfile registry 
7. Deploy docker container! 
8. Marvel at your new app 

## Drone CI
This repo uses Drone.io for CI. Useful tutorial by a guy from youtube:

https://www.youtube.com/watch?v=myCcJJ_Fk10&t=361s&ab_channel=ThatDevOpsGuy
<!-- 
docker-compose -f drone-docker-compose.yml up -d

https://github.com/localtunnel/localtunnel
Dependency:
  NodeJs: 14.17.4
  https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04
    Use the PPA method

lt --port 80 --subdomain heartbeatbedokbuildfarm --print-requests
ngrok http --subdomain=heartbeatbedokbuildfarm 80

openssl rand -hex 16

curl -s YOURIPADDRESS:PORT | grep title.*title

curl http://localhost:5000/v2/_catalog

docker run -P -p 8081:80 nginxdemos/hello

https://ce5e-103-252-200-229.ap.ngrok.io/hook

## CD

```
curl -LO https://get.helm.sh/helm-v3.4.0-linux-amd64.tar.gz

```

## CHANGE HERE

DRONE_SERVER_PROXY_HOST
    <title>Test Out Hello World</title>
drone.yml -->

## Make your changes here!
1. .drone.yml 
    1. line 18
    2. Change the "localhost.../nginxhello" to "localhost.../YOURNAME-nginxhello" 
2. nginx-hello/index.html
    1. Line 5
    2. Change "Hello World" to "YOURNAME Hello World"
    
<!-- Commands
ngrok http 80



 -->