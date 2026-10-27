<div align="center">

# Day 16 — Security Monitoring

**Week 3 · Security Operations & Threat Detection**

`~30 min` · `Learn + Identify`

</div>

---

## 🎯 Focus

Learn what logs and telemetry matter for security monitoring.

---

## 📚 Learned

I learned that **security monitoring** is about watching the right data at the right time. You cannot monitor everything, so you have to pick the most valuable sources.

What I learned:
- **Logs** are records of events that happen on a system or network.
- **Telemetry** is data sent automatically from devices to a monitoring system.
- The goal is to catch threats early, before they do damage.
- Good monitoring means fewer false alarms and faster real detections.

🔗 [Get Started with OCSF: Standardize Security Data Across Tools](https://www.splunk.com)

---

## ✅ What I Did

### Identified the first five log sources I would monitor

If I were starting a security monitoring program from scratch, these are the first five places I would look:

1. **Firewall logs** — See what traffic is allowed, blocked, or leaving the network.
2. **Authentication logs** — See who is logging in, from where, and if it failed.
3. **Endpoint logs (EDR)** — See processes running on laptops and servers.
4. **DNS logs** — See what domains devices are trying to reach (great for catching malware).
5. **Cloud service logs (e.g., Microsoft 365, AWS)** — See who is accessing cloud resources and from where.

### Why these five first
- They cover the most common attack paths.
- They generate the data most incidents are built from.
- They are available in almost every environment.

---

## 💡 Key Takeaways

- You cannot monitor what you do not collect.
- Logs are only useful if they are searchable and reviewed.
- Authentication logs are often the first sign of an attack.
- DNS is a goldmine for detecting malware because malware has to call home.
- Start small with the most valuable sources, then expand.

---

## ❓ Questions

- How long should logs be kept for investigation?
- What is the difference between SIEM and SOAR?

---

## ⏱️ Time Spent

30 minutes

---

## ✅ Completed

- [x] Learned what logs and telemetry matter
- [x] Listed five log sources I would monitor first

---

<div align="center">

[← Previous: Day 15](day-15-why-splunk.md) · [Back to Week 3](README.md) · [Next: Day 17 →](day-17-intro-to-siem.md)

</div>