# AccessAnalyzr
Client and Server to test Internet Access properties.

## What are the properties of Internet Access?
Apart from "bandwidth" an Internet access lacks a product declaration. The purpose of the AccessAnalyzr is to probe a given network access and score it based on how well it supports "true" Internet Access.

Is IPv4 and IPv6 provided? Is IPv4 behind a NAT, and what are the properties of that NAT?
Is the access transparent, or are some ports blocked or throttled? Does it pass IPv6 extension headers, does PMTUD work correctly?

## Planned probes ##

* IPv4 addresses. How many? Lifetimes?
* IPv4 NAT properties. Endpoint independence, address/port filtering
* IPv6 addresses.
* UDP/TCP Port throttling or blocking
* Access link MTU and Path MTU discovery
* IPv4 fragmentation
* IPv6 fragmentation
* Transparent passing of IPv6 extension headers
* MANRS
* DNS posioning
* BCP38 (IPv4, IPv6)
* Bandwith, Latency, Queueing (Bufferbloat)
* ECN
* Use of IPv4 as a service or IPv6 as a service mechanisms
