# evolocity_v2
sucessor to https://github.com/BitOMOn/evolocity

DATA PIPELINE:
1. DATA COLLECTION (FROM VESC AND SENSORS)
2. MAKEW JSON PACKET AND SEND VIA BLUETOOTH FROM MICROCONTROLLER TO APP
3. DATA DECODE FOR IN APP DASH
4. DATA TRANSMISSION VIA MQTT TO NODE RED FOR GRAPHING AND INFLUXDB INPUT
5. INFLUXDB TO GRAFANA FOR VIEWING
