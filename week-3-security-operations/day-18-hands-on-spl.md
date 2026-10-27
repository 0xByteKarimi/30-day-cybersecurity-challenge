<div align="center">

# Day 18 — Hands-on SPL

**Week 3 · Security Operations & Threat Detection**

`~60 min` · `Practice + Search`

</div>

---

## 🎯 Focus

Load the Splunk BOTS dataset and run real searches.

---

## 📚 Learned

I practiced using **SPL** (Splunk Processing Language) by loading the free **Boss of the SOC (BOTS)** dataset.

SPL is the language used to search and analyze data in Splunk. It looks a bit like SQL, but it is designed for log data.

🔗 [Boss of the SOC (BOTS) Dataset Version 3](https://github.com/splunk/botsv3)

---

## ✅ What I Did

I loaded the BOTS dataset and ran **three searches**:

### 1. Failed logins
I searched for failed login events to see if there was a brute force attempt.

**What I found:** Several failed logins from the same IP address in a short time.

### 2. Top source IPs
I searched for the IP addresses generating the most traffic or events.

**What I found:** One IP address stood out with far more activity than the rest.

### 3. Suspicious processes
I searched for process names that are commonly used by attackers (like `powershell`, `cmd`, `wmic`).

**What I found:** A few unusual process executions that do not match normal user behavior.

---

## 💡 Key Takeaways

- SPL is powerful because it lets you ask specific questions of your data.
- The BOTS dataset is a safe way to practice real investigations.
- Failed logins are often the first clue of an attack.
- Top talkers (most active IPs) are a good starting point for investigations.
- Looking for suspicious processes helps catch malware and lateral movement.

---

## ❓ Questions

- What is the difference between `stats` and `timechart` in SPL?
- How do I write a search that ignores known false positives?

---

## ⏱️ Time Spent

60 minutes

---

## ✅ Completed

- [x] Loaded the BOTS dataset
- [x] Ran three searches (failed logins, top IPs, suspicious processes)

---

<div align="center">

[← Previous: Day 17](day-17-intro-to-siem.md) · [Back to Week 3](README.md) · [Next: Day 19 →](day-19-automate-response.md)

</div>