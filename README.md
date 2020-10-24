# raspi_server_docker
The docker compose file for running a home Raspberry Pi 4 server

Will Launch:
Portainer for managing docker containers
MQTT Broker for handling messages from house nodes (e.g. getting temperature readings, or sending instructions to turn on lights)
Node-Red for home automation workflows
Telegraf for gathering data from the Pi itself (e.g. CPU temp)
InfluxDB for holding data from node-red and telegraf
Grafana for displaying data
MotionEye for running CCTV system
Plex for serving media
Tatauli for monitoring Plex use and logs
VPN for connecting with a VPN provider
