+++
date = '2024-12-18T13:24:20+07:00'
draft = false
title = 'aws cpe one day'
type = 'xpage'
categories = ['pages']
tags = ['aws']
authors = ['viridi']
+++
<!--more-->

- Firewall has rules from top to down.
- Firewall is in on-premise.
- In AWS, A network ACL is a virtual firewall for a subnet.
- Network ACL by default allows all inbound and outbound traffic.
- ACL is stateless, checked in and out.
- Security group is a virtual firewall for an Amazon EC2, by default denied all inbound and allows all outbound traffic.

+ DNS (domain name system).
+ IP information for domain name is stored in DNS server.
+ AWS DNS is Route 53 (visiting a houes using IP via services HTTP, DNS, dll, named it DNS port is 53 like http, ftp, etc)
+ DNS resolution (domain to IP)
+ Global infrastructure, user can choose which server is free.
+ AWS 34 regions.

- DC (data center) pada satu region punya multi AZ (availability zone)
- Jakarta 3 AZ (min 2 per region).
