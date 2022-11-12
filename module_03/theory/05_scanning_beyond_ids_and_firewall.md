# Section 05: Scanning Beyond IDS and Firewall

## Evasion Techniques (Routing)
IDS (Intrusion Detection System)
> An intrusion detection system (IDS; also intrusion prevention system or IPS) is a device or software application that monitors a network or systems for malicious activity or policy violations.

Techniques to evade IDS/firewalls are
- Proxy servers
- IP address spoofing
- Mac address spoofing
- Packet fragmentation

Packet fragmentation
> IP fragmentation is an Internet Protocol (IP) process that breaks packets into smaller pieces (fragments), so that the resulting pieces can pass through a link with a smaller maximum transmission unit (MTU) than the original packet size.
> The fragments are reassembled by the receiving host.

Source routing
> In computer networking, source routing, also called path addressing, allows a sender of a packet to partially or completely specify the route the packet takes through the network.

Links
- [https://en.wikipedia.org/wiki/Intrusion_detection_system](https://en.wikipedia.org/wiki/Intrusion_detection_system)
- [https://en.wikipedia.org/wiki/IP_fragmentation](https://en.wikipedia.org/wiki/IP_fragmentation)
- [https://en.wikipedia.org/wiki/Source_routing](https://en.wikipedia.org/wiki/Source_routing)

## Evasion Techniques (Spoofing)
IP Address spoofing
> In computer networking, IP address spoofing or IP spoofing is the creation of Internet Protocol (IP) packets with a false source IP address, for the purpose of impersonating another computing system.

MAC spoofing
> MAC spoofing is a technique for changing a factory-assigned Media Access Control (MAC) address of a network interface on a networked device.
> The MAC address that is hard-coded on a network interface controller (NIC) cannot be changed.
> However, many drivers allow the MAC address to be changed.

Links
- [https://en.wikipedia.org/wiki/IP_address_spoofing](https://en.wikipedia.org/wiki/IP_address_spoofing)
- [https://en.wikipedia.org/wiki/MAC_spoofing](https://en.wikipedia.org/wiki/MAC_spoofing)

## Evasion Techniques (Other)
Randomizing host order. The `nmap` option `--randomize-hosts` man pages is
```shell
--randomize-hosts (Randomize target host order)
   Tells Nmap to shuffle each group of up to 16384 hosts before it scans them. This can make the scans less obvious to various network monitoring systems, especially when
   you combine it with slow timing options. If you want to randomize over larger group sizes, increase PING_GROUP_SZ in nmap.h and recompile. An alternative solution is to
   generate the target IP list with a list scan (-sL -n -oN filename), randomize it with a Perl script, then provide the whole list to Nmap with -iL.
```

Proxy server
> n computer networking, a proxy server is a server application that acts as an intermediary between a client requesting a resource and the server providing that resource.

Proxy chaining
> Proxy chaining involves forwarding traffic from one proxy server to another.
 
Links
- [https://en.wikipedia.org/wiki/Proxy_server](https://en.wikipedia.org/wiki/Proxy_server)
