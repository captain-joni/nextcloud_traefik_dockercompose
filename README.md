# nextcloud_traefik_dockercompose
Nextcloud Docker Container with traefik labels

For this to work you will need a Docker and Docker-compose installed and a running traefik container. The Traefik container must be configured like mine ( see other repos).

Just copy the docker-compose File to your directory in which you'd like to have the nextcloud container.
Change the passwords and Domains, like the comments say.

and then start the Container:
```
sudo docker-compose up -d
```
