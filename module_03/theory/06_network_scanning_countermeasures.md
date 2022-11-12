# Section 06: Network Scanning Countermeasures

## Ping Sweeping Countermeasures

- Dont allow connections to send more than a small number of ICMP ECHO requests.
- Use IDS and IPS to detect ping sweeps
- Limit ICMP traffic with access control lists (ACLs)

## Port Sweeping Countermeasures

- Use IDS and IPS to detect ping sweeps
- Ensure all routers, firewalls, etc are running the latests version of their software.
- Block unwanted ports.

## Banner Grabbing countermeasures

- Display false banners to mislead attackers.
- Turn of unnecessary services on hosts to limit information disclosure.
- Disable details of vendors and version in banners.

## IP Spoofing Countermeasures

- Avoid authentication based on IP address
- Use firewalls and ACLs
- Use encyrption. IPSec can greatly reduce the risk of IP spoofing.

Links
- [https://en.wikipedia.org/wiki/IPsec](https://en.wikipedia.org/wiki/IPsec)

## Scanning Detection Tools
Splunk
> Splunk is the data platform that powers enterprise observability, unified security and limitless custom applications in hybrid environments.

Links
- [https://www.splunk.com](https://www.splunk.com)
