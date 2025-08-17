# 🍪 Hack-a-Snack

A beginner-friendly repository where contributors can add **bite-sized cybersecurity challenges**. Each challenge is designed to be simple, fun, and educational — perfect for people learning **Python + Cybersecurity basics**.

This repo will also serve as a **CTF mini-challenge archive**, and challenges may be reused in CTFs hosted by the maintainer (with credits to contributors).

---

## 📂 Repository Structure


```
Hack-a-Snack/
│
├── README.md                # Main project overview
├── CONTRIBUTING.md          # Guidelines for contributors
├── LICENSE                  # Open source license
├── .gitignore               # Git ignore rules
├── CODE_OF_CONDUCT.md       # Community standards
├── SECURITY.md              # Security policy
├── disclaimer.md            # Legal disclaimer
├── .github/                 # GitHub templates & workflows
│   ├── ISSUE_TEMPLATE/      # Issue templates
│   │   ├── challenge-proposal.md
│   │   └── solution-submission.md
│   └── PULL_REQUEST_TEMPLATE.md
├── challenges/              # All challenge files
│   ├── TEMPLATE.md          # Challenge template
│   ├── python/              # Python-based challenges
│   │   └── reverse_string.py
│   ├── regex/               # Regex/log analysis puzzles
│   │   └── find_ip.txt
│   ├── crypto/              # Cryptography challenges
│   │   └── caesar_shift.md
│   └── web/                 # Web/appsec mini challenges
│       └── sql_injection.md
└── solutions/               # Solutions for each challenge
    ├── TEMPLATE.md          # Solution template
    ├── python/
    │   └── reverse_string_solution.py
    ├── regex/
    │   └── find_ip_solution.txt
    ├── crypto/
    │   └── caesar_shift_solution.md
    └── web/
        └── sql_injection_solution.md
```

---

## 🚀 How to Contribute

1. **Fork** this repo.
2. Create a new file in the appropriate folder inside `challenges/`.
3. Add your challenge (with a short description).
4. (Optional but encouraged) Add a solution in `solutions/`.
5. Update `README.md` (Challenge List) with your new challenge.
6. Submit a **Pull Request**.

> ✨ All contributors will be credited. Challenges may also appear in CTFs hosted by the maintainer.

---

## 🍴 Challenge Categories & Examples

### 1. Python 🐍

**Example Challenge:**

```python
# File: challenges/python/reverse_string.py
# Task: Reverse the following string without using [::-1]

s = "h4ckth3pl4net"
# Expected output: "tenalp3htkc4h"
```

### 2. Regex / Log Analysis 🥷

**Example Challenge:**

```
# File: challenges/regex/find_ip.txt
# Task: Extract all IP addresses from the given log.

[INFO] Connection from 192.168.0.10
[INFO] Connection from 10.0.0.5
[ERROR] Failed login from 172.16.4.22
```

Expected regex should capture: `192.168.0.10`, `10.0.0.5`, `172.16.4.22`

### 3. Crypto 🔐

**Example Challenge:**

```md
# File: challenges/crypto/caesar_shift.md
Task: The following text was encrypted with Caesar cipher (shift 3). Decrypt it.

Encrypted: khoor zruog
```

Expected Answer: `hello world`

### 4. Web/AppSec 🌐

**Example Challenge:**

```md
# File: challenges/web/sql_injection.md
Task: Identify the vulnerability in this query.

SELECT * FROM users WHERE username = 'admin' AND password = ' ' OR '1'='1';
```

Expected: SQL Injection vulnerability.

---

## 🏆 Solutions

Solutions are stored in `/solutions/` with the same folder structure. Example:

```
solutions/python/reverse_string_solution.py
solutions/regex/find_ip_solution.txt
solutions/crypto/caesar_shift_solution.md
solutions/web/sql_injection_solution.md
```

---

## 🙌 Credits

* Maintained by: **Dharan Ragunathan**
* Contributors: [![All Contributors](https://img.shields.io/badge/all_contributors-0-orange.svg?style=flat-square)](#contributors-)

---

## ✨ Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://allcontributors.org) specification. Contributions of any kind welcome!
