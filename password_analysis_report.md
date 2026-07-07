# Password Strength Analysis Report

## 1. Overview

This report analyzes different passwords with varying levels of complexity to understand how password length, character variety, and predictability affect overall password security.

The passwords were tested using an online password strength evaluation tool.

---

## 2. Objective

The objective of this task was to:

- Create passwords with different complexity levels.
- Test password strength using a password evaluation tool.
- Analyze the effect of password length and character diversity.
- Understand common password attacks.
- Identify best practices for creating secure passwords.

---

## 3. Tool Used

| Tool | Purpose |
|---|---|
| Password Meter | Password strength evaluation |

---

# 4. Password Strength Results

## 4.1 Weak Password Test

### Password Tested

```
password123
```

### Result

**Strength:** Very Weak

### Observations

- Uses a common dictionary word.
- Contains a predictable number sequence.
- No uppercase letters.
- No special characters.
- Easily guessed using automated attacks.

### Security Risk

This type of password is vulnerable to:

- Dictionary attacks
- Brute-force attacks
- Credential guessing

---

## 4.2 Medium Complexity Password Test

### Password Tested

```
Password@123
```

### Result

**Strength:** Fair

### Observations

Positive factors:

- Contains uppercase letters.
- Contains lowercase letters.
- Includes numbers.
- Includes a special character.

Weakness:

- Uses a common word.
- Contains predictable number sequence (`123`).

### Security Analysis

Adding symbols and character variety improves security, but predictable patterns reduce effectiveness.

---

## 4.3 Strong Password Test

### Password Tested

```
BlueTiger$RunsFast2026!
```

### Result

**Strength:** Very Strong

### Observations

Positive factors:

- Long password length.
- Uses uppercase and lowercase letters.
- Includes numbers.
- Includes special characters.
- Uses passphrase-style structure.

Minor weakness:

- Contains a year pattern which may be easier to guess if related to personal information.

---

# 5. Effect of Password Complexity

| Factor | Security Impact |
|-|-|
| Length | Longer passwords increase cracking difficulty |
| Uppercase & lowercase letters | Increase possible combinations |
| Numbers | Add additional complexity |
| Symbols | Improve resistance against guessing |
| Avoiding common words | Reduces dictionary attack success |

---

# 6. Common Password Attacks

## Brute Force Attack

A brute force attack attempts every possible password combination until the correct one is discovered.

Longer and more complex passwords greatly increase the time required.

---

## Dictionary Attack

A dictionary attack uses lists of common words, leaked passwords, and predictable patterns.

Passwords such as:

```
password123
admin123
qwerty
```

are highly vulnerable.

---

# 7. Password Best Practices

Recommended practices:

- Use passwords of at least 12-16 characters.
- Prefer passphrases.
- Mix uppercase and lowercase letters.
- Include numbers and symbols.
- Avoid personal information.
- Avoid common words and keyboard patterns.
- Use unique passwords for every account.
- Enable Multi-Factor Authentication (MFA).
- Use a password manager.

---

# 8. Conclusion

The analysis shows that password strength improves significantly when password length increases and multiple character types are used.

Short and predictable passwords can be cracked easily, while long passphrase-based passwords provide stronger protection against brute force and dictionary attacks.