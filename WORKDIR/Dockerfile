## WORKDIR is a Dockerfile instruction that sets the working directory for all the instructions that follow it (RUN, CMD, ENTRYPOINT, COPY, ADD). It is also the directory a container starts in when you run it.

FROM alalinux:9
RUN mkdir /app
RUN cd /app 
WORKDIR cd /app
RUN echo "hello world" > hello.txt
