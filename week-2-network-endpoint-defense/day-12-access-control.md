<div align="center">

# Day 12 — Access Control

**Week 2 · Network & Endpoint Defense**

`~30 min` · `Read + Review`

</div>

---

## 🎯 Focus

Learn about AAA and least-privilege models.

---

## 📚 Learned

I read the chapter on access control from the CCST Cybersecurity 100-160 Official Cert Guide.

### The main concepts

- **AAA** — Authentication (who are you?), Authorization (what can you do?), Accounting (what did you do?)
- **Least privilege** — give people the minimum access they need to do their job, nothing more
- **Role-based access** — assign permissions by role, not by person

### Why it matters

Most insider incidents happen because someone had access they should not have had.

---

## ✅ What I Did

### Reviewed permissions on a shared folder

I checked the permissions on a shared folder used by my team.

**What I found:**
- 12 people had access
- 4 of them had full control (they only needed read access)
- 2 people had not used the folder in over a year
- One external contractor still had access

**What I did:**
- Removed full control from the 4 people who only needed read
- Removed the 2 inactive users
- Removed the external contractor
- Left access for the people who actually need it

**Result:** Access went from 12 people to 6 people. Same work gets done, less risk.

---

## 💡 Key Takeaways

- Least privilege is not about being strict. It is about being correct.
- Access tends to grow over time if nobody reviews it.
- Old accounts are a hidden risk. Clean them up regularly.
- "Can everyone see this?" is a question worth asking monthly.

---

## ❓ Questions

- What is the difference between RBAC and ABAC?
- How often should access reviews happen in a real company?

---

## ⏱️ Time Spent

30 minutes

---

## ✅ Completed

- [x] Read the access control chapter
- [x] Reviewed permissions on a shared folder
- [x] Removed excess access

---

<div align="center">

[← Previous: Day 11](day-11-harden-a-network.md) · [Back to Week 2](README.md) · [Next: Day 13 →](day-13-wireless-mobile.md)

</div>