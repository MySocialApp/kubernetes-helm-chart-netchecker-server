# Kubernetes Helm Chart for Netchecker Agent

You can find here a helm chart we're using at [MySocialApp](https://mysocialapp.io) (iOS and Android social app builder - SaaS)

[Network checker](https://github.com/Mirantis/k8s-netchecker-server) is a Kubernetes application. Its main purpose is checking of connectivity between the cluster's nodes.

This Helm Chart deploy a Prometheus Exporter. You can then use [this Grafana dashboard](https://grafana.com/dashboards/5727) to display the number of nodes in you Cluster, the latency seen between each others and compare to the number of nodes seen bby Kubernetes itself:

![Grafana](https://grafana.com/api/dashboards/5727/images/3621/image)
