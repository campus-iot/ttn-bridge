# Simple TTN Bridge
Simple One-Way Bridge between Chirpstack and TTN

## Code
The bridge is a NodeRED flow in [configuration/nodered/flow.json](configuration/nodered/flow.json).

## Launch the NodeRED server
```bash
docker-compose -f nodered.yml up -d
docker-compose -f nodered.yml logs -f
```

## Register the gateways
You should register the gateways as "legacy packet forwarder" into your [TTN console](https://console.thethingsnetwork.org/gateways/register) in order to enable the traffic.

![Gateway registration](./gw-registration.png)
