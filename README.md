# 🌐 NetPath Illuminator — The Network Odyssey
### Cisco AICTE Virtual Internship Program (VIP) 2025 — Networking Track

> 🚀 *Selected participant, Cisco VIP 2025 — Industry Networking Project Challenge*

A level-based simulation project covering the progressive networking stack — from basic PC-to-PC connectivity through static/dynamic routing, VLAN segmentation, and ACL/NAT security policy — built and verified in **Cisco Packet Tracer**.

📄 [Full Project Report (PDF)](CISCO%20VIP%20-Final%20Report.pdf)

---

## 📁 Repository Structure

```
Cisco_vip_2025-Projects/
├── level1.pkt              # PC-to-PC connectivity
├── level2.pkt              # Static routing
├── level3.pkt              # Dynamic routing (RIP v2)
├── level4.pkt              # Dynamic routing (OSPF)
├── level5.pkt              # VLAN configuration
├── level6.pkt              # Inter-VLAN routing
├── level7.pkt              # ACL & NAT
├── level8.pkt              # End-to-end traceroute validation
├── screenshots/            # Topology + verification screenshots per level
├── configs/                # Exported "show run" CLI configs per level (.txt)
├── CISCO VIP -Final Report.pdf
└── README.md
```

> **Note:** `.pkt` files require [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) to open. The `screenshots/` and `configs/` folders let you review the work without installing it.

---

## 🧠 Levels

### Level 1 — PC-to-PC Communication
- **Goal:** Establish direct ping connectivity between two end devices.
- **Skills:** IP addressing, subnetting, basic topology design.
- **Devices:** 2 PCs, 1 Switch.

### Level 2 — Static Routing
- **Goal:** Manually configure routes across a 3-router topology.
- **Skills:** Routing tables, subnet planning, `ip route`.
- **Devices:** 3 Routers, 3 Switches, 6 PCs.

### Level 3 — Dynamic Routing (RIP v2)
- **Goal:** Automate route discovery.
- **Commands:** `router rip`, `network`, `version 2`.

### Level 4 — Dynamic Routing (OSPF)
- **Goal:** Implement OSPF across a multi-router topology with area design.
- **Commands:** `router ospf 1`, `network ... area 0`.
- **Verification:** Simulated link failure to confirm route reconvergence to a backup path.

### Level 5 — VLAN Configuration
- **Goal:** Segment a LAN into isolated broadcast domains.
- **Skills:** VLAN creation, access port assignment, trunking between switches.

### Level 6 — Inter-VLAN Routing
- **Goal:** Enable controlled communication between VLANs.
- **Skills:** Router-on-a-stick, sub-interface configuration.

### Level 7 — ACL & NAT
- **Goal:** Enforce traffic policy and map private-to-public addressing.
- **Skills:** Standard/extended ACLs, NAT inside/outside.

### Level 8 — End-to-End Verification
- **Goal:** Validate full-path connectivity and routing across all prior levels.
- **Skills:** `tracert`, ICMP path debugging, systematic fault isolation.

---

## 🛠 Tools & Technologies

- **Simulation:** Cisco Packet Tracer
- **Protocols:** RIP v2, OSPF, VLAN trunking, ACL, NAT, ARP, ICMP
- **Documentation:** MS Word/PDF, Markdown
- **Version Control:** Git & GitHub

---

## 🧠 Key Takeaways

- Practical grounding in OSI/TCP-IP layered troubleshooting
- Hands-on static and dynamic routing protocol configuration and convergence behavior
- LAN segmentation and inter-VLAN routing design
- Security policy enforcement via ACL/NAT
- Structured technical documentation of network builds and fixes

## 🌱 Future Scope

- Migrate simulated topology to physical/virtual router lab (EVE-NG or GNS3)
- Capture and analyze live traffic with Wireshark per level
- Add a Python-based dashboard for route/link status monitoring

---

## 📄 License

MIT License — see [LICENSE](LICENSE)

## 🙋‍♀️ About Me

**Kaviya Murugan** — B.E. (Hons.) Electronics & Communication Engineering | Cisco VIP 2025 Selected Participant

🔗 [LinkedIn](https://www.linkedin.com/in/kaviya-murugan/) · [GitHub](https://github.com/Kaviya-3016) 

---

⭐ If this was useful as a reference, consider starring the repo.
