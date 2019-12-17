# kibana-dashboards

some kibana dasboards for remote download

## import via:

```
curl -v -s --connect-timeout 60 --max-time 60 -XPOST localhost:5601/api/kibana/dashboards/import?force=true -H 'kbn-xsrf:true' -H 'Content-type:application/json' -d @./k8s-fluentd-elasticsearch.json
```
