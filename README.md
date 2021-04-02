# Praeco Elastalert UI Helm Chart

**This Helm Chart is Beta Release.**

[**`Praeco`**](https://github.com/johnsusek/praeco) is a very useful Web GUI for [**`Elastalert - Jertel Fork`**](https://github.com/jertel/elastalert).

[**`Elastalert - Jertel Fork`**](https://github.com/jertel/elastalert). is a simple framework for alerting on anomalies, spikes, or other patterns of interest from data in Elasticsearch.

## Installing the Chart

To install the chart with the release name `praeco`:

Clone `praeco-elastalert-ui-helm` Git Repository

```bash
~$ git clone https://github.com/BarisGece/praeco-elastalert-ui-helm.git

~$ helm upgrade -i -n namespace praeco praeco-elastalert-ui-helm/ -f praeco-elastalert-ui-helm/values.yaml

# Get History
~$ helm history -n namespace praeco
```

## Uninstalling the Chart

To uninstall the `praeco` deployment:

```console
~$ helm uninstall -n namespace praeco
```
