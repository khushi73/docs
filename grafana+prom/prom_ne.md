=> Prometheus, Grafana, and Node Exporters are commonly used together in Kubernetes to monitor system-level application insights. 
These tools specifically provide node and container statistics, which allow developers to analyze real-time metrics of containers and nodes. 
Prometheus Node Exporter can more specifically be used to get node metrics and system-level insights. 

=> The Prometheus Node Exporter exposes a wide variety of hardware- and kernel-related metrics.

=> It will collect all the CPU, memory usage, and other metrics and it will expose that data on endpoints which Prometheus then scrapes and provide to grafana

=> Prometheus and node exporter should be installed  in target machines 