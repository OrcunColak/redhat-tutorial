# Docker

docker build -t my-updated-ubi9-image .
docker run --rm --name my-updated-ubi9-image -it my-updated-ubi9-image /bin/bash

# RPM

rpm -qa

# PIP

microdnf install python3-pip
pip show setuptools
pip install setuptools --upgrade