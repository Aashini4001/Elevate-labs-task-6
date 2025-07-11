# Cybersecurity Internship-Task 6
# Create a Strong Password and Evaluate its Strength

## 🎯 Objective

To understand the characteristics that make a password strong and evaluate its strength using online password strength tools.


## 🧪 Methodology

### **Tools Used:**

- [Password Meter](https://www.passwordmeter.com/)
- NordPass Password Strength Checker
- Kaspersky Password Checker

### **Password Samples Tested:**

| Password | Description |
| --- | --- |
| `12345678` | Common, numeric only |
| `P@ssword` | Common word with one symbol |
| `MyD0g$N@meIsB1ngo!` | Long, complex with substitutions |
| `qwertyuiop` | Keyboard pattern |
| `Tr0ub4dor&3` | Based on a popular XKCD comic example |
| `uK3$8m!9X@7lQ#2d` | Randomly generated secure password |

---

## 📊 Results

### **Password Meter (passwordmeter.com):**

| Password | Score (%) | Strength | Comments |
| --- | --- | --- | --- |
| `12345678` | 4% | Very Weak | Too short, numeric only |
| `P@ssword` | 54% | Weak | Predictable pattern |
| `MyD0g$N@meIsB1ngo!` | 100% | Very Strong | High complexity and length |
| `qwertyuiop` | 22% | Very Weak | Pattern-based, easy to guess |
| `Tr0ub4dor&3` | 74% | Strong | Good mix but partially predictable |
| `uK3$8m!9X@7lQ#2d` | 100% | Very Strong | Random, long, and complex |


## 🧠 Analysis

### What Makes a Password Strong?

A strong password typically has:

- **Length**: ≥ 12 characters
- **Character Variety**: Mix of uppercase, lowercase, digits, and special characters
- **Unpredictability**: No common words, patterns, or reused passwords
- **Randomness**: Ideally, generated by a password manager or passphrase generator

### Weak Password Pitfalls

- Short length
- Common words or sequences (like `123456`, `qwerty`)
- Leetspeak replacements alone aren’t enough (`P@ssword`)
- Keyboard patterns (`asdfgh`, `qwerty`) are easily guessed

---

## ✅ Recommendations

- Use passphrases (e.g., `B1gC@tJumps0ver2Moon!`) — easy to remember but hard to crack
- Consider password managers for generating and storing complex passwords
- Avoid reusing passwords across services
- Enable two-factor authentication (2FA) wherever possible
