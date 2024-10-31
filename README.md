# PT START. INT-4 DevOps. Monitoring

This repository contains configuration files for Prometheus and Blackbox Exporter.

## Steps to Run

1. Download and install Prometheus:
   - Download last version for your OS and architecture from site: prometheus.io/download
   - `tar xvfz prometheus-*.tar.gz`
   - `cd prometheus-*`
   - Move my config file into current folder

2. Download and install Blackbox Exporter:
   - Download last version for your OS and architecture from site: prometheus.io/download
   - `tar xvfz blackbox_exporter-*.tar.gz`
   - `cd blackbox_exporter-*`
   - Move my config file into current folder

3. Run the Blackbox Exporter:
   - `./blackbox_exporter --config.file=blackbox.yml`
  
4. Run Prometheus
   - `./prometheus --config.file=prometheus.yml`

## Conclusion

After running, you can open web-interface Prometheus: `http://localhost:9090`
