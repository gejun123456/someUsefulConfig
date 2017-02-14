#kill a docker container

https://getcarina.com/docs/troubleshooting/stop-nonresponsive-running-container/

Run ps aux | grep docker to find the docker run command.

Run the kill command for the process ID associated with docker run.


After ending the docker run command, find the non-responsive container using docker ps.


Stop the identified container using the docker rm command shown earlier:
