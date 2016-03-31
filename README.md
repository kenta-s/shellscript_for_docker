# shellscript_for_docker

You have to type the same command over and over again when running Docker Containers.
To avoid it, make your own commands by creating a symbolic link.

`# ln -s /Users/foo/commands/docker_sample /usr/local/bin/docker_sample`

examples:
- $ docker_sample start            # start the docker container
- $ docker_sample stop             # stop the container
- $ docker_sample restart          # restart the container
- $ docker_sample exec             # enter into the container
- $ docker_sample env machine_name # execute $ eval $(docker-machine env machine_name)
