<div align="center">

# Day 11 — Harden a Network

**Week 2 · Network & Endpoint Defense**

`~30 min` · `Learn + Monitor`

</div>

---

## 🎯 Focus

Learn how to monitor and protect a network and evaluate security alerts.

---

## 📚 Learned

I learned how to harden a network by:

- Reducing the attack surface (turn off unused services and ports)
- Enforcing strong access rules
- Monitoring logs and alerts for unusual activity
- Evaluating alerts — not every alert is an attack, but every alert deserves a look

🔗 [Network Defense | Module 2](https://u.cisco.com)

---

## ✅ What I Did

### Evaluated security alerts

I looked at a list of sample security alerts and sorted them by what they actually meant:

1. **Failed logins (many in a row)** — Possible brute force. Needs attention.
2. **New device on the network** — Could be fine (new phone) or could be an intruder. Verify.
3. **Traffic to a known bad IP** — High priority. Investigate immediately.
4. **Outdated software alert** — Low urgency, but should be patched.

### Hardening steps I noted
- Disable unused ports on switches
- Change default passwords on all network devices
- Update firmware regularly
- Enable logging and review alerts weekly

---

## 💡 Key Takeaways

- Hardening is about reducing what an attacker can use.
- Logging is useless if nobody looks at it.
- Alerts need context — a single failed login is normal, fifty is not.
- Small changes (passwords, updates, unused ports) have big impact.

---

## ❓ Questions

- What is the difference between an IDS and an IPS?
- How do I prioritize alerts when there are too many?

---

## ⏱️ Time Spent

30 minutes

---

## ✅ Completed

- [x] Learned how to monitor and protect a network
- [x] Evaluated security alerts and sorted by priority

---

<div align="center">

[← Previous: Day 10](day-10-endpoint-security.md) · [Back to Week 2](README.md) · [Next: Day 12 →](day-12-access-control.md)

</div>