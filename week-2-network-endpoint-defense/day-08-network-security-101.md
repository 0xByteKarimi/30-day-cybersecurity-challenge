<div align="center">

# Day 08 — Network Security 101

**Week 2 · Network & Endpoint Defense**

`~45 min` · `Learn + Build`

</div>

---

## 🎯 Focus

Learn how networks are defended and build a small lab topology.

---

## 📚 Learned

I learned the basics of network defense:

- **Segmentation** — split the network into smaller parts so an attacker cannot move freely
- **Firewalls** — filter traffic between networks
- **Switches vs. routers** — switches connect devices in a LAN, routers connect networks
- **Trust zones** — not all networks should talk to each other

🔗 [Endpoint Security | Module 6](https://u.cisco.com)

---

## ✅ What I Did

### Built a small topology in Cisco Modeling Labs

Components:
- 1 router
- 1 switch
- 2 hosts

What I practiced:
1. Connected the hosts to the switch
2. Connected the switch to the router
3. Set basic IP addresses
4. Configured basic segmentation so the two hosts could talk to the router but stay separated at layer 2

### What segmentation looks like

Host A ──┐
├── Switch ── Router ── Outside
Host B ──┘


Each host only sees what it needs to see. Nothing extra.

---

## 💡 Key Takeaways

- Segmentation limits how far an attacker can move.
- Firewalls are policy, not magic. Someone has to write the rules.
- Even a simple two-host lab teaches the basics of traffic flow.
- Cisco Modeling Labs is free for NetAcad students.

---

## ❓ Questions

- What is the difference between a VLAN and a subnet?
- How does a firewall decide what to allow?

---

## ⏱️ Time Spent

45 minutes

---

## ✅ Completed

- [x] Learned how networks are defended
- [x] Built a small topology in Cisco Modeling Labs

---

<div align="center">

[← Previous: Day 7](../week-1-security-foundations/day-07-reflect-plan.md) · [Back to Week 2](README.md) · [Next: Day 9 →](day-09-defense-in-depth.md)

</div>