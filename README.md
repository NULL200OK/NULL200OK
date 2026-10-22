<!-- ═══════════════════════════════════════════════════════════════════
     يجب أن يكون هذا الملف في مستودع عام باسم  NULL200OK/NULL200OK
     مع مجلد assets/ و .github/workflows/ بجانبه.
     Must live in a public repo named exactly  NULL200OK/NULL200OK
     together with the assets/ and .github/workflows/ folders.
     ═══════════════════════════════════════════════════════════════════ -->

<!-- ───────────────────────── HEADER ───────────────────────── -->
<p align="center">
  <img src="./assets/banner.svg" width="100%" alt="NULL200OK — Offensive Security"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=FF1A3C&center=true&vCenter=true&width=760&height=48&lines=%24+whoami+%E2%86%92+Nabil+Hassan+%28NULL200OK%29;Breaking+things+so+they+can+be+fixed.;Recon+%E2%86%92+Exploit+%E2%86%92+Persist+%E2%86%92+Report.;Red+Team+%7C+Web+%26+Mobile+Pentest+%7C+Tooling;%D8%A7%D9%84%D9%87%D8%AC%D9%88%D9%85+%D9%87%D9%88+%D8%A3%D9%81%D8%B6%D9%84+%D9%88%D8%B3%D9%8A%D9%84%D8%A9+%D9%84%D9%84%D8%AF%D9%81%D8%A7%D8%B9" alt="Typing SVG"/>
  </a>
</p>

<!-- ───────────────────────── NAV ───────────────────────── -->
<p align="center">
  <a href="#whoami"><img src="https://img.shields.io/badge/01-whoami-ff1a3c?style=for-the-badge&labelColor=0d1117"/></a>
  <a href="#recon"><img src="https://img.shields.io/badge/02-attack_surface-ff1a3c?style=for-the-badge&labelColor=0d1117"/></a>
  <a href="#missions"><img src="https://img.shields.io/badge/03-missions-ff1a3c?style=for-the-badge&labelColor=0d1117"/></a>
  <a href="#arsenal"><img src="https://img.shields.io/badge/04-arsenal-ff1a3c?style=for-the-badge&labelColor=0d1117"/></a>
  <a href="#project"><img src="https://img.shields.io/badge/05-project-ff1a3c?style=for-the-badge&labelColor=0d1117"/></a>
  <a href="#telemetry"><img src="https://img.shields.io/badge/06-telemetry-ff1a3c?style=for-the-badge&labelColor=0d1117"/></a>
  <a href="#ctf"><img src="https://img.shields.io/badge/07-capture_the_flag-2ea043?style=for-the-badge&labelColor=0d1117"/></a>
  <a href="#contact"><img src="https://img.shields.io/badge/08-contact-ff1a3c?style=for-the-badge&labelColor=0d1117"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Role-Offensive%20Security%20Engineer-ff1a3c?style=flat-square&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Focus-Red%20Teaming-8b0000?style=flat-square&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Mode-Authorized%20Testing%20Only-2ea043?style=flat-square&labelColor=0d1117"/>
  <img src="https://komarev.com/ghpvc/?username=NULL200OK&label=VIEWS&color=ff1a3c&style=flat-square&labelColor=0d1117" alt="views"/>
  <a href="https://github.com/NULL200OK?tab=followers"><img src="https://img.shields.io/github/followers/NULL200OK?label=FOLLOWERS&style=flat-square&color=ff1a3c&labelColor=0d1117" alt="followers"/></a>
</p>

<p align="center"><img src="./assets/ticker.svg" width="100%" alt="tools and techniques ticker"/></p>

<!-- ───────────────────────── WHOAMI ───────────────────────── -->
<h2 id="whoami">🩸 ~/whoami</h2>

<p align="center"><img src="./assets/terminal.svg" width="100%" alt="animated terminal"/></p>

> **I think like an attacker so defenders don't have to learn the hard way.**
> I map attack surfaces, chain small weaknesses into real impact, and turn the findings into reports that engineering teams can actually act on.

```yaml
name:        Nabil Hassan  (NULL200OK)
title:       Cybersecurity Expert · Offensive Security · Software Developer
specialty:   Red Team ops · web & mobile pentesting · exploit research · custom tooling
also:        AI-assisted security automation
languages:   [ العربية, English ]
philosophy:  "If it has an input, it has an attack surface."
ethics:      scope first · written authorization always · responsible disclosure
```

<p align="center"><img src="./assets/divider.svg" width="100%" alt=""/></p>

<!-- ───────────────────────── RECON ───────────────────────── -->
<h2 id="recon">📡 Attack Surface — live radar</h2>

<table>
  <tr>
    <td width="46%" align="center" valign="middle">
      <img src="./assets/radar.svg" width="100%" alt="animated radar"/>
    </td>
    <td width="54%" valign="top">

**🌐 WEB** — OWASP Top 10, auth & session flaws, IDOR / BOLA, SSRF, injection, business-logic abuse

**🔌 API** — REST / GraphQL, broken object-level auth, mass assignment, rate-limit bypass

**📱 MOBILE** — Android RE, APK static & dynamic analysis, SSL-pinning & root-detection bypass

**🏰 AD** — attack-path mapping, Kerberos abuse, ACL misconfigurations, lateral movement

**☁️ CLOUD** — IAM misconfigurations, exposed storage, metadata-service abuse

**🕸 NETWORK** — service enumeration, protocol weaknesses, segmentation & pivoting

    </td>
  </tr>
</table>

<h3>⛓ Engagement flow</h3>

<p align="center"><img src="./assets/chain.svg" width="100%" alt="animated kill chain"/></p>

<p align="center"><img src="./assets/divider.svg" width="100%" alt=""/></p>

<!-- ───────────────────────── MISSIONS ───────────────────────── -->
<h2 id="missions">🗂 Missions — click to expand</h2>

<details>
<summary><b>🌐 &nbsp;Web &amp; API pentest checklist</b> &nbsp;<sub>(click)</sub></summary>

<br>

| Phase | What I look at |
|---|---|
| **Recon** | subdomains, tech stack, JS files, hidden endpoints, exposed `.git` / backups |
| **Auth** | weak resets, session fixation, JWT misuse, OAuth redirect flaws, 2FA bypass |
| **Access control** | IDOR / BOLA, forced browsing, role & tenant confusion |
| **Input** | SQLi / NoSQLi, XSS, SSTI, XXE, command injection, SSRF, file upload |
| **Logic** | race conditions, price / quantity tampering, workflow skipping |
| **Reporting** | reproducible PoC · impact in business terms · concrete fix · retest |

</details>

<details>
<summary><b>📱 &nbsp;Android security checklist</b> &nbsp;<sub>(click)</sub></summary>

<br>

- [x] Decompile & review manifest: exported components, debuggable / backup flags
- [x] Insecure storage: SharedPreferences, SQLite, logs, clipboard
- [x] Network: cleartext traffic, weak TLS, certificate-pinning strength
- [x] Deep links, intents & WebView misconfigurations
- [x] Hard-coded secrets, API keys, tokens
- [x] Runtime tampering resistance: root / emulator / Frida detection
- [x] Backend API behind the app (the real target most of the time)

</details>

<details>
<summary><b>🏰 &nbsp;Active Directory attack path</b> &nbsp;<sub>(click)</sub></summary>

<br>

```mermaid
flowchart LR
    A[Foothold<br/>low-priv user] --> B[Enumerate<br/>users · groups · ACLs]
    B --> C{Weak spots?}
    C -->|Service accounts| D[Kerberoast /<br/>AS-REP roast]
    C -->|Misconfigured ACL| E[ACL abuse]
    C -->|Credentials in shares| F[Credential reuse]
    D --> G[Privileged account]
    E --> G
    F --> G
    G --> H[Domain compromise<br/>→ report & remediate]
    style A fill:#0d1117,stroke:#ff1a3c,color:#fff
    style G fill:#5c0a14,stroke:#ff1a3c,color:#fff
    style H fill:#0d1117,stroke:#2ea043,color:#fff
```

</details>

<details>
<summary><b>🧪 &nbsp;Recon cheat-sheet (lab / authorized targets only)</b> &nbsp;<sub>(click)</sub></summary>

<br>

```bash
# service & version discovery
nmap -sC -sV -T4 -oA scan lab.target.local

# content discovery
ffuf -u https://lab.target.local/FUZZ -w common.txt -mc 200,204,301,302,403

# template-based vulnerability checks
nuclei -u https://lab.target.local -severity medium,high,critical

# quick HTTP probing of a host list
cat hosts.txt | httpx -status-code -title -tech-detect
```

> Run these **only** against systems you own or are explicitly authorized to test.

</details>

<details>
<summary><b>🔁 &nbsp;Engagement lifecycle</b> &nbsp;<sub>(click)</sub></summary>

<br>

```mermaid
sequenceDiagram
    autonumber
    participant C as Client
    participant R as Red Team (me)
    participant T as Target environment
    C->>R: Scope · rules of engagement · authorization
    R->>T: Recon & enumeration
    R->>T: Exploitation (in scope only)
    T-->>R: Evidence · impact
    R->>C: Report · severity · remediation
    C->>R: Fixes deployed
    R->>T: Retest
    R-->>C: Closure letter
```

</details>

<p align="center"><img src="./assets/divider.svg" width="100%" alt=""/></p>

<!-- ───────────────────────── ARSENAL ───────────────────────── -->
<h2 id="arsenal">🧰 Arsenal</h2>

<details open>
<summary><b>Offensive tooling</b></summary>

<p>
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Metasploit-2f6fdb?style=for-the-badge&logo=metasploit&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Frida-d6002f?style=for-the-badge&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Ghidra-b5121b?style=for-the-badge&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/BloodHound-ff1a3c?style=for-the-badge&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/SQLmap-444?style=for-the-badge&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/ffuf-00a86b?style=for-the-badge&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Hashcat-8a2be2?style=for-the-badge&labelColor=0d1117"/>
</p>
</details>

<details open>
<summary><b>Languages</b></summary>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white&labelColor=0d1117"/>
</p>
</details>

<details open>
<summary><b>Platforms &amp; labs</b></summary>

<p>
  <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Parrot_OS-15E0ED?style=for-the-badge&logo=parrotsecurity&logoColor=black&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=black&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Hack_The_Box-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white&labelColor=0d1117"/>
</p>
</details>

<p align="center"><img src="./assets/divider.svg" width="100%" alt=""/></p>

<!-- ───────────────────────── PROJECT ───────────────────────── -->
<h2 id="project">🛡 Featured project — Keep Safe (أمان)</h2>

> The same attacker's eye, turned around: an Android defense app I built for **non-technical users**.

| | |
|---|---|
| 🔗 **Link scanner** | Phishing / malicious URL risk scoring before you open it, also via the system Share menu |
| 🛰 **DNS-filter VPN** | Local VPN that blocks malware & adult domains, with forced SafeSearch and bedtime schedules |
| 👨‍👩‍👧 **Family protection** | Protection levels, custom block / allow lists, PIN-guarded settings, weekly report |
| 🔍 **Phone security check** | 0–100 score with one-tap fixes, plus a private leaked-password check (k-anonymity) |
| 📩 **Scam detection** | Suspicious SMS, calls and email analysis |

<p>
  <img src="https://img.shields.io/badge/Kotlin-Jetpack_Compose-7F52FF?style=flat-square&logo=kotlin&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=black&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Languages-AR%20%C2%B7%20EN%20%C2%B7%20FR%20%C2%B7%20ES%20%C2%B7%20TR-ff1a3c?style=flat-square&labelColor=0d1117"/>
</p>

<p align="center"><img src="./assets/divider.svg" width="100%" alt=""/></p>

<!-- ───────────────────────── TELEMETRY ───────────────────────── -->
<h2 id="telemetry">📊 Telemetry</h2>

<p align="center">
  <a href="https://github.com/NULL200OK">
    <img height="175" src="https://github-readme-stats.vercel.app/api?username=NULL200OK&show_icons=true&hide_border=true&bg_color=0d1117&title_color=ff1a3c&icon_color=ff1a3c&text_color=c9d1d9&ring_color=ff1a3c&count_private=true&include_all_commits=true" alt="GitHub stats"/>
  </a>
  <a href="https://github.com/NULL200OK">
    <img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=NULL200OK&layout=compact&hide_border=true&bg_color=0d1117&title_color=ff1a3c&text_color=c9d1d9&langs_count=8" alt="Top languages"/>
  </a>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=NULL200OK&hide_border=true&background=0d1117&ring=ff1a3c&fire=ff1a3c&currStreakLabel=ff1a3c&currStreakNum=ffffff&sideNums=ffffff&sideLabels=c9d1d9&dates=8b949e" alt="Streak"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=NULL200OK&bg_color=0d1117&color=ff1a3c&line=ff1a3c&point=ffffff&area=true&area_color=ff1a3c&hide_border=true&custom_title=Contribution%20Activity" alt="Activity graph"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=NULL200OK&theme=onedark&no-frame=true&no-bg=true&margin-w=8&column=7" alt="Trophies"/>
</p>

<!-- الأفعى تُولَّد تلقائيًا بعد تشغيل workflow (انظر .github/workflows/snake.yml) -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NULL200OK/NULL200OK/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/NULL200OK/NULL200OK/output/github-snake.svg"/>
    <img alt="contribution snake" src="https://raw.githubusercontent.com/NULL200OK/NULL200OK/output/github-snake-dark.svg"/>
  </picture>
</p>

<p align="center"><img src="./assets/divider.svg" width="100%" alt=""/></p>

<!-- ───────────────────────── CTF ───────────────────────── -->
<h2 id="ctf">🚩 Capture the flag — mini challenge</h2>

Found something odd? Decode it. Send me the flag if you solve it. 😉

<details>
<summary><b>🔒 Classified payload</b> &nbsp;<sub>(click to reveal)</sub></summary>

<br>

```text
U1lOVHthaHl5MjAwYnhfanJ5cGJ6cmZfbGJofQ==
```

<details>
<summary><i>Need a hint?</i></summary>

<br>

`Base64` → then a classic Caesar-style rotation that every beginner learns first. 🔁

</details>

</details>

<br>

<!-- ───────────────────────── QUOTE ───────────────────────── -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=4000&pause=1500&color=2EA043&center=true&vCenter=true&width=700&height=30&lines=Every+system+is+secure+until+someone+asks+the+right+question.;Trust+nothing.+Verify+everything.;Think+like+an+attacker.+Report+like+a+professional." alt="quotes"/>
  </a>
</p>

<!-- ───────────────────────── CONTACT ───────────────────────── -->
<h2 id="contact">📡 Contact</h2>

<p>
  <a href="https://github.com/NULL200OK"><img src="https://img.shields.io/badge/GitHub-NULL200OK-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <!-- أضف روابطك هنا / add your links here — احذف علامات التعليق وعدّل الروابط:
  <a href="mailto:YOUR_EMAIL"><img src="https://img.shields.io/badge/Email-ff1a3c?style=for-the-badge&logo=protonmail&logoColor=white"/></a>
  <a href="https://linkedin.com/in/YOUR_ID"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://x.com/YOUR_ID"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"/></a>
  <a href="https://t.me/YOUR_ID"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/></a>
  -->
</p>

> 💬 Open to: **authorized pentests · red-team engagements · bug bounty collaboration · security tooling projects**

<details>
<summary><b>⚖️ Ethics &amp; disclaimer</b></summary>

<br>

Everything I publish is for **education, research and authorized security testing only**. I only test systems I own or have explicit written permission to assess, I follow responsible-disclosure practice, and I do not support the misuse of any tool or technique shown here. You are responsible for your own actions.

</details>

<p align="center">
  <i>"The only truly secure system is one that is powered off, cast in a block of concrete and sealed in a lead-lined room — and even then I have my doubts."</i><br><sub>— Gene Spafford</sub>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=130&color=0:ff1a3c,55:5c0a14,100:0d1117&section=footer&animation=twinkling" alt="footer"/>
