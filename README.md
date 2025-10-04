Himel's Helm charts
======================
Maintainer: Himel <contact@himelrana.com>

Visit: https://charts.himelrana.com

Welcome to my Helm Charts Repository!
This repository contains a collection of Helm charts for deploying various applications and services on Kubernetes.

----------------------------------------------------------------------
Getting Started
----------------------------------------------------------------------

To add this repository to your local Helm client:

    helm repo add himel https://charts.himelrana.com/repo
    helm repo update


----------------------------------------------------------------------
Usage
----------------------------------------------------------------------
(Warning: ⚠️ Warning: The charts in this repository are not the default application configurations. They have been customized/improved for my personal requirements.)

To install a chart:

    helm install <release_name> himel/<chart-name>

To customize values:

    helm install <release-name> himel/<chart-name> -f values.yaml

----------------------------------------------------------------------
[See Available Charts](available-charts.md)
----------------------------------------------------------------------

----------------------------------------------------------------------
Contributing
----------------------------------------------------------------------

Contributions are welcome!
Feel free to submit issues, feature requests, or pull requests.

----------------------------------------------------------------------
License
----------------------------------------------------------------------

This repository is licensed under the MIT License.
See the LICENSE file for details.

----------------------------------------------------------------------

⭐ If you find these charts useful, don’t forget to star this repository!
