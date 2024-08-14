# Deepspace Proposed Charter

Deep space communications involve long delays (e.g., Earth to Mars is 4-20 minutes) and intermittent communications, because of orbital dynamics. The combination of long delays and intermittent communications makes the round-trip time very large and very variable. Up to now, communications have been done on a layer-2 point to point basis, with sometimes the use of relays, therefore no layer-3 networking was possible. Space agencies and private sector are planning to deploy IP networks on celestial bodies, such as Moon or Mars, ground, orbits and vicinity. If the deep space links are also IP, then it makes a complete end to end IP network. However, given the delays and disruptions, the upper layers such as transport and application protocols have to be profiled to support this environment.

This working group will work on an overall architecture of using the IP stack in deep space, including documenting the key characteristics that make this environment unique. A profile for the QUIC transport will also be defined to make use of QUIC end to end in deep space. Given the often disconnected nature of networks on celestial bodies, considerations on the deployment of DNS will be documented. Finally, considerations on how to properly design applications in this environment will be provided.

## Milestones
* Deep space IP Architecture, Informational
* QUIC profile for deep space, Informational
* DNS in mostly isolated networks, Informational
* Application Considerations for deep space, Informational