<div align="center">

# Day 13 — Wireless & Mobile

**Week 2 · Network & Endpoint Defense**

`~30 min` · `Read + Audit`

</div>

---

## 🎯 Focus

Study wireless and mobile attacks and audit your network.

---

## 📚 Learned

I studied wireless and mobile security and audited my network.

What I learned:
- **WPA3** is the current standard for Wi-Fi security. It replaces WPA2.
- **WPA2** still works but is less secure, especially against offline password guessing.
- **WEP** is broken. Never use it.
- Common wireless attacks: evil twin (fake hotspot), deauthentication, password cracking.
- Mobile risks: malicious apps, outdated OS, unsecured public Wi-Fi, SIM swapping.

🔗 [Endpoint Security | Module 1](https://u.cisco.com)

---

## ✅ What I Did

### Audited my Wi-Fi

**Is my Wi-Fi WPA3-ready?**

| Check | Result |
|-------|--------|
| Router supports WPA3? | Yes |
| Currently using WPA3? | No — was on WPA2 |
| Guest network enabled? | No |
| Router firmware up to date? | No — updated it |
| Default admin password changed? | Yes |

**What I did:**
1. Updated the router firmware
2. Switched from WPA2 to WPA3
3. Enabled the guest network and isolated it from the main network
4. Confirmed the admin password was not the default

### Mobile audit
- Checked for OS updates on my phone — updated
- Reviewed app permissions — removed two apps with unnecessary access
- Disabled auto-connect to open Wi-Fi networks

---

## 💡 Key Takeaways

- WPA3 is better. Use it if your router supports it.
- Guest Wi-Fi should be isolated. Guests should not see your devices.
- Router firmware updates matter. They often fix serious bugs.
- Public Wi-Fi is risky. Use a VPN or mobile data when possible.
- App permissions should be reviewed. Most apps ask for more than they need.

---

## ❓ Questions

- What is the difference between WPA3-Personal and WPA3-Enterprise?
- How does an evil twin attack work in practice?

---

## ⏱️ Time Spent

30 minutes

---

## ✅ Completed

- [x] Studied wireless and mobile attacks
- [x] Audited my Wi-Fi network
- [x] Audited mobile device security

---

<div align="center">

[← Previous: Day 12](day-12-access-control.md) · [Back to Week 2](README.md) · [Next: Day 14 →](day-14-access-control-lists.md)

</div>