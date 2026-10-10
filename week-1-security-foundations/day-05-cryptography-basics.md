<div align="center">

# Day 05 — Cryptography Basics

**Week 1 · Security Foundations**

`~30 min` · `Read + Practice`

</div>

---

## 🎯 Focus

Cryptography basics — hashing vs. encryption.

---

## 📚 Learned

I learned the difference between **hashing** and **encryption**.

### Hashing
- One-way. You cannot reverse it.
- Same input always gives the same output.
- Used to check if data has been changed.
- Example: SHA-256, MD5

### Encryption
- Two-way. You can decrypt it with the right key.
- Used to keep data secret.
- Example: AES, RSA

🔗 [Endpoint Security | 10.1.14](https://u.cisco.com)

---

## ✅ What I Did

### Hashed a sample file and verified its integrity

1. Created a small text file.
2. Ran a hash tool on it to get the fingerprint.
3. Changed one character in the file.
4. Hashed it again.
5. The hash was completely different.

This is how integrity checks work. If even one bit changes, the hash changes.

---

## 🔐 Hashing vs. Encryption — Side by Side

| | Hashing | Encryption |
|---|---------|------------|
| Direction | One-way | Two-way |
| Reversible | No | Yes, with key |
| Purpose | Verify integrity | Keep data secret |
| Example use | Password storage, file checksums | HTTPS, disk encryption |
| Algorithms | SHA-256, MD5 | AES, RSA |

---

## 💡 Key Takeaways

- Hashing proves data has not changed.
- Encryption keeps data private.
- Passwords should be hashed, not encrypted.
- HTTPS uses encryption to protect traffic in transit.

---

## ❓ Questions

- Why is MD5 considered weak today?
- How does HTTPS use both hashing and encryption?

---

## ⏱️ Time Spent

30 minutes

---

## ✅ Completed

- [x] Learned hashing vs. encryption
- [x] Hashed a file and verified integrity

---

<div align="center">

[← Previous: Day 4](day-04-passwords-mfa.md) · [Back to Week 1](README.md) · [Next: Day 6 →](day-06-explore-cisco-u.md)

</div>