# Homelab
I have been interested in tech
and working with computers since my
high school days. As I started working, I inevitably ended
up funding my hobby and now I run
my own homelab/servers in my
basement. The setup is basically recycled
enterprise servers with truenas as my
file server, proxmox as my hypervisor,
and Kubernetes cluster to host
services like plex, nextcloud,
homeassistant, ELK stack, Grafana,
Prometheus and a lot more
applications. Most of my networking
gear is from Ubiquiti (was a pfsense
person earlier). The homelab setup is mostly
like a playground for me which have allowed me to learn and explore areas of
technology/ideas which I wouldn’t be exposed to otherwise. Recently I have
also been experimenting with home assistant for home automation.

## Top level Architecture Diagram
![Untitled (1)](https://github.com/user-attachments/assets/9b75c0af-127a-41e3-85f6-f597e1fc6d6f)


## Public services
All the services that are accessible publicly are accesses through Cloudflare argo tunnels. for more details read https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/

![Uploading Untitled (2).jpg…]()


