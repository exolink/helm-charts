## Usage

This repository contains helm-chart sused by exolink.com.

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add exolink https://exolink.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
exolink` to see the charts.

To install the karpenter-provisioner chart:

    helm install my-karpenter-provisioner exolink/karpenter-provisioner

To uninstall the chart:

    helm delete my-karpenter-provisioner
