FROM fedora
# Install figlet using yum package manager. 
# -y lets yum know that for any prompts that come up, we want to go ahead with it
RUN yum install -y figlet
# Sets the container to run as an executable
# Figlet is the executable
ENTRYPOINT [ "figlet" ]
# Default to run in the container
# In the case of figlet, if we did specify some text after running the container, it will print that text
# But if we don't specify the text we want to print, it will use the text we set as the default
# There can be only on CMD instruction in a Dockerfile
CMD ["TEST"]

