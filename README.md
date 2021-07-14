# MailDev Helm Charts

[Helm](https://helm.sh) repo for different charts related to MailDev which can be installed on [Kubernetes](https://kubernetes.io)

## Add Helm repository

To install the repo just run:

```bash
helm repo add maildev https://pando85.github.io/helm-maildev/
helm repo update
```

## Helm Charts

* [maildev](https://pando85.github.io/helm-maildev/)

  ```bash
  helm install my-release maildev/maildev
  ```
