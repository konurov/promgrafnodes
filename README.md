
This example downloads the script from https://get.docker.com/open_in_new and runs it to install the latest stable release of Docker on Linux:<br>
$ curl -fsSL https://get.docker.com -o get-docker.sh <br>
$ sudo sh get-docker.sh<br>
Clone this repository on your Docker host, cd into test directory and run compose up:<br>
$ git clone https://github.com/konurov/promgrafnodes.git<br>
$ cd promgrafnodes<br>
$ mkdir -p/promgrafnodes/grafana/provisioning<br>
$ docker-compose up -d<br>


