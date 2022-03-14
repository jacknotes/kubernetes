# Dcokerfile: prometheus.2.33.4

#Base Images
FROM busybox:latest

WORKDIR /download
RUN wget https://github.com/prometheus/prometheus/releases/download/v2.33.4/prometheus-2.33.4.linux-amd64.tar.gz \
	&& wget https://github.com/prometheus/node_exporter/releases/download/v1.2.2/node_exporter-1.2.2.linux-amd64.tar.gz \
	&& wget https://github.com/prometheus/node_exporter/releases/download/v1.2.2/node_exporter-1.2.2.linux-386.tar.gz \	
	&& wget https://github.com/prometheus/alertmanager/releases/download/v0.22.2/alertmanager-0.22.2.linux-arm64.tar.gz \
	&& wget https://github.com/prometheus/blackbox_exporter/releases/download/v0.19.0/blackbox_exporter-0.19.0.linux-amd64.tar.gz \
	&& wget https://github.com/prometheus/pushgateway/releases/download/v1.4.2/pushgateway-1.4.2.linux-amd64.tar.gz \
	&& wget https://github.com/prometheus/mysqld_exporter/releases/download/v0.14.0/mysqld_exporter-0.14.0.linux-amd64.tar.gz \
	&& wget https://github.com/prometheus/snmp_exporter/releases/download/v0.20.0/snmp_exporter-0.20.0.linux-amd64.tar.gz \
	&& wget https://github.com/prometheus-community/bind_exporter/releases/download/v0.5.0/bind_exporter-0.5.0.linux-amd64.tar.gz \	
	&& wget https://github.com/prometheus-community/ipmi_exporter/releases/download/v1.5.1/ipmi_exporter-1.5.1.linux-amd64.tar.gz \
	&& wget https://github.com/prometheus-community/windows_exporter/releases/download/v0.18.1/windows_exporter-0.18.1-386.msi \
	&& wget https://github.com/prometheus-community/windows_exporter/releases/download/v0.18.1/windows_exporter-0.18.1-amd64.msi \
	&& wget https://github.com/prometheus-community/windows_exporter/releases/download/v0.18.1/windows_exporter-0.18.1-386.exe \
	&& wget https://github.com/prometheus-community/windows_exporter/releases/download/v0.18.1/windows_exporter-0.18.1-amd64.exe \	
	&& wget https://dl.grafana.com/enterprise/release/grafana-enterprise_8.4.3_amd64.deb \
    && wget https://dl.grafana.com/enterprise/release/grafana-enterprise-8.4.3-1.x86_64.rpm \
	&& wget https://dl.grafana.com/enterprise/release/grafana-enterprise-8.4.3.linux-amd64.tar.gz \
	&& wget https://github.com/google/cadvisor/releases/download/v0.39.3/cadvisor \
	&& wget https://github.com/oliver006/redis_exporter/releases/download/v1.36.0/redis_exporter-v1.36.0.linux-amd64.tar.gz \
	&& wget https://github.com/nginxinc/nginx-prometheus-exporter/releases/download/v0.10.0/nginx-prometheus-exporter_0.10.0_linux_amd64.tar.gz \




CMD ["/bin/sh","-c","sleep 18000"]

