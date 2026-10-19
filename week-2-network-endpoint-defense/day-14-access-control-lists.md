<div align="center">

# Day 14 — Access Control Lists (ACLs)

**Week 2 · Network & Endpoint Defense**

`~45 min` · `Build + Test`

</div>

---

## 🎯 Focus

Extend your lab topology with a firewall and ACLs.

---

## 📚 Learned

I learned how **Access Control Lists (ACLs)** work and how to apply them in a network.

What I learned:
- An ACL is a set of rules that allow or block traffic.
- ACLs process rules **top to bottom**. The first match wins.
- There is an **implicit deny** at the end. If no rule matches, traffic is blocked.
- Standard ACLs filter by source IP only.
- Extended ACLs filter by source, destination, protocol, and port.

🔗 [CCNA: Configure Your First ACL](https://u.cisco.com)

---

## ✅ What I Did

### Extended my Cisco Modeling Labs topology

I added a firewall and ACLs between the network segments.

**Setup:**

Host A ──┐
├── Switch ── Router (ACL) ── Server
Host B ──┘


**The goal:** Allow Host A to reach the Server, but block Host B.

### The ACL logic I used (conceptually)

```text
Rule 1: Allow traffic from Host A to Server (port 80, 443)
Rule 2: Block traffic from Host B to Server
Rule 3: Allow all other traffic
Rule 4: Deny everything else (implicit)