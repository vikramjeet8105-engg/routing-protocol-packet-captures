# OSPF, BGP, MPLS and multicast: protocol captures

Wireshark captures taken while building each routing lab, one file per behaviour.

| Folder | Captures |
|---|---|
| `ospf/` | Neighbour adjacency forming (hello, DBD, LSR, LSU, LSAck) and the different LSA types |
| `bgp/` | iBGP and eBGP peering, eBGP multihop with TTL change, route reflector cluster-list and originator-id, confederation AS_CONFED_SEQUENCE, soft versus hard reset |
| `mpls/` | LDP adjacency, labelled ping, explicit-null, `no mpls ip propagate-ttl`, MPLS traceroute |
| `multicast/` | IGMPv2 report, query and leave, PIMv2 hello, PIM dense-mode prune, PIM sparse-mode join and register/register-stop |

---
Lab work from my Master of Engineering in Internetworking, Dalhousie University (2024 to 2026). Course handouts and graded answer sheets are not included.

Author: Vikramjeet Singh, [LinkedIn](https://www.linkedin.com/in/vikramjeet-singh-75b7a2183)
