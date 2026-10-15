---
in-progress: "true"
---
# Related
[[Dijkstra's]]

# Distributed Alternative
The main disadvantages of the Bellman–Ford algorithm in this setting are as follows:
- It does not scale well.
- Changes in [network topology](https://en.wikipedia.org/wiki/Network_topology "Network topology") are not reflected quickly since updates are spread node-by-node.
- [Count to infinity](https://en.wikipedia.org/wiki/Distance-vector_routing_protocol#Count_to_infinity_problem "Distance-vector routing protocol") if link or node failures render a node unreachable from some set of other nodes, those nodes may spend forever gradually increasing their estimates of the distance to it, and in the meantime there may be routing loops.

# Used In
Used by this algorithm [[Energy-Efficient Decentralized Cooperative Routing in Wireless Networks.pdf#page=2&selection=24,38,24,60|Energy-Efficient Decentralized Cooperative Routing in Wireless Networks, page 2]] [[Energy-Efficient Decentralized Cooperative Routing in Wireless Networks|link]]