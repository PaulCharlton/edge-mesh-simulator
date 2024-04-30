# edge-mesh-simulator
simulation of mesh network communications for BLE, 5G, etc.

### basic requirements

1) fixed position node instances using a 6-vector x,y,z and facing direction x', y', z'
2) node capabilities -- radio type [BLE, 5G, others]
3) node power source
4) node attentuation relative to default

5) manage a fleet of nodes
6) manage communications between nodes [A, B] and [B, A]
7) log communication data by transmitter, receiver [power output, angle of departure, angle of arrival, RSSI]
8) fleet will have at least 2 gateway nodes which are not transient part of fleet

9) manage a fleet of moving nodes [which are observed by the fixed position nodes]
10) moving position node instances using a 6-vector x,y,z and facing direction x', y', z' which varies over time
11) node capabilities -- radio type [BLE, 5G, others]
12) node power source
13) node attenuation relative to default

14) chaos
15) each message between nodes can be altered by noise and attentuation
16) extra nodes may be injected and try to particpate in the networking protocols -- should get rejected

17) each fixed node instance needs to recognize packets for:
18) provisioning at "factory"
19) re-provisioning via OTA update
20) using zero trust

21) nodes need to be able to save state to "get smarter" over time by 1:1 routing instead of broadcast
22) nodes to to specify "angle of departure" when hardware is available
23) broadcast with TTL in hops or seconds
24) nodes need to provide 6 or more "sensors" and 6 or more "control settings"


25) over time, network traffic varies
26) provisioning
27) mesh discovery
29) telemetry from sensors
30) node status
31) control data to "control settings"
32) responses to "moving nodes"
33) re-provisioning (OTA)



