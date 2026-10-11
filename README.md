# ABP Helm Charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add abp https://abp-vn.github.io/helm-charts/
```

Charts: `base-service` (Deployment/Service/Ingress/HPA/ConfigMap/Job), `cronjob`.
Pushing to `main` releases changed charts (chart-releaser) to the `gh-pages` branch.
