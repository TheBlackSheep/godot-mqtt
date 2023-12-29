
# Changes
Nothing major - Just modded the test application to add the username/pasword parameters and changed the ssl drop-down option to use port 8883 instead of 8886.  Also changed the parameters of the "connect_to_broker" function to also accept the username/password and set them if they aren't empty (required for HiveMQ).

## Local Server test
Tested locally against a Ubuntu Mosquitto installation (no username/password and not exposed to the Internet) on port 1883 (and still works after these mods).

## HiveMQ Cloud (AWS MQTT)
Successfully tested against the free tier which is limited to 100 clients in both directions with publishing and subscribing using the mosquitto_clients (mosquitto_pub/mosquitto_sub cmd-line utilities) on Ubuntu 23.10.







