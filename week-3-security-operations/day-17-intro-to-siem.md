<div align="center">

# Day 17 — Intro to SIEM

**Week 3 · Security Operations & Threat Detection**

`~45 min` · `Course + Learn`

</div>

---

## 🎯 Focus

Take Intro to Splunk Security Essentials and understand how detections work.

---

## 📚 Learned

I took the **Intro to Splunk Security Essentials** course and learned how a SIEM (Security Information and Event Management) works.

What I learned:
- A **SIEM** collects logs from many sources and puts them in one place.
- It uses rules and searches to detect suspicious activity.
- **Detections** are the rules that look for known bad patterns.
- **Analytic stories** group related detections together to tell the full story of an attack.

🔗 [Intro to Splunk Security Essentials](https://www.splunk.com)

---

## ✅ What I Did

I explored how detections and analytic stories work in practice.

### What a detection looks like (conceptually)
A detection might say: "If a user fails to log in 5 times in 2 minutes, alert."

### What an analytic story looks like
An analytic story might group:
1. Failed logins
2. Successful login from a new country
3. New admin account created
4. Data downloaded

Each one alone might be noise. Together they tell a story: **a possible account takeover**.

### Why this matters
Security analysts do not look at single events. They look at **patterns**. SIEM tools help find those patterns at scale.

---

## 💡 Key Takeaways

- A SIEM is only as good as the detections you build for it.
- Analytic stories help connect the dots between separate alerts.
- Context is everything. A single event means nothing without surrounding events.
- SIEM tools are not magic. They are search engines with security logic built in.

---

## ❓ Questions

- How do you reduce false positives in a SIEM?
- What is the difference between a detection rule and a correlation search?

---

## ⏱️ Time Spent

45 minutes

---

## ✅ Completed

- [x] Took Intro to Splunk Security Essentials
- [x] Understood how detections and analytic stories work

---

<div align="center">

[← Previous: Day 16](day-16-security-monitoring.md) · [Back to Week 3](README.md) · [Next: Day 18 →](day-18-hands-on-spl.md)

</div>