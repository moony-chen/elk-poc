# Buddhist Machine Log system
**/*log                 test log files
filebeat.*.yml          file beats config
buddhist-pipeline.conf  logstash pipeline


## Start elastic search
`
bin/elasticsearch
`

## Start Kibana
`
bin/kibana
`

## Start LogStash
`
bin/logstash -f ./buddhist-pipeline.conf
`

## Start file beat on buddhist machine server
`
filebeat -e -c ./filebeat.dev.yml
`



