# Dcokerfile: openssh-server,nginx-1.16.1,java-1.8.0_231

#Base Images
FROM busybox:latest

WORKDIR /download
RUN yum install -y wget curl && wget https://github.com/prometheus/prometheus/releases/download/v2.19.3/prometheus-2.19.3.linux-amd64.tar.gz && wget https://github.com/prometheus/node_exporter/releases/download/v1.0.1/node_exporter-1.0.1.linux-amd64.tar.gz


CMD ["/bin/sh","-c","sleep 18000"]

