# Lab: Basic IPv4 Subnetting & Router Configuration

## Objective
To successfully segment a /24 network into four distinct subnets to optimize broadcast domains.

## What I Learned
* How to calculate the magic number to find subnet boundaries quickly.
* Assigning the first usable IP address to the router's GigabitEthernet interface.

## Useful Commands Used
`router(config)# interface g0/0`
`router(config-if)# ip address 192.168.1.1 255.255.255.192`
`router(config-if)# no shutdown`
