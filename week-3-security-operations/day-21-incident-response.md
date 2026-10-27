<div align="center">

# Day 21 — Incident Response

**Week 3 · Security Operations & Threat Detection**

`~30 min` · `Learn + Write`

</div>

---

## 🎯 Focus

Learn the Incident Response lifecycle and write a mini runbook.

---

## 📚 Learned

I learned the **Incident Response (IR) lifecycle**. This is the standard process organizations follow when an attack is detected.

The 6 phases of the IR lifecycle:
1. **Preparation** — Get ready before anything happens. Policies, tools, training.
2. **Identification** — Detect the incident. Confirm it is real.
3. **Containment** — Stop the spread. Isolate affected systems.
4. **Eradication** — Remove the threat. Delete malware, close the hole.
5. **Recovery** — Bring systems back online safely.
6. **Lessons Learned** — What worked? What failed? Update the plan.

🔗 [Cisco Talos Incident Response Services](https://talosintelligence.com/incident-response)

---

## ✅ What I Did

### Wrote a 1-page mini runbook for a malware infection

Here is my runbook for handling a suspected malware infection on a company laptop:

**1. Preparation**
- Keep an offline copy of emergency contacts.
- Have EDR tools installed and updated on all devices.

**2. Identification**
- Receive alert or user report of strange behavior (slow computer, pop-ups, files renamed).
- Verify the infection: check EDR dashboard, look for known malware processes.

**3. Containment**
- Disconnect the laptop from the network immediately (unplug Ethernet, turn off Wi-Fi).
- Do not shut down the device. Leave it on for forensics.
- Block the malware's known command-and-control (C2) IPs at the firewall.

**4. Eradication**
- Use EDR to quarantine the malware.
- Scan the entire device.
- Identify how it got in (phishing email, bad download).
- Remove the source (delete the email, block the site).

**5. Recovery**
- Restore the device from a clean backup if needed.
- Reconnect to the network and monitor for 24 hours.
- Verify the user can work normally.

**6. Lessons Learned**
- Write a short report: what happened, what we did, what could be better.
- Update email filters or blocklists if needed.
- Brief the team on the new threat.

---

## 💡 Key Takeaways

- **Preparation** is the most important phase. You cannot respond well if you are not ready.
- **Containment** comes before eradication. Stop the bleeding first.
- **Do not turn off the device.** You lose volatile memory.
- **Document everything.** Timestamps matter.
- **Lessons learned** turns a bad event into a better future.

---

## ❓ Questions

- What is the difference between an incident and an event?
- How do you handle an incident that involves multiple departments?

---

## ⏱️ Time Spent

30 minutes

---

## ✅ Completed

- [x] Learned the IR lifecycle
- [x] Wrote a 1-page mini runbook for malware infection

---

<div align="center">

[← Previous: Day 20](day-20-inside-the-soc.md) · [Back to Week 3](README.md) · [Next: Day 22 →](../week-4-offense-cloud-certification/day-22-think-like-an-attacker.md)

</div>