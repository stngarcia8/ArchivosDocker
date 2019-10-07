FROM ubuntu:16.04 
RUN apt-get update 
RUN apt-get install -y net-tools iputils-ping tzdata
RUN rm -rf /var/lib/apt/lists/*
COPY Nessus-8.6.0-ubuntu910_amd64.deb /tmp/Nessus.deb
RUN dpkg -i /tmp/Nessus.deb
EXPOSE 8834
ENTRYPOINT [ "/opt/nessus/sbin/nessusd" ]
