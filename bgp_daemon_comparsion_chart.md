| Requirement  | Bird          | Quagga | OpenBGPd | GoBGP |
| ------------- |:-------------:|:------:|:--------:|:-----:|
| Scalability to 1500 peers | ? | No  | No | ? |
| Per Peer RIBs | Yes | Yes  | Yes | Yes |
| Fast BGP convergence times | Yes | ?  | Yes | ? |
| Scalability of filters | Yes | No | Yes | ? |
| Fast reload of filters | Yes | No | Yes | ? |
| Decent memory requirements | Yes | Yes | ? | ? |
| Multi-Core support | No | No | No | Yes |
| Ipv4/IPv6 support | Yes | Yes | Yes | Yes |
| (Extended) BGP communities | Yes | Yes | Yes | Yes |
| Multi protocol support | Yes | Yes | Yes | No |
| Configuration | Yes | Yes | Yes | Yes |
| GTSM | Yes | Yes | Yes | No |

| Requirement  | Bird          | Quagga | OpenBGPd | GoBGP |
| ------------- |:-------------:|:------:|:--------:|:-----:|
| Route Flap Dampening | ? | No | No | No |
| BFD | Broken | No | No | No |
| RPKI Validation | Yes | No | No | Yes |
| BGPSec Validation | No | No | No | No |
| Multi Path | Yes | Yes | No | No |

| Requirement  | Bird          | Quagga | OpenBGPd | GoBGP |
| ------------- |:-------------:|:------:|:--------:|:-----:|
| TCP MD5 passwords | Yes | Yes | Yes | Yes |
| Graceful restart | Yes | No | Yes | No |
| FlowSpec | No | No | No | Yes |
| NetConf | No | No | No | No |
| NetConf over SSH | No | No | No | No |
| MRT dumps | Yes | Yes | Yes | Yes |
| Route refresh | Yes | Yes | Yes | Yes |
| SNMP | No | Yes | No | No |
| BMP | No | No | No | Yes |
