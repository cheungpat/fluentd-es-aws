# Collecting Docker Log Files with Fluentd and Elasticsearch

This is a fluentd daemon for monitoring kubernetes log and sending the
log to AWS ElasticSearch. This is adapted from the kubernetes
[fluentd-es-image](https://github.com/kubernetes/kubernetes/tree/master/cluster/addons/fluentd-elasticsearch/fluentd-es-image).

You must configure the following environment variables:

* `AWS_ELASTICSEARCH_URL` (with `https://` appended by the ElasticSearch endpoint)
* `AWS_REGION`
* `AWS_ACCESS_KEY_ID`
* `AWS_SECRET_ACCESS_KEY`
