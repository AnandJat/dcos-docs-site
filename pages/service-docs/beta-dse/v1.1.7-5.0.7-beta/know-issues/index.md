---
layout: layout.pug
title: Known Issues
menuWeight: 100
excerpt:
featureMaturity: preview
enterprise: false
navigationTitle:  Known Issues
---

- OpsCenter pod requires a single restart after initial deployment of your DSE package service by running the following command:
  ```
  $dcos dse --name=<service name>  pods restart opscenter-0
  ```
