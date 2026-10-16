<div align="center">

# Day 09 — Defense in Depth

**Week 2 · Network & Endpoint Defense**

`~30 min` · `Map + Think`

</div>

---

## 🎯 Focus

Map the layers of defense for one asset.

---

## 📚 Learned

**Defense in depth** means using multiple layers of security so that if one fails, another catches the attack.

No single control is perfect. Layers buy time and give you chances to detect and respond.

🔗 [Network Defense | Module 1](https://u.cisco.com)

---

## ✅ What I Did

### Picked one asset: Company email account

### Mapped the layers of defense

| Layer | Control | What it protects against |
|-------|---------|--------------------------|
| **Data** | Email encryption, DLP | Leaked sensitive content |
| **Application** | Spam filter, attachment scanning | Malicious attachments, phishing |
| **Host** | Endpoint antivirus, EDR | Malware on the device |
| **Network** | Firewall, DNS filtering | Bad traffic, command-and-control |
| **Perimeter** | MFA, conditional access | Stolen credentials |

### What this looks like as a chain

Attacker → Perimeter (MFA) → Network (Firewall) → Host (EDR)
→ Application (Spam filter) → Data (Encryption)


If any layer blocks, the attack stops.

---

## 💡 Key Takeaways

- One control is never enough.
- Layers should cover different attack stages.
- Perimeter alone is not enough. Attackers get past it.
- Data is the last layer. Protect it even if everything else fails.

---

## ❓ Questions

- How do you decide how many layers are enough?
- What is the difference between defense in depth and zero trust?

---

## ⏱️ Time Spent

30 minutes

---

## ✅ Completed

- [x] Learned defense in depth
- [x] Mapped layers for one asset

---

<div align="center">

[← Previous: Day 8](day-08-network-security-101.md) · [Back to Week 2](README.md) · [Next: Day 10 →](day-10-endpoint-security.md)

</div>
