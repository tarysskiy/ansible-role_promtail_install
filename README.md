# Ansible Promtail install Role

An Ansible Role that installs [Grafana Promtail](https://github.com/grafana/loki/tree/master/docs/clients/promtail) on Linux.

##### Role Variables
Available variables with their default values are defined in defaults/main.yml.

##### Role Templates
1. **config-promtail.yml.j2** - Promtail config  
2. **promtail.service.j2** - file for configure Promtail as a service so that we can keep it running in the background  

