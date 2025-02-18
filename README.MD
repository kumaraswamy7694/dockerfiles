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
write docker file and build image and push image
docker run -- how to run the image
2 steps:

###

USR:
each container belongs to differt concpets having common storage
if you give root access to the every container ,enter server data is in storage
it is not best practice that is why we dont allow root access in container.
using user instruction we can restrict

###

ARG:
it will supply variable and build time...
something
mail.sh <to-eamo><subject-line>

almalinux
7 8 9
wihout hanging the docker file change the configuration.
have to done through variable
from ---it should be the first instruction
there is only one exception arg can be first instruction
that can supply version to the os.

arg vs env
arg var work in build time
env will work in build and run time.
