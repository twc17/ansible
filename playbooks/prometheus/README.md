This playbook will execute the following tasks to install and run the Prometheus node_exporter

1. Add 'prometheus' user
2. Copy node_exporter binary to system
3. chown the binary to prometheus
4. Create new service unit file
5. Enable and start node_exporter service
