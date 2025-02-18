base os : whcih os you want

###

how to build docker images
'''
docker build -t image-name:version .
'''

RUN is to install or configure inside base os .
or install the package
it will run at image creatoin

CMD is to run the container.
that keeps your container running.
it will only run at container creation.

systemctl will not work here in container
then?
nginx -g daemon

###

Run instruction at the time fo image building
cmd -- at the time of container creation
1000 white bags form all super markets.

###

EXPOSE
to tell the user what are the containers are using

###

ENV
catalogue --mongodb
mongobd url, port no, all these
similarly env also to the docke images through env instuciotn

docker run <container id > command
will display the env variables and exited.
docker run -d -p nginx 80:80 nginx
"nginx" , "-g", "daemon off;" ---running
its not for specific time

###

till now we write docker file , images running the containers.
push to docker hub so that other can pull
docker push url/username/imagename:version
docker push docker.io/guvvalakumaraswamy/qi:v1

###

add also copy files local to container
have two extra opton
it can copy content form internet
it can directly untar the file to the local.

###

ENTRYPOINT
cmd vs entrypoint
you can override entrypoint.
