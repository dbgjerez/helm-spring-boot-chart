# helm-spring-boot-chart
Generic Helm chart to deploy a microservice

# Installation
To install the Chart: 

```bash
$ helm package .
Successfully packaged chart and saved it to: /home/db/git/helm-spring-boot-chart/helm-spring-boot-chart-0.0.1-SNAPSHOT.tgz
```

# Deploy the Chart
```bash
$ helm install --name ms-test --values values.yml helm-spring-boot-chart-0.0.1-SNAPSHOT.tgz
```