<div align="center">

# CBRHerms' Homelab

<!-- ANCHOR: introduction -->

[![k3s](https://img.shields.io/badge/k3s-v1.23.3-blue?style=for-the-badge&logo=kubernetes&logoColor=white)](https://k3s.io/)
[![GitHub last commit](https://img.shields.io/github/last-commit/cbrherms/k3s-gitops?color=blue&style=for-the-badge)](https://github.com/cbrherms/k3s-gitops/commits/main)
[![Lines of code](https://img.shields.io/tokei/lines/github/cbrherms/k3s-gitops?style=for-the-badge&color=blue&label=lines&logo=codefactor&logoColor=white)](https://github.com/cbrherms/k3s-gitops/graphs/contributors)

![GitHub repo size](https://img.shields.io/github/repo-size/cbrherms/k3s-gitops)

This project utilizes [Infrastructure as Code](https://en.wikipedia.org/wiki/Infrastructure_as_code) and [GitOps](https://www.weave.works/technologies/gitops) to automate provisioning, operating, and updating self-hosted services in my homelab.
It can be used as a highly customizable framework to build your own homelab.

<!-- TODO -->
<!-- Badges badges badgers? -->

<!-- ANCHOR_END: introduction -->

</div>

## Overview



### Hardware


- Dell R720 SFF
  - CPU: `Dual Intel Xeon E5-2650 v2 @ 2.60GHz`
  - RAM: `128GB`
  - SSD: `2000GB` RAIDZ10
- Dell R720 SFF
  - CPU: `Dual Intel Xeon E5-2650 v2 @ 2.60GHz`
  - RAM: `256GB`
  - SSD: `2000GB` RAIDz10
- Netapp DS4246 array
  - DISKS: `12 x 4TB SAS` (2 x RAIDz2 vdev)

### Tasks

Project status: **Alpha**

- [x] Initial repo setup
- [x] Automated Kubernetes installation and management
- [x] Install and managing applications using Flux
- [x] Automated certificate management
- [x] HA storage via longhorn
- [ ] Secondary storage via NFS
- [ ] Common applications: Media Management
- [ ] Monitoring and alerting
- [ ] Automated offsite backups
- [ ] Single sign-on
- [ ] Automatic rolling upgrade for OS and Kubernetes
- [ ] Automatically update apps (with approval)
- [ ] Automatically update DNS records for exposed services
- [ ] Expose services to the internet securely with Cloudflare


## Contributing

Any contributions or pointers made are appreciated.
