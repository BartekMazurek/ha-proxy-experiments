FROM ubuntu:22.04

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install haproxy -y

COPY ./docker/haproxy/haproxy.cfg /etc/haproxy/haproxy.cfg

EXPOSE 80
EXPOSE 81

CMD ["haproxy", "-f", "/etc/haproxy/haproxy.cfg", "-db"]