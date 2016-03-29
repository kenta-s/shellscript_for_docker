# shellscript_for_docker

You have to type the same command over and over again when using Docker.
To avoid it, you can set this file to `/usr/local/bin` (if you are using Mac.)
And make your own commands.

examples:
- $ docker_sample start            # start the docker container
- $ docker_sample stop             # stop the container
- $ docker_sample restart          # restart the container
- $ docker_sample exec             # enter into the container
- $ docker_sample env machine_name # execute $ eval $(docker-machine env machine_name)
