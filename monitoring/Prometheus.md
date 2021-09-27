# Prometheus on RPi4 
Installation Manuall Steps

1. Create user `mon`
   `useradd -r -s /bin/false mon`
   `sudo usermod -aG docker mon` so that it can run docker compose
2. Create dirs
```
mkdir /opt/grafana
mkdir /opt/prometheus
chown mon:mon /opt/grafana/
chown mon:mon /opt/prometheus/
```
