<div align="center">

# Day 19 — Automate Response

**Week 3 · Security Operations & Threat Detection**

`~45 min` · `Course + Sketch`

</div>

---

## 🎯 Focus

Learn about SOAR and sketch a simple playbook for a phishing alert.

---

## 📚 Learned

I took the **Intro to Splunk SOAR** course.

SOAR stands for **Security Orchestration, Automation, and Response**. It connects different security tools and automates repetitive tasks so analysts can focus on real threats.

What I learned:
- **Orchestration** — connecting tools together so they can talk to each other
- **Automation** — making the tools do tasks without a human clicking
- **Response** — taking action based on what the tools find
- **Playbooks** — the step-by-step instructions SOAR follows

🔗 [Splunk SOAR](https://www.splunk.com)

---

## ✅ What I Did

### Sketched a simple playbook for a phishing alert

**Trigger:** A user reports a suspicious email, or an email filter flags one.

**Playbook steps:**

1. **Extract** the email details (sender, subject, links, attachments).
2. **Check** the sender against known blocklists.
3. **Scan** any links in a sandbox (safe environment).
4. **Scan** any attachments for malware.
5. **Search** the email gateway to see if anyone else received it.
6. **Decide:**
   - If safe → close the alert, tell the user it was safe.
   - If malicious → continue.
7. **Contain** — quarantine the email from all inboxes.
8. **Block** the sender domain across the organization.
9. **Notify** the user and the security team.
10. **Log** everything in the incident record.

### Why this playbook works
It removes the boring, repetitive steps (checking, searching) so analysts can focus on judgment calls (is this really malicious?).

---

## 💡 Key Takeaways

- Automation does not replace analysts. It removes the boring parts so they can focus on real decisions.
- Playbooks make response consistent. Everyone follows the same steps.
- Phishing is one of the most automatable alerts because the steps are predictable.
- A good playbook has clear decisions and clear actions at every step.

---

## ❓ Questions

- How do you test a playbook before using it for real?
- What happens when a playbook makes a wrong decision?

---

## ⏱️ Time Spent

45 minutes

---

## ✅ Completed

- [x] Took Intro to Splunk SOAR
- [x] Sketched a phishing response playbook

---

<div align="center">

[← Previous: Day 18](day-18-hands-on-spl.md) · [Back to Week 3](README.md) · [Next: Day 20 →](day-20-inside-the-soc.md)

</div>