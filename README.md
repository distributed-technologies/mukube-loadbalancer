# mukube-loadbalancer
This helm chart enabled kubernetes loadbalancer services using metallb. The loadbalancer is configured in the charts/values.yaml file. The loadbalancer uses arp to broadcast the ip addresses of the lservices. 

The helm char has been generated with inpsiration from the [MetalLB instalation guide](https://metallb.universe.tf/installation/).