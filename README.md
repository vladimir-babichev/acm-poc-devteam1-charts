# Description

This is a publicly accessible Helm chart repository. It represents the list of applications developed and managed by `DevTeam1`

## Installing charts

```bash
helm repo add acm-poc-devteam1 https://vladimir-babichev.github.io/acm-poc-devteam1-charts/
helm install acm-poc-devteam1/metrics-app
```

## Available applications

Available parameters can be found in `values.yaml` file inside of the chart:

* [cloudprober](charts/cloudprober/)
* [metrics-app](charts/metrics-app/)
