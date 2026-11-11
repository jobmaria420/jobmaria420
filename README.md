<img src="https://capsule-render.vercel.app/api?type=rect&color=0:020617,60:0b3a4a,100:0e7490&height=200&section=header&text=LORAX&fontSize=64&fontColor=e6edf3&fontAlignY=42&desc=SOC%20%7C%20Blue%20Team%20%7C%20Red%20Team%20%7C%20Networking&descSize=16&descAlignY=66&descColor=22d3ee&animation=twinkling" width="100%" alt="Lorax: cybersecurity, SOC, blue team, red team, networking" />
```text
┌─ operator
│ id        Lorax
│ focus     SOC and blue team (primary), red team, networking
│ build     Python, C, offensive tooling
│ rule      authorized scope only: labs, CTFs, bug bounty
│ status    ● online
└─────────────────────────────────────────────
```

## Mission

I work the defensive side of security: detecting, investigating and responding to threats. I practice offensive techniques to learn what attacks actually look like in network traffic and logs, then turn that into better detection. Networking is the ground truth under all of it, and code is how I make the tools I need.

## Two sides, one kill chain

| Phase (MITRE ATT&CK) | Attack (red) | Defend (blue) |
|---|---|---|
| Reconnaissance | Enumeration with Nmap, ffuf, Gobuster | Spot scanning patterns in network and web logs |
| Initial Access | Web application testing with Burp Suite | Alert on exploitation attempts and anomalous requests |
| Execution | Custom tooling in Python and C | Sigma rules for suspicious process and command activity |
| Discovery | Protocol and traffic analysis with Wireshark | Correlate network events, separate noise from signal |
| **Response** | | **Triage, investigation and containment per playbook** |

<!--
UNCOMMENT THIS SECTION ONLY WHEN YOU HAVE REAL REPOS

## In production

| Repo | What it solves | Stack |
|---|---|---|
| [repo-name](https://github.com/jobmaria/repo-name) | One objective line | Sigma |
| [repo-name](https://github.com/jobmaria/repo-name) | One objective line | KQL |
| [repo-name](https://github.com/jobmaria/repo-name) | One objective line | Python |
-->

## Stack

```text
detection   Sigma · KQL · MITRE ATT&CK · Microsoft Sentinel
offensive   Burp Suite · Nmap · ffuf · Gobuster
network     TCP/IP · Wireshark · Cisco Packet Tracer
code        Python · C · C++ · Linux
```

## Contact

[LinkedIn](https://linkedin.com/in/SEU_USER) · [Email](mailto:SEU@EMAIL)
