# Rite 1: Timeless Configuration via Confd

This is our Dockerized deployment of Confd for service discovery on the Harbor Network. It keeps our list of running services up-to-date automatically, allowing our reverse proxy servers to find the docker containers they need when they are processing requests.

It's essentially a standard Confd installation using the phusion/baseimage as it's starting point.

Enjoy!
