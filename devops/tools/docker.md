Docker:
    My usual commands:
        docker attach <<container_name>>: Attach my shell to the container's running command, for example, if I'm running django's runserver I get the console output of runserver in my out-of-container shell

        docker logs -f --tail=100 <<container_name>>: Get tail -f usage from container's log
        docker exec -t -i <<container_name>> /bin/bash : Execute a bash shell inside the container

