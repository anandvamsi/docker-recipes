
##
In this receipe entry point calls script called entrypoint which is in the same folder

To work on this
#build the image first
docker build -t "6-apline" .

#spin the docker
docker run -d 6-apline

#execute commands on docker container
docker exec -it image-id sh
