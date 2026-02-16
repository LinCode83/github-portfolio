**Lab 02:** System Audit
**Name:** [LinR]
**Date:** [02/15/2026]

## 1. System Inventory
| Component | Specification |
|-----------|---------------|
| OS | [Windwos 11 25H2] |
| RAM | 4 GB] |
| CPU | [Intel Core i7] |

## 2. Access Control
**Model Definition:**
[DAC - a security model where the resource owners decide who gets access and what permissions (read, write, delete) to grant]

**Principle of Least Privilege (PoLP):**
<<<<<<< HEAD
[I have a user account for everyday access, editing personal files and the admin account I use for changing settings, managing other accounts]

**Concrete Example:**
[my user account is a an example of PoLP, as it allows me to use but does not grant privileged access therefore protects me from malware and reduces the attack surface]

## 3. Process Analysis
**Process 1:** [explorer.exe] (PID: [4516])
*   **Risk Hypothesis:** [if it gets attacked, the desktop environment collapses, taskbar, start menu, file explorer windows etc. It also impacts performance with spiked levels of CPU and memory, freezes, crashes etc]

**Process 2:** [Antimalware Service Executable] (PID: [3120])
*   **Risk Hypothesis:** [If attacked by malware it gets hijacked or mimicked, leading to massive resources spikes, while failing to protect the system]

**Process 3:** [Windows Widgets] (PID: [Number])
*   **Risk Hypothesis:** [Compromised widgets might steal credentials, clipboard data, screen captures, which could mimic updates via browser lures that inject into processes like explorer.exe]
=======
[I have a user account for everyday acess, editing personal files an dthe admin accont I use for changing settings, managing other accounts]

**Concrete Example:**
[my user acount is a an example of PoLP, as it allows me to use but does not grant priviledged acess therefore protects me from malware and reduces the attack surface]

## 3. Process Analysis
**Process 1:** [explorer.exe] (PID: [4516])
*   **Risk Hypothesis:** [if it gets attacked, the destop environment collapses, taskbar, start menu, file explorer windows etc. It also impacts performance with spiked leveles of CPU and memory, freezes, crashes etc]

**Process 2:** [Antimalware Service Executable] (PID: [3120])
*   **Risk Hypothesis:** [If attacked by malware it gets hijaked or mimicked, leading to massive resources spikes, while failing to protect the system]

**Process 3:** [Windows Widgets] (PID: [Number])
*   **Risk Hypothesis:** [Compromised widgets might steal credentials, clipboard data, screen captures, which could mimick updates via browswer lures that inject into processes like explorer.exe]
>>>>>>> 7d3ea37c8cfbbe971796437cc001f0ca721bd4ac
