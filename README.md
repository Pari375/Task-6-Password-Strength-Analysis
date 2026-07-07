# Task 6: Password Strength Analysis

## Overview

This project demonstrates password strength evaluation using an online password analysis tool.

Different passwords with varying levels of complexity were tested to understand how factors such as length, uppercase and lowercase letters, numbers, symbols, and predictability affect password security.

---

## Objective

The objective of this task was to:

- Create multiple passwords with different complexity levels.
- Test passwords using a strength checker.
- Analyze password strength results.
- Understand how complexity affects password security.
- Learn common password attacks and prevention techniques.

---

## Tool Used

- Password Meter (Online Password Strength Checker)

---

## Repository Structure

```
Task-6-Password-Strength-Analysis/
│
├── README.md
├── password_analysis_report.md
└── screenshots/
    ├── 01_weak_password.png
    ├── 02_medium_password.png
    └── 03_strong_password.png
```

---

## Passwords Tested

| Password Type | Strength Result |
|---|---|
| Common password | Very Weak |
| Mixed characters password | Fair |
| Long passphrase-style password | Very Strong |

---

## Analysis Summary

### Weak Password

Example:

```
password123
```

Issues identified:

- Commonly used password.
- Contains dictionary words.
- Uses predictable number sequence.
- Low resistance against guessing attacks.

---

### Medium Strength Password

Example:

```
Password@123
```

Improvements:

- Uses uppercase and lowercase letters.
- Includes numbers.
- Includes a symbol.

Weakness:

- Still contains predictable words and patterns.

---

### Strong Password

Example:

```
BlueTiger$RunsFast2026!
```

Strength factors:

- Longer length.
- Combination of multiple character types.
- Passphrase-based structure.
- Higher resistance against cracking attempts.

---

## Common Password Attacks

### Brute Force Attack

Attackers attempt all possible password combinations until the correct password is discovered.

### Dictionary Attack

Attackers use lists of common words and leaked passwords to guess credentials.

---

## Best Practices Learned

- Use long passwords or passphrases.
- Include uppercase and lowercase characters.
- Add numbers and symbols.
- Avoid common words and personal information.
- Avoid reusing passwords.
- Use password managers.
- Enable Multi-Factor Authentication (MFA).

---

## Conclusion

The analysis demonstrated that password length and unpredictability have a major impact on password security.

Long passphrase-style passwords with varied character types provide significantly stronger protection compared to short or commonly used passwords.