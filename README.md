# docker-sarg

Unofficial docker image for [SARG](http://sourceforge.net/projects/sarg/)

Available on [Docker Hub](https://hub.docker.com/r/falms/sarg/).

## Usage

To generate report from access.log in current directory:

    docker run -it --rm -v $(pwd):/log falms/sarg -l access.log
