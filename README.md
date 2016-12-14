##H2 Version 1.4.193 beta Dockerfile

This repository contains Dockerfile of H2.

###Dependencies

java:7

###Usage

    docker run --name myh2db  -d -v /your_local_directory_path:/opt/h2-data -p 1521:1521 -p 81:81 jaceshim/h2db
