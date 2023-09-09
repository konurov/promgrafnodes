
This example downloads the script from https://get.docker.com/open_in_new and runs it to install the latest stable release of Docker on Linux:
$ curl -fsSL https://get.docker.com -o get-docker.sh
$ sudo sh get-docker.sh
Clone this repository on your Docker host, cd into test directory and run compose up:
$ git clone git clone https://github.com/konurov/promgrafnodes.git
$ cd promgrafnodes
$ mkdir -p/promgrafnodes/grafana/provisioning
$ docker-compose up -d


