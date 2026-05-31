<div align="center">
  <img src="https://img.shields.io/badge/RED_TEAM-OPERATOR-ff0000?style=for-the-badge&logo=github&labelColor=%230d1117" alt="Red Team">
  <img src="https://img.shields.io/badge/ADVERSARY-SIMULATION-ff4444?style=for-the-badge&labelColor=%230d1117" alt="Adversary">
  <img src="https://img.shields.io/badge/STATUS-ACTIVE-ff0000?style=for-the-badge&labelColor=%230d1117" alt="Active">
</div>

<br>

<!-- Animated Skull/Target SVG -->
<div align="center">
  <svg width="100" height="100" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <filter id="red-glow">
        <feGaussianBlur stdDeviation="4" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <radialGradient id="pulse-grad" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#ff0000" stop-opacity="0.3">
          <animate attributeName="stop-opacity" values="0.3;0.6;0.3" dur="2s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#ff0000" stop-opacity="0"/>
      </radialGradient>
    </defs>
    <style>
      .ring { animation: spin 4s linear infinite; transform-origin: 50px 50px; }
      .ring2 { animation: spin 3s linear infinite reverse; transform-origin: 50px 50px; }
      .pulse-dot { animation: dot-pulse 1.5s ease-in-out infinite; }
      @keyframes spin { 100% { transform: rotate(360deg); } }
      @keyframes dot-pulse {
        0%, 100% { r: 5; opacity: 1; }
        50% { r: 8; opacity: 0.5; }
      }
    </style>

    <!-- Pulse background -->
    <circle cx="50" cy="50" r="45" fill="url(#pulse-grad)"/>

    <!-- Outer ring -->
    <circle class="ring" cx="50" cy="50" r="40" fill="none" stroke="#ff0000" stroke-width="1.5" stroke-dasharray="8 6" opacity="0.8"/>

    <!-- Middle ring -->
    <circle class="ring2" cx="50" cy="50" r="30" fill="none" stroke="#ff3333" stroke-width="1" stroke-dasharray="4 8" opacity="0.6"/>

    <!-- Crosshair lines -->
    <line x1="10" y1="50" x2="90" y2="50" stroke="#ff0000" stroke-width="0.8" opacity="0.4"/>
    <line x1="50" y1="10" x2="50" y2="90" stroke="#ff0000" stroke-width="0.8" opacity="0.4"/>

    <!-- Skull face -->
    <g filter="url(#red-glow)">
      <circle cx="50" cy="45" r="15" fill="#0d1117" stroke="#ff0000" stroke-width="1.5"/>
      <circle cx="43" cy="42" r="3" fill="#ff0000"/>
      <circle cx="57" cy="42" r="3" fill="#ff0000"/>
      <ellipse cx="50" cy="52" rx="4" ry="2" fill="#ff0000" opacity="0.8"/>
      <!-- Teeth -->
      <line x1="47" y1="54" x2="47" y2="57" stroke="#ff0000" stroke-width="0.8"/>
      <line x1="50" y1="54" x2="50" y2="57" stroke="#ff0000" stroke-width="0.8"/>
      <line x1="53" y1="54" x2="53" y2="57" stroke="#ff0000" stroke-width="0.8"/>
    </g>

    <!-- Center dot -->
    <circle cx="50" cy="50" r="3" fill="#ff0000" filter="url(#red-glow)"/>

    <!-- Corner marks -->
    <path d="M5 50 L15 50 M85 50 L95 50 M50 5 L50 15 M50 85 L50 95" stroke="#ff0000" stroke-width="1.5" opacity="0.6"/>
  </svg>
</div>

<br>

```ascii
██████╗ ███████╗██████╗     ████████╗███████╗ █████╗ ███╗   ███╗
██╔══██╗██╔════╝██╔══██╗    ╚══██╔══╝██╔════╝██╔══██╗████╗ ████║
██████╔╝█████╗  ██║  ██║       ██║   █████╗  ███████║██╔████╔██║
██╔══██╗██╔══╝  ██║  ██║       ██║   ██╔══╝  ██╔══██║██║╚██╔╝██║
██║  ██║███████╗██████╔╝       ██║   ███████╗██║  ██║██║ ╚═╝ ██║
╚═╝  ╚═╝╚══════╝╚═════╝        ╚═╝   ╚══════╝╚═╝  ╚═╝╚═╝     ╚═╝
```

<h1 align="center">
  <code style="color:#ff0000">// RED TEAM OPERATOR // aBadRoy</code>
</h1>

<p align="center">
  <em>Adversary Emulation · Offensive Security · Purple Team Orchestration</em>
</p>

<div align="center">
  <img src="https://img.shields.io/github/followers/aBadRoy?style=flat-square&color=0d1117&labelColor=ff0000&logo=github" alt="Followers">
  <img src="https://img.shields.io/github/stars/aBadRoy?style=flat-square&color=0d1117&labelColor=ff0000&logo=star" alt="Stars">
  <img src="https://img.shields.io/github/last-commit/aBadRoy/aBadRoy?style=flat-square&color=0d1117&labelColor=ff0000&logo=github" alt="Last Updated">
  <img src="https://img.shields.io/badge/C2-ACTIVE-ff0000?style=flat-square&labelColor=0d1117" alt="C2">
</div>

<br>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2500&pause=800&color=FF0000&background=0D1117&center=true&vCenter=true&width=620&lines=Access+is+the+only+law.;Trust+none.+Verify+everything.+Pivot+everywhere.;The+best+defense+is+a+good+offense.;Leave+no+log+uncleared.;Emulate.+Evade.+Exploit.+Exfil." alt="Red Team Quotes">
</div>

---

## ☠️ Operator Profile

```yaml
handle: aBadRoy
role: Red Team Operator
specialty: Adversary Emulation · Web Exploitation · C2 Infrastructure
sector: Offensive Security · VAPT · Purple Team
status: 🔴 Active — Simulating advanced persistent threats
philosophy: "The only way to test the walls is to try to break them down."
```

---

## 🔴 C2 Arsenal

<table>
  <tr>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=python" width="48" height="48" alt="Python"/>
      <br><sub style="color:#ff0000">Python</sub>
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=bash" width="48" height="48" alt="Bash"/>
      <br><sub style="color:#ff0000">Bash</sub>
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=js" width="48" height="48" alt="JS"/>
      <br><sub style="color:#ff0000">JavaScript</sub>
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=linux" width="48" height="48" alt="Linux"/>
      <br><sub style="color:#ff0000">Linux</sub>
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=sqlite" width="48" height="48" alt="SQL"/>
      <br><sub style="color:#ff0000">SQL</sub>
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git"/>
      <br><sub style="color:#ff0000">Git</sub>
    </td>
  </tr>
</table>

<div align="center">
  <img src="https://img.shields.io/badge/Burp_Suite-0d1117?style=flat-square&logo=burpsuite&logoColor=ff0000" alt="Burp">
  <img src="https://img.shields.io/badge/Nmap-0d1117?style=flat-square&logo=nmap&logoColor=ff0000" alt="Nmap">
  <img src="https://img.shields.io/badge/Metasploit-0d1117?style=flat-square&logo=metasploit&logoColor=ff0000" alt="Metasploit">
  <img src="https://img.shields.io/badge/Cobalt_Strike-0d1117?style=flat-square&logo=github&logoColor=ff0000" alt="Cobalt Strike">
  <img src="https://img.shields.io/badge/Wireshark-0d1117?style=flat-square&logo=wireshark&logoColor=ff0000" alt="Wireshark">
  <img src="https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=ff0000" alt="Docker">
  <img src="https://img.shields.io/badge/Splunk-0d1117?style=flat-square&logo=splunk&logoColor=ff0000" alt="Splunk">
  <img src="https://img.shields.io/badge/Nessus-0d1117?style=flat-square&logo=tenable&logoColor=ff0000" alt="Nessus">
  <img src="https://img.shields.io/badge/MITRE_ATT%26CK-0d1117?style=flat-square&logo=github&logoColor=ff0000" alt="MITRE">
</div>

---

## 🎯 Operations (Featured Repos)

| TTP | Project | Description | Status |
|-----|---------|-------------|--------|
| T1059 | [**SilentStrike-XSS**](https://github.com/aBadRoy/SilentStrike-XSS) | XSS detection & neutralization — 100+ payloads, multi-vector | 🔴 Deployed |
| T1595 | [**Nessus-project**](https://github.com/aBadRoy/Nessus-project) | Vulnerability assessment & remediation intelligence | 🟢 Complete |
| T1087 | [**Splunk-SIEM-Home-Lab**](https://github.com/aBadRoy/Splunk-SIEM-Home-Lab) | SOC-grade SIEM deployment & detection engineering | 🟢 Complete |
| T1552 | [**Wi-fi-password-stealer-using-Attiny85**](https://github.com/aBadRoy/Wi-fi-password-stealer-using-Attiny85) | Hardware credential harvest — OpSec research | 🟡 Advisory |
| T1190 | [**owl-book-shop**](https://github.com/aBadRoy/owl-book-shop) | CTF — Full-stack web exploitation playground | 🟢 Complete |
| T1641 | [**nsoql-ctf**](https://github.com/aBadRoy/nsoql-ctf) | NoSQL injection CTF — SHADOW_NET dark-web | 🟢 Complete |
| T1203 | [**Web_exploitation_CTF**](https://github.com/aBadRoy/Web_exploitation_CTF) | Custom CTF machine — WordPress LFI to Root | 🟢 Complete |
| T1204 | [**cyart-vapt-team**](https://github.com/aBadRoy/cyart-vapt-team) | VAPT ops & vulnerability assessment missions | 🟢 Complete |

---

## 📊 Engagement Statistics

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=aBadRoy&show_icons=true&theme=dark&bg_color=0d1117&title_color=ff0000&icon_color=ff0000&text_color=c9d1d9&border_color=30363d&hide_border=true&count_private=true)

![Streak](https://streak-stats.demolab.com/?user=aBadRoy&theme=dark&background=0d1117&ring=ff0000&fire=ff4444&currStreakLabel=ff0000&sideNums=c9d1d9&sideLabels=c9d1d9&dates=8b949e&hide_border=true)

![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=aBadRoy&layout=compact&theme=dark&bg_color=0d1117&title_color=ff0000&text_color=c9d1d9&border_color=30363d&hide_border=true)

</div>

---

## 📡 Activity Telemetry

![Activity](https://github-readme-activity-graph.vercel.app/graph?username=aBadRoy&bg_color=0d1117&color=ff0000&line=ff4444&point=ff0000&area=true&area_color=ff000020&hide_border=true)

---

## 🐍 Kill Chain Coverage

![Snake](https://raw.githubusercontent.com/aBadRoy/aBadRoy/output/github-contribution-grid-snake-dark.svg)

---

## 🔴 Command & Control

<div align="center">
  <table>
    <tr>
      <td>
        <a href="https://github.com/aBadRoy">
          <img src="https://img.shields.io/badge/C2-GitHub-ff0000?style=for-the-badge&logo=github&labelColor=0d1117" alt="GitHub">
        </a>
      </td>
      <td>
        <a href="mailto:thedemonknight16@gmail.com">
          <img src="https://img.shields.io/badge/OPSEC-Email-ff4444?style=for-the-badge&logo=gmail&labelColor=0d1117" alt="Email">
        </a>
      </td>
    </tr>
  </table>
</div>

---

<div align="center">
  <pre style="color:#ff0000;background:#0d1117;padding:15px;border:1px solid #ff000044;">
    ╔══════════════════════════════════════════════════════╗
    ║  "Access is the only law.                           ║
    ║   Everything else is just a firewall waiting        ║
    ║   to be breached."                                  ║
    ║                                                      ║
    ║   🔴 RED TEAM — SIMULATE. EVADE. EXPLOIT. 🔴      ║
    ╚══════════════════════════════════════════════════════╝
  </pre>
  <br>
  <sub style="color:#8b949e">
    <code># Trust none. Verify everything. Pivot everywhere.</code>
  </sub>
</div>
