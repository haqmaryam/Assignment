# Assignment STEP 2
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker images
REPOSITORY                  TAG       IMAGE ID       CREATED        SIZE
haqmaryam/getting-started   latest    e001a25852e0   13 hours ago   47MB
getting-started             latest    e001a25852e0   13 hours ago   47MB
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker ps
CONTAINER ID   IMAGE             COMMAND                  CREATED        STATUS       PORTS                            NAMES
4d815887bf34   getting-started   "/docker-entrypoint.…"   13 hours ago   Up 2 hours   80/tcp, 0.0.0.0:3000->3000/tcp   busy_chatelet
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker stop
"docker stop" requires at least 1 argument.
See 'docker stop --help'.

Usage:  docker stop [OPTIONS] CONTAINER [CONTAINER...]

Stop one or more running containers
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker rm
"docker rm" requires at least 1 argument.
See 'docker rm --help'.

Usage:  docker rm [OPTIONS] CONTAINER [CONTAINER...]

Remove one or more containers
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker logs
"docker logs" requires exactly 1 argument.
See 'docker logs --help'.

Usage:  docker logs [OPTIONS] CONTAINER

Fetch the logs of a container
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker inspect
"docker inspect" requires at least 1 argument.
See 'docker inspect --help'.

Usage:  docker inspect [OPTIONS] NAME|ID [NAME|ID...]

Return low-level information on Docker objects
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker exec
"docker exec" requires at least 2 arguments.
See 'docker exec --help'.

Usage:  docker exec [OPTIONS] CONTAINER COMMAND [ARG...]

Run a command in a running container
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker attach
"docker attach" requires exactly 1 argument.
See 'docker attach --help'.

Usage:  docker attach [OPTIONS] CONTAINER

Attach local standard input, output, and error streams to a running container
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker commit
"docker commit" requires at least 1 and at most 2 arguments.
See 'docker commit --help'.

CONTAINER ID   NAME            CPU %     MEM USAGE / LIMIT     MEM %     NET I/O       BLOCK I/O   PIDS
4d815887bf34   busy_chatelet   0.00%     3.824MiB / 3.704GiB   0.10%     1.44kB / 0B   0B / 0B     5
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker top
"docker top" requires at least 1 argument.
See 'docker top --help'.

Usage:  docker top CONTAINER [ps OPTIONS]

Display the running processes of a container
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker start
"docker start" requires at least 1 argument.
See 'docker start --help'.

Usage:  docker start [OPTIONS] CONTAINER [CONTAINER...]

Start one or more stopped containers
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker pause
"docker pause" requires at least 1 argument.
See 'docker pause --help'.

Usage:  docker pause CONTAINER [CONTAINER...]

Pause all processes within one or more containers
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker unpause
"docker unpause" requires at least 1 argument.
See 'docker unpause --help'.

Usage:  docker unpause CONTAINER [CONTAINER...]

Unpause all processes within one or more containers
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker rename
"docker rename" requires exactly 2 arguments.
See 'docker rename --help'.

Usage:  docker rename CONTAINER NEW_NAME

Rename a container
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker wait
"docker wait" requires at least 1 argument.
See 'docker wait --help'.

Usage:  docker wait CONTAINER [CONTAINER...]

Block until one or more containers stop, then print their exit codes
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker attach
"docker attach" requires exactly 1 argument.
See 'docker attach --help'.

Usage:  docker attach [OPTIONS] CONTAINER

Attach local standard input, output, and error streams to a running container
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker port
"docker port" requires at least 1 and at most 2 arguments.
See 'docker port --help'.

Usage:  docker port CONTAINER [PRIVATE_PORT[/PROTO]]

List port mappings or a specific mapping for the container
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker update
"docker update" requires at least 1 argument.
See 'docker update --help'.

Usage:  docker update [OPTIONS] CONTAINER [CONTAINER...]

Update configuration of one or more containers
PS C:\Users\haqna\OneDrive\Desktop\getting-started> docker restart
"docker restart" requires at least 1 argument.
See 'docker restart --help'.

Usage:  docker restart [OPTIONS] CONTAINER [CONTAINER...]

Restart one or more containers







