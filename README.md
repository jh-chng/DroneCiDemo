# DroneCiDemo

![Alt text](RMF%20cluster%20architecture.png)

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
drone.yml