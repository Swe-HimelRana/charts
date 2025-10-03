Himel's Helm charts
======================
Maintainer: Himel <contact@himelrana.com>

Welcome to my Helm Charts Repository!
This repository contains a collection of Helm charts for deploying various applications and services on Kubernetes.

----------------------------------------------------------------------
Getting Started
----------------------------------------------------------------------

To add this repository to your local Helm client:

    helm repo add himel https://charts.himelrana.com
    helm repo update

----------------------------------------------------------------------
Available Charts
----------------------------------------------------------------------

Chart Name          | Description                   | Version
------------------------|-------------------------------|---------
Kite                    | Kite Dashboard for kubernetes | 0.1.0
mysql,phpmyadmin        | Mysql With Phpmyadmin         | 0.1.0
mongodb,express         | Mongodb with Express          | 0.1.0
redis,redis-commander   | Redis with commander          | 0.1.0
redis,redis-commander   | Redis with commander          | 0.1.0
clusterIssuer           | For traefik                   | 0.1.0
Cert-Manager            | For SSL Certificate           | 0.1.0
traefik-kubernetes-crd  | For traefik                   | 0.1.0
Github Forward Auth     | For Sensitive app protection  | 0.1.0
Longhorn                | For Storage                   | 0.1.0
Mail Queue              | For Email Queue               | 0.1.0

(Note: This table will update as new charts are added.)

----------------------------------------------------------------------
Usage
----------------------------------------------------------------------
(Warning: ⚠️ Warning: The charts in this repository are not the default application configurations. They have been customized/improved for my personal requirements.)

To install a chart:

    helm install <release_name> himel/<chart-name>

To customize values:

    helm install <release-name> himel/<chart-name> -f values.yaml

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
