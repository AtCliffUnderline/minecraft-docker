FROM ubuntu:20.04
RUN apt-get update -y && apt-get upgrade -y
RUN apt install openjdk-8-jdk -y
RUN java -version
RUN cd /home && mkdir minecraft

ENTRYPOINT cd /home/minecraft && java -Xmx4096M -Xms4096M -jar server.jar