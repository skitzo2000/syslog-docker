# syslog-docker
Syslog Telegraf InfluxDB Grafana Docker compose

Docker compose structure to start a syslog container for remote syslog's including a Grafana dashboard for visulazation.

The initial concept dervied from here: https://nwmichl.net/2020/03/15/telegraf-influxdb-grafana-as-syslog-receiver/

Converted to a docker compose file instead of installed arrangment on blog post.

Grafana dashboard source: https://github.com/NWMichl/grafana/blob/master/Syslog-Dashboard.json

Note you will need to setup an .env file with references for:

SYSLOG_DB_NAME
SYSLOG_USER
SYSLOG_PASSWORD
GF_SECURITY_ADMIN_PASSWORD
GF_AUTH_ANONYMOUS_ENABLED=false
