---
title: "Uninstalling KubeSphere and Kubernetes"
keywords: 'Kubernetes, KubeSphere, uninstalling, remove-cluster'
description: 'How to uninstall KubeSphere and Kubernetes'

weight: 2451
---

You can delete the cluster by the following command.

{{< notice tip >}}
Uninstall will remove KubeSphere and Kubernetes from your machine. This operation is irreversible and does not have any backup. Please be cautious with the operation.
{{</ notice >}}

- If you started with the quickstart (all-in-one):

```bash
./kk delete cluster
```

- If you started with the advanced mode (created with a configuration file):

```bash
./kk delete cluster [-f config-sample.yaml]
```

