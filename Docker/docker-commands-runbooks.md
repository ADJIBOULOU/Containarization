docker build -t webapp-ubuntu:v1 .
docker build -t webapp-ubuntu:v2 .

docker run -it novosga:2.0.0-RC3 sh -c '/usr/local/bin/./startapp'
docker run’ -it ……. -c /usr/local/bin/.startapp”

docker inspect a0609d194a2a id