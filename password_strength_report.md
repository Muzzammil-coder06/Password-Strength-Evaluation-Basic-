 # 🔐 Password Strength Evaluation Report

## 🎯 Objective
To understand the components of a strong password and evaluate various passwords using online strength checkers. The goal is to identify best practices that enhance password security and defend against common password attacks.

---

## 🛠️ Tools Used
- [PasswordMeter](https://www.passwordmeter.com/)
- [Kaspersky Password Checker](https://password.kaspersky.com/)
- [NordPass Strength Checker](https://nordpass.com/password-strength-checker/)

---

## 🔢 Password Samples Created and Tested

| Password # | Password | Description |
|------------|----------|-------------|
| P1 | `password123` | Common word + numbers |
| P2 | `Pass1234` | Uppercase + lowercase + numbers |
| P3 | `P@ssw0rd!` | Uppercase + lowercase + number + symbol |
| P4 | `T!m3$Tr@v3L#42` | Complex mix of character types and length |
| P5 | `tH!s1s$Tr0nG@2025!` | Long, complex, unpredictable |

---

## ✅ Test Results

| Password | PasswordMeter Score (%) | Kaspersky Rating | NordPass Rating |
|----------|--------------------------|-------------------|------------------|
| `password123` | 18% | Weak | Very Weak |
| `Pass1234` | 42% | Weak | Weak |
| `P@ssw0rd!` | 76% | Medium | Medium |
| `T!m3$Tr@v3L#42` | 94% | Strong | Strong |
| `tH!s1s$Tr0nG@2025!` | 100% | Very Strong | Excellent |

---

## 🔍 Observations

- **Password Length:** The longer the password, the better the score across all tools.
- **Character Diversity:** Including uppercase, lowercase, numbers, and special characters significantly boosts strength.
- **Predictability:** Simple or commonly used words (even with numbers) are flagged as weak.
- **Substitution:** Replacing letters with numbers and symbols adds complexity.
- **Best Performer:** `tH!s1s$Tr0nG@2025!` – due to its length, unpredictability, and diversity.

---

## 📚 Best Practices for Creating Strong Passwords

1. Use a **minimum of 12–16 characters**.
2. Mix **uppercase**, **lowercase**, **numbers**, and **special characters**.
3. **Avoid real words**, usernames, or personal data (birthdays, names).
4. Create **passphrases** that are easy to remember but hard to guess, e.g. `Tr@v3lN0w!2Italy`.
5. **Don’t reuse** passwords across different accounts.
6. Use a **password manager** for secure storage and generation.
7. Enable **Two-Factor Authentication (2FA)** wherever possible.

---

## 🛡️ Common Password Attacks and Mitigations

| Attack Type         | Description                                           | Mitigation                                      |
|---------------------|-------------------------------------------------------|--------------------------------------------------|
| **Brute Force**     | Tries all possible combinations of characters         | Use long, complex passwords                     |
| **Dictionary Attack** | Uses precompiled lists of common words/passwords    | Avoid dictionary words or patterns              |
| **Credential Stuffing** | Tries leaked credentials from other sites         | Never reuse passwords across sites              |
| **Phishing**        | Tricks user into revealing their credentials          | Be alert, verify sources, use 2FA               |

---

## 🧠 Learnings & Takeaways

- Password strength is not just about length but also **unpredictability** and **character variety**.
- Online strength checkers provide useful **feedback** on how to improve passwords.
- Complex, **non-dictionary** passphrases outperform short, common passwords.
- **Security hygiene** starts with strong passwords, reinforced with **2FA** and a **password manager**.
- Even advanced attacks can be mitigated with a **layered approach to password security**.

---

## 📌 Conclusion

Strong passwords are the first line of defense in cybersecurity. By testing and analyzing different passwords, it’s clear that using diverse character types, avoiding common patterns, and prioritizing length and randomness lead to better protection. This exercise demonstrates the importance of applying best practices for digital safety in both personal and professional contexts.
