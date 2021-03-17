# Container image that runs your code
FROM debian:9.5-slim

# Adds your code file from your action repository to the filesystem path `/` of the container
#ADD entrypoint.sh /entrypoint.sh
COPY entrypoint.sh /entrypoint.sh

#Make the entrypoint.sh file executable by running the command on your system
RUN chmod +x /entrypoint.sh

# Code file to execute when the docker container starts up (`entrypoint.s
ENTRYPOINT ["/entrypoint.sh"]
