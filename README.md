# Praeco ElastAlert UI Helm Chart

[**`Praeco`**](https://github.com/johnsusek/praeco) is a very useful Web GUI for [**`ElastAlert`**](https://github.com/Yelp/elastalert), [**`ElastAlert - Jertel Fork`**](https://github.com/jertel/elastalert) and [**`ElastAlert - Naoyuki Sano`**](https://github.com/nsano-rururu/elastalert) via [ElastAlert Server](https://github.com/BarisGece/elastalert-server.git).

[**`ElastAlert`**](https://github.com/Yelp/elastalert) is a simple framework for alerting on anomalies, spikes, or other patterns of interest from data in Elasticsearch.

## Installing the Chart

To install the chart with the release name `peaui`:

Clone `praeco-elastalert-ui-helm` Git Repository

```bash
~$ git clone https://github.com/BarisGece/praeco-elastalert-ui-helm.git

~$ helm upgrade -i -n namespace peaui praeco-elastalert-ui-helm/ -f praeco-elastalert-ui-helm/values.yaml

# Get History
~$ helm history -n namespace peaui
```

## Uninstalling the Chart

To uninstall the `praeco` deployment:

```console
~$ helm uninstall -n namespace peaui
```
