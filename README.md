# VPN Deployment & ACL Lab

## Overview
This lab simulates the deployment of secure VPN tunnels between two branch offices using virtualized routers. It demonstrates VPN configuration, IPsec tunnel establishment, and ACL (Access Control List) filtering to control traffic between the sites.

## Objectives
- Deploy IPsec VPN tunnels between simulated branch sites.
- Apply ACLs to filter and secure VPN traffic.
- Verify tunnel establishment and ACL enforcement.
- Perform packet captures to validate secure traffic flows.

## Tools & Technologies
- Cisco Packet Tracer / GNS3
- IPsec VPN Configuration
- Extended ACLs (Access Control Lists)

## Key Tasks
- Configure IP addressing and routing on both branches.
- Create ISAKMP policy and IPsec transform sets.
- Define crypto maps and apply them to outside interfaces.
- Configure ACLs to permit only authorized subnets across the VPN.
- Verify the VPN establishment using `show crypto isakmp sa` and packet captures.

## Screenshots
_Add relevant screenshots of tunnel status and ACL verification here._

## Outcome
Established a secure VPN between two branches with strict ACL traffic filtering, ensuring only intended traffic traverses the encrypted tunnel.

---

**Author:** Serena Lindquist
