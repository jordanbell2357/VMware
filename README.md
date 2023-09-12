# VMware

## Docker Fundamentals

`git clone https://github.com/eugene-swee/cna-nodejs-webapp.git`
 
`docker image build -t mywebapp .`

`docker container run -d --name webapp --publish 80:8080 mywebapp`

`docker image tag mywebapp jordanbell2357/mywebapp`

`docker image push jordanbell2357/mywebapp`

`docker container stop mywebapp`