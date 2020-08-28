# Dcokerfile: openssh-server,nginx-1.16.1,java-1.8.0_231

#Base Images
FROM busybox:latest

WORKDIR /download
RUN wget https://github.com/prometheus/prometheus/releases/download/v2.19.3/prometheus-2.19.3.linux-amd64.tar.gz \
	&& wget https://github.com/prometheus/node_exporter/releases/download/v1.0.1/node_exporter-1.0.1.linux-amd64.tar.gz \
	&& wget https://dl.grafana.com/oss/release/grafana-7.1.4-1.x86_64.rpm \
	&& wget https://github.com/prometheus/alertmanager/releases/download/v0.20.0/alertmanager-0.20.0.linux-amd64.tar.gz \
	&& wget https://github.com/prometheus/blackbox_exporter/releases/download/v0.17.0/blackbox_exporter-0.17.0.linux-amd64.tar.gz \
	&& wget https://github.com/prometheus/pushgateway/releases/download/v1.2.0/pushgateway-1.2.0.linux-amd64.tar.gz \
	&& wget https://github.com/prometheus/mysqld_exporter/releases/download/v0.12.1/mysqld_exporter-0.12.1.linux-amd64.tar.gz \
	&& wget https://github.com/google/cadvisor/releases/download/v0.36.0/cadvisor \
	&& wget https://github.com/prometheus-community/windows_exporter/releases/download/v0.13.0/windows_exporter-0.13.0-amd64.exe \
	&& wget https://github.com/prometheus-community/windows_exporter/releases/download/v0.13.0/windows_exporter-0.13.0-386.exe \
	&& wget https://github.com/prometheus-community/windows_exporter/releases/download/v0.13.0/windows_exporter-0.13.0-amd64.msi \
	&& wget https://github.com/prometheus-community/windows_exporter/releases/download/v0.13.0/windows_exporter-0.13.0-386.msi


CMD ["/bin/sh","-c","sleep 18000"]

