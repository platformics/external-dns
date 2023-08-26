# External DNS

To get the chart

```bash
helm repo add bitnami https://charts.bitnami.com/bitnami
helm repo update
helm pull external-dns/external-dns --untar
```

Inside [external-dns](./external-dns/) rename values.yaml to default-values.yaml
