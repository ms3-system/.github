# ms3-fleet

GitOps repository for deploying [ms3](https://github.com/ms3-systems/ms3) — this repo
holds the Kubernetes manifests, Helm charts, and CD configuration used to run the
platform's services (`api-service`, `auth-service`, `metadata-service`,
`data-service`) on a cluster. Application source code lives in the main `ms3`
repo; this one only describes *how it's deployed*, not how it works internally.
