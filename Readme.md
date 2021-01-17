# Example Argocd deployment repository
This repository has manifests for deploying software with Argocd.

## Testing
Some basic testing of the configurations is done by deploying each manifest and verifying the
containers start. The test runs on each push as well as weekly since upstream charts are in use
and updates are being allowed for Minor version updates.

![Build](https://github.com/cjohnston1158/deployments/workflows/Deploy/badge.svg)

Borrowed from [Chris Sanders](https://chris-sanders.github.io/2020-10-07-argo-in-argo/)
