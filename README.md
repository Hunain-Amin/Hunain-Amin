<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:08090f,50:0e111a,100:ff2fb0&height=200&section=header&text=Hunain%20Amin&fontSize=48&fontColor=00E5FF&fontAlignY=38&desc=Cybersecurity%20%2B%20Home%20Lab%20Operator&descAlignY=58&descColor=e8edf7&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2600&pause=900&color=39FF88&center=true&vCenter=true&width=650&lines=hunain@security:~%24+whoami;BS+Computer+Science+%40+UMT+Lahore;Former+SOC+Intern+%40+Zong+(CMPak);SIEM+%2F+Network+Security+%2F+Cloud" alt="Typing SVG" />

<br/>

[![Open portfolio](https://img.shields.io/badge/-%24_open_portfolio-00E5FF?style=for-the-badge&logo=codeforces&logoColor=black)](https://hunain-amin.github.io)
[![Email](https://img.shields.io/badge/-%24_contact_email-0e111a?style=for-the-badge&logo=gmail&logoColor=39FF88)](mailto:p.hunainamin@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=Hunain-Amin&color=ff2fb0&style=for-the-badge&label=SIGNAL+RECEIVED)

</div>

<br/>

```yaml
# 🔴 🟡 🟢 /home/hunain — whoami
$ cat profile.yml
name: "HUNAIN AMIN"
role: "BS Computer Science student — cybersecurity focus"
experience: "Former SOC Intern @ Zong (CMPak) | firewalls & SIEM"
home_lab: "Wazuh SIEM | network segmentation | cloud infra"
```

<div align="center">

**CYBERSECURITY STUDENT · HOME LAB OPERATOR**
<h2>Securing systems, one <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&duration=2600&pause=900&color=FF2FB0&vCenter=true&width=110&lines=log+line;packet;alert" alt="log line" /> at a time.</h2>

</div>

> **BS Computer Science student (Class of 2027)** building hands-on security operations skills. Having recently completed a **SOC internship at Zong (CMPak)** managing firewalls and SIEM systems, I actively run a self-managed home lab focused on threat detection, network segmentation, and cloud infrastructure hardening.

<br/>

## 🌐 `[01_summary]` About

I'm a Computer Science student at the University of Management and Technology, Lahore. I recently worked at Zong (CMPak) headquarters, gaining hands-on enterprise experience with Security Operations Center protocols, firewall administration, and SIEM event management. 

Rather than waiting for a classroom to hand me infrastructure, I also built my own: a home lab covering network security, log analysis, and cloud fundamentals. I am comfortable across operating systems, networking, and cloud computing, with active exposure to tools like Wazuh, pfSense, and AWS.

<table>
<tr>
<td align="center"><h2>🛡️ 3</h2><sub>SIEM &amp; network security tools deployed</sub></td>
<td align="center"><h2>🖧 6+</h2><sub>VLANs designed in enterprise network sim</sub></td>
<td align="center"><h2>🚨 ~427K</h2><sub>events logged by my AWS honeypot</sub></td>
<td align="center"><h2>🎓 2027</h2><sub>expected graduation, BS Computer Science</sub></td>
</tr>
</table>

<br/>

## 📟 `[02_activity]` Home Lab Log

```diff
@@ wazuh-siem :: alerts.log                                      🟢 monitoring @@

+ 00:00:01  INFO  Deployed AWS EC2 instance (Ubuntu Server) — SSH hardened, security groups configured.
+ 00:00:04  OK    Wazuh SIEM online — centralized log collection + file integrity monitoring active.
! 00:00:07  INFO  Custom detection rules written for suspicious activity patterns.
+ 00:00:11  OK    pfSense virtual firewall configured — network segmentation enforced.
- 00:00:14  WARN  Simulated attack behavior detected by custom alert rule — logged for review.
! 00:00:18  INFO  Traffic filtering + access control policies applied across lab segments.
+ 00:00:22  OK    System log analysis pass complete — no unresolved anomalies.
! 00:00:26  INFO  Enterprise network sim: 6+ VLANs, OSPF/RIP routing verified.
! 00:00:30  INFO  Cowrie honeypot exposed on :2222 (AWS EC2) — logs shipped to Wazuh through a reverse SSH tunnel.
- 00:00:34  WARN  Honeypot, 7 weeks: ~427K events, ~53K logins — 3 IPs produced ~95% of traffic. Rules tagged with MITRE ATT&CK.
```

<br/>

## 📂 `[03_projects]` Projects

### ☁️ Internet-Facing SSH Honeypot on AWS, Monitored by Wazuh
![AWS](https://img.shields.io/badge/AWS-0e111a?style=flat-square&logo=amazon-aws&logoColor=00E5FF) ![Wazuh](https://img.shields.io/badge/Wazuh-0e111a?style=flat-square&logo=wazuh&logoColor=ff2fb0) ![MITRE](https://img.shields.io/badge/MITRE_ATT&CK-0e111a?style=flat-square&logo=mitre&logoColor=39ff88)

- Ran a Cowrie SSH honeypot on a free-tier AWS EC2 instance for 7 weeks, with its logs analyzed in a Wazuh SIEM at home.
- Built a reverse SSH tunnel (systemd service) to ship logs home without opening any ports on my network.
- Wrote custom Wazuh detection rules for connections, logins and commands, tagged with MITRE ATT&CK (T1595, T1110, T1059).

**→ [view repository](https://github.com/Hunain-Amin/cowrie-wazuh-honeypot)**

<br/>

### ⚙️ Mini Operating System
![C++](https://img.shields.io/badge/C++-0e111a?style=flat-square&logo=cplusplus&logoColor=00E5FF) ![Systems](https://img.shields.io/badge/OS_Design-0e111a?style=flat-square&logo=linux&logoColor=ff2fb0)

- C++ OS simulator implementing process management, a CPU scheduler, and multithreaded synchronization.
- Banker's Algorithm for deadlock avoidance, evaluating resource requests against safe-state conditions.
- Producer-Consumer problem solved with mutex locks and semaphores to prevent race conditions.

**→ [view repository](https://github.com/Hunain-Amin/hunain-amin-770-PROJECT-MINI_OS)**

<br/>

### 🖧 Enterprise IT Department Network
![Cisco](https://img.shields.io/badge/Cisco_Packet_Tracer-0e111a?style=flat-square&logo=cisco&logoColor=00E5FF) ![Networking](https://img.shields.io/badge/Network_Design-0e111a?style=flat-square&logo=ubiquiti&logoColor=ff2fb0)

- Multi-department enterprise network simulated in Cisco Packet Tracer — 6+ VLANs, 10–20 networked devices.
- Static and dynamic routing (OSPF/RIP) for inter-VLAN and inter-department connectivity.
- ACLs and port security to restrict cross-department access; DHCP for automated IP assignment.

**→ [view repository](https://github.com/Hunain-Amin/Enterprise-IT-department-Network)**

<br/>

## 🛠️ `[04_scan_report]` Skills

| Category | Tools |
|---|---|
| **Security** | ![Wazuh](https://img.shields.io/badge/Wazuh-00E5FF?style=for-the-badge&logo=wazuh&logoColor=black) ![pfSense](https://img.shields.io/badge/pfSense-0e111a?style=for-the-badge&logo=pfsense&logoColor=00E5FF) ![Oracle VM](https://img.shields.io/badge/VirtualBox-ff2fb0?style=for-the-badge&logo=virtualbox&logoColor=white) <br/> `SIEM` `ACLs` `Port Security` `Cowrie Honeypot` `MITRE ATT&CK` |
| **Networking** | ![Cisco](https://img.shields.io/badge/Cisco-39ff88?style=for-the-badge&logo=cisco&logoColor=black) <br/> `Packet Tracer` `VLANs` `OSPF / RIP Routing` `DHCP` `SSH Tunneling` |
| **Cloud** | ![AWS](https://img.shields.io/badge/AWS_EC2-0e111a?style=for-the-badge&logo=amazon-aws&logoColor=00E5FF) ![Hadoop](https://img.shields.io/badge/Hadoop-ff2fb0?style=for-the-badge&logo=apachehadoop&logoColor=white) |
| **Languages** | ![C++](https://img.shields.io/badge/C++-00E5FF?style=for-the-badge&logo=cplusplus&logoColor=black) ![C#](https://img.shields.io/badge/C%23-0e111a?style=for-the-badge&logo=csharp&logoColor=00E5FF) ![Python](https://img.shields.io/badge/Python-ff2fb0?style=for-the-badge&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-39ff88?style=for-the-badge&logo=openjdk&logoColor=black) ![Dart](https://img.shields.io/badge/Dart-0e111a?style=for-the-badge&logo=dart&logoColor=00E5FF) ![HTML](https://img.shields.io/badge/HTML-ff2fb0?style=for-the-badge&logo=html5&logoColor=white) |
| **Frameworks** | ![Flutter](https://img.shields.io/badge/Flutter-00E5FF?style=for-the-badge&logo=flutter&logoColor=black) ![Unity](https://img.shields.io/badge/Unity-0e111a?style=for-the-badge&logo=unity&logoColor=00E5FF) `MATLAB` |

<br/>

## 📜 `[05_credentials]` Education & Certifications

| 🎓 Education | 🏅 Certifications |
|---|---|
| **BS Computer Science**<br/>University of Management and Technology (UMT), Lahore<br/>*Expected 2027*<br/>Relevant coursework: Cloud Computing, Operating Systems, Computer Networks | **Mastercard Cybersecurity Virtual Experience Program**<br/>Forage<br/><br/>**Introduction to Cybersecurity**<br/>Cisco Networking Academy |

<br/>

## 📊 `[06_telemetry]` GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Hunain-Amin&show_icons=true&theme=dark&hide_border=true&bg_color=08090f&title_color=00E5FF&icon_color=39ff88&text_color=e8edf7&ring_color=ff2fb0" width="49%" alt="GitHub Stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Hunain-Amin&theme=dark&hide_border=true&background=08090f&stroke=1e2536&ring=39ff88&fire=ff2fb0&currStreakLabel=00E5FF" width="49%" alt="GitHub Streak" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hunain-Amin&layout=compact&theme=dark&hide_border=true&bg_color=08090f&title_color=ff2fb0&text_color=e8edf7" width="40%" alt="Top Languages" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=Hunain-Amin&theme=radical&no-frame=true&no-bg=true&margin-w=8&column=4" width="80%" alt="Trophies"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hunain-Amin/Hunain-Amin/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Hunain-Amin/Hunain-Amin/output/github-contribution-grid-snake.svg">
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/Hunain-Amin/Hunain-Amin/output/github-contribution-grid-snake.svg">
</picture>

<sub>⚠️ this animates once the GitHub Action snake workflow is set up to output to the "output" branch</sub>

</div>

<br/>

## 📡 `[07_connect]` Let's talk security.

<div align="center">

Open to expanding my cybersecurity experience and connecting on security operations. Reach out — I respond fast.

[![Email](https://img.shields.io/badge/-%24_email-00E5FF?style=for-the-badge&logo=gmail&logoColor=black)](mailto:p.hunainamin@gmail.com)
[![GitHub](https://img.shields.io/badge/-%24_github-0e111a?style=for-the-badge&logo=github&logoColor=39ff88)](https://github.com/Hunain-Amin)
[![Portfolio](https://img.shields.io/badge/-%24_portfolio-0e111a?style=for-the-badge&logo=githubpages&logoColor=ff2fb0)](https://hunain-amin.github.io)
[![LinkedIn](https://img.shields.io/badge/-%24_linkedin-0e111a?style=for-the-badge&logo=linkedin&logoColor=00E5FF)](https://linkedin.com/in/Hunain-Amin)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff2fb0,50:0e111a,100:08090f&height=100&section=footer" width="100%"/>

`🟢 connection secure — built by Hunain Amin`

</div>
