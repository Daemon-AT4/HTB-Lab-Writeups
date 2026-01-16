```markdown
```

 ██░ ██ ▄▄▄█████▓ ▄▄▄▄      ██▓    ▄▄▄       ▄▄▄▄    ██████
▓██░ ██▒▓  ██▒ ▓▒▓█████▄   ▓██▒   ▒████▄    ▓█████▄ ▒██    ▒
▒██▀▀██░▒ ▓██░ ▒░▒██▒ ▄██  ▒██░   ▒██  ▀█▄  ▒██▒ ▄██░ ▓██▄
░▓█ ░██ ░ ▓██▓ ░ ▒██░█▀    ▒██░   ░██▄▄▄▄██ ▒██░█▀    ▒   ██▒
░▓█▒░██▓  ▒██▒ ░ ░▓█  ▀█▓  ░██████▒▓█   ▓██▒░▓█  ▀█▓▒██████▒▒
 ▒ ░░▒░▒  ▒ ░░   ░▒▓███▀▒  ░ ▒░▓  ░▒▒   ▓▒█░░▒▓███▀▒▒ ▒▓▒ ▒ ░
 ▒ ░▒░ ░    ░    ▒░▒   ░   ░ ░ ▒  ░ ▒   ▒▒ ░▒░▒   ░ ░ ░▒  ░ ░
 ░  ░░ ░  ░       ░    ░     ░ ░    ��   ▒    ░    ░ ░  ░  ░
 ░  ░  ░          ░            ░  ░     ░  ░ ░            ░
                       ░                          ░

╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                                          ║
║    ██╗    ██╗██████╗ ██╗████████╗███████╗██╗   ██╗██████╗ ███████╗                     ║
║    ██║    ██║██╔══██╗██║╚══██╔══╝██╔════╝██║   ██║██╔══██╗██╔════╝                     ║
║    ██║ █╗ ██║██████╔╝██║   ██║   █████╗  ██║   ██║██████╔╝███████╗                     ║
║    ██║███╗██║██╔══██╗██║   ██║   ██╔══╝  ██║   ██║██╔═══╝ ╚════██║                     ║
║    ╚███╔███╔╝██║  ██║██║   ██║   ███████╗╚██████╔╝██║     ███████║                     ║
║     ╚══╝╚══╝ ╚═╝  ╚═╝╚═╝   ╚═╝   ╚══════╝ ╚═════╝ ╚═╝     ╚══════╝                     ║
║                                                                                          ║
║   ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀          ║
║   ░░░ HACK THE BOX // EXPLOITATION ARCHIVE // ATTACK PATH DOCUMENTATION ░░░             ║
║   ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀          ║
║                                                                                          ║
╚══════════════════════════════════════════════════════════════════════════════╝

<div align="center">

![HackTheBox](https://img.shields.io/badge/HACK_THE_BOX-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)
![Status](https://img.shields.io/badge/STATUS-ACTIVE_DEVELOPMENT-ff00ff?style=for-the-badge)
![Author](https://img.shields.io/badge/AUTHOR-NETRUNNER-00ffff?style=for-the-badge&logo=ghost&logoColor=white)

</div>

---

> 💀 Personal collection of Hack The Box lab writeups with detailed attack chains, credential dumps, and MITRE ATT&CK mappings.

---

## `>>> TARGET_INDEX`

### 💾 Windows Machines

| Machine | Difficulty | Attack Vector | Status |
|:--------|:----------:|:--------------|:------:|
| [Support](machines/windows/Support/HTB_Lab_AD_Support.md) | ![Easy](https://img.shields.io/badge/-EASY-brightgreen?style=flat-square) | LDAP + GenericAll + RBCD | `[PWNED]` |
| [Sauna](machines/windows/Sauna/HTB-Sauna.md) | ![Easy](https://img.shields.io/badge/-EASY-brightgreen?style=flat-square) | AS-REP Roasting + DCSync | `[PWNED]` |

### 🐧 Linux Machines

| Machine | Difficulty | Attack Vector | Status |
|:--------|:----------:|:--------------|:------:|
| [MetaTwo](machines/Linux/HTB-MetaTwo.md) | ![Easy](https://img.shields.io/badge/-EASY-brightgreen?style=flat-square) | WordPress SQLi + XXE + Passpie | `[PWNED]` |

---

## `>>> ATTACK_CATEGORIES`

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                                                                                 │
│   ████████╗███████╗ ██████╗██╗  ██╗███╗   ██╗██╗ ██████╗ ██╗   ██╗███████╗    │
│   ╚══██╔══╝██╔════╝██╔════╝██║  ██║████╗  ██║██║██╔═══██╗██║   ██║██╔════╝    │
│      ██║   █████╗  ██║     ███████║██╔██╗ ██║██║██║   ██║██║   ██║█████╗      │
│      ██║   ██╔══╝  ██║     ██╔══██║██║╚██╗██║██║██║▄▄ ██║██║   ██║██╔══╝      │
│      ██║   ███████╗╚██████╗██║  ██║██║ ╚████║██║╚██████╔╝╚██████╔╝███████╗    │
│      ╚═╝   ╚══════╝ ╚═════╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝ ╚══▀▀═╝  ╚═════╝ ╚══════╝    │
│                                                                                 │
├─────────────────────────────────────────────────────────────────────────────────┤
│  [+] Active Directory Exploitation                                              │
│  [+] LDAP Enumeration & Attacks                                                 │
│  [+] Resource-Based Constrained Delegation (RBCD)                               │
│  [+] BloodHound Attack Path Analysis                                            │
│  [+] Credential Harvesting                                                      │
│  [+] .NET Binary Reverse Engineering                                            │
│  [+] Kerberos Ticket Manipulation (AS-REP Roasting)                             │
│  [+] DCSync Attack & Domain Compromise                                          │
│  [+] WordPress Vulnerability Exploitation                                       │
│  [+] SQL Injection (SQLi) Attacks                                               │
│  [+] XML External Entity (XXE) Injection                                        │
│  [+] Password Manager Exploitation (Passpie)                                    │
│  [+] PGP Key Cracking                                                           │
└─────────────────────────────────────────────────────────────────────────────────┘
```

---

## `>>> TOOLS_ARSENAL`

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│  🔧 EXPLOITATION TOOLKIT                                                        │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│  ▸ Impacket ────────── Python collection for network protocols                 │
│  ▸ BloodHound ──────── AD attack path visualization                            │
│  ▸ Evil-WinRM ──────── Windows Remote Management shell                         │
│  ▸ NetExec ─────────── Network service enumeration                             │
│  ▸ Rustscan ────────── Fast port scanner                                       │
│  ▸ Rubeus ──────────── Kerberos interaction toolkit                            │
│  ▸ PowerView ───────── PowerShell AD enumeration                               │
│  ▸ SQLMap ──────────── Automated SQL injection tool                            │
│  ▸ WPScan ──────────── WordPress vulnerability scanner                         │
│  ▸ Hashcat ─────────── Advanced password recovery                              │
│  ▸ John the Ripper ─── Password hash cracking                                  │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

---

## `>>> STATISTICS`

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║   📊 PWNED MACHINES                                                          ║
║   ════════════════════════════════════════════════════════════════           ║
║                                                                              ║
║   TOTAL......: 3                                                             ║
║   WINDOWS....: 2                                                             ║
║   LINUX......: 1                                                             ║
║   ACTIVE DIR.: 2                                                             ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                                          ║
║   ░█▀█░█░█░▀█▀░█░█░█▀█░█▀▄                                                               ║
║   ░█▀█░█░█░░█░░█▀█░█░█░█▀▄                                                               ║
║   ░▀░▀░▀▀▀░░▀░░▀░▀░▀▀▀░▀░▀                                                               ║
║                                                                                          ║
║   OPERATOR: Netrunner                                                                    ║
║   STATUS: Active Development                                                             ║
║   PURPOSE: Educational & CTF Documentation                                               ║
║                                                                                          ╚══════════════════════════════════════════════════════════════════════════════╝
```

---

<div align="center">

![Made With](https://img.shields.io/badge/MADE_WITH-OBSIDIAN_&_VIM-ff00ff?style=for-the-badge&logo=obsidian&logoColor=white)
![License](https://img.shields.io/badge/LICENSE-EDUCATIONAL_USE-00ff00?style=for-the-badge)

</div>
```