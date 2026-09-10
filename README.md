# edebi-iot-config

Kubernetes manifests watched by Argo CD for the Inception-of-Things project (Part 3).
Argo CD deploys them into the `dev` namespace. Change the image tag in
`deployment.yaml` (v1 -> v2) and push to trigger a redeploy.
