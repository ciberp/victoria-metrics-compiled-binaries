# victoria-metrics-compiled-binaries for raspberry pi 4 debian buster

source: https://github.com/VictoriaMetrics/VictoriaMetrics

## compile

git pull https://github.com/VictoriaMetrics/VictoriaMetrics
make victoria-metrics-arm
make vmagent-arm
make vmbackup-arm
make vmrestore-arm
make vmalert-arm

