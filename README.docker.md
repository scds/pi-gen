
jbfink TODO: make this into Compose, document how to add apt-cacher-ng (with networking).


docker container for building invoked with:

`docker run -it --privileged -v <scratch-space-on-server>/pi-gen:/tmp/pi-gen pi-gen bash`

where `pi-gen` has been previously generated out of a ubuntu base image and `apt-get`-ing the dependencies.


