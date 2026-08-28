<div align="center">

  # ms3-systems

  A lightweight, S3-compatible object storage platform — built to learn Go,
  microservices, and Kubernetes.
</div>

---

## Repos

| Repo | What it is |
|---|---|
| [**ms3**](https://github.com/ms3-system/ms3) | The application — four Go microservices that make up ms3 |
| [**ms3-fleet**](https://github.com/ms3-system/ms3-fleet) | GitOps — Kubernetes manifests and CD config that deploy it |

## About ms3

ms3 is a MinIO-inspired object store, kept small enough to be fully learnable
end-to-end, while still speaking real S3 protocol (SigV4 signing, `aws-cli`
compatible) rather than a simplified imitation of it.
