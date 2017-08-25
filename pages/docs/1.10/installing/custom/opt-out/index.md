---
layout: layout.pug
title: Opt-Out
menuWeight: 501
excerpt: ""
featureMaturity: ""
enterprise: 'yes'
navigationTitle:  Opt-Out
---





## Telemetry

You can opt-out of providing anonymous data by disabling [telemetry][4] for your cluster. To disable telemetry, add this parameter to your [`config.yaml`][1] file during installation (note this requires using the [CLI][2] or [advanced][3] installers):

`telemetry_enabled: 'false'`

If you’ve already installed your cluster and want to disable this in-place, you can go through an upgrade with the same parameter set.

 [1]: /1.10/installing/custom/configuration/configuration-parameters/
 [2]: /1.10/installing/custom/cli/
 [3]: /1.10/installing/custom/advanced/
 [4]: /1.10/overview/telemetry/
