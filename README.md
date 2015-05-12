# node-red-contrib-mqtt-env
This is an node module for node-red that allows to use environment variables for MQTT broker uris in MQTT nodes.

#### Run locally
(npm install node-red -g)
npm install node-red-contrib-mqtt-env -g
export MQTT_AWESOME_BROKER_URI=<your_awesome_broker_uri>

start node-red

Your should see in the console something like
[mqtt] Resolving ENV: MQTT_AWESOME_BROKER_URI into your_awesome_broker_uri
