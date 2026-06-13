# SIEM Security Monitoring & Incident Response Lab (Wazuh)

>  SOC Incident Simulation: SIEM Monitoring, Brute Force Detection, and Automated Response (Wazuh + Fail2Ban)

---

## Environment Setup (SIEM Monitoring)

<img src="screenshots/Wazuh_Active.png" width="800" alt="Wazuh dashboard showing active SIEM monitoring"/>

The SIEM environment was configured using Wazuh to collect and monitor logs from connected endpoints.

---

## Monitored Endpoint

<img src="screenshots/Wazuh_Agents.png" width="800" alt="Playserver showing active Wazuh agent connection"/>

The target system ("playserver") was successfully integrated into the SIEM environment as a monitored agent.

---

## Attack Simulation (Brute Force)

<img src="screenshots/Hydra_Correct.png" width="800" alt="Hydra brute force attack showing successful login attempts"/>

A brute force attack was simulated using Hydra to generate repeated authentication attempts against the target system.

---

## Detection (Log Analysis & SIEM Alerts)

<img src="screenshots/Wazuh_brute_force.png" width="800" alt="Wazuh SIEM alert showing brute force detection activity"/>

---

## Response (Fail2Ban Mitigation)

<img src="screenshots/Fail2ban_status.png" width="800" alt="Fail2Ban status showing active jail configuration and protection rules"/>

Fail2Ban was configured to monitor authentication failures and enforce automated blocking rules.

<img src="screenshots/Fail2ban_jail.png" width="800" alt="Fail2Ban jail showing malicious IP blocked after repeated failed login attempts"/>

The attacking IP was successfully blocked after repeated failed authentication attempts.

<img src="screenshots/Wazuh_Block_hydra.png" width="800" alt="Wazuh dashboard showing failed login attempts from Hydra brute force activity"/>

---

## Security Outcome

This project demonstrates a full Security Operations Center (SOC) workflow:

- SIEM deployment and configuration (Wazuh)
- Endpoint monitoring and log collection
- Attack simulation (Hydra brute force)
- Detection through log analysis and alerting
- Automated response and mitigation (Fail2Ban)

---

## Outcome
This project reinforced core SOC analyst skills including monitoring security events, interpreting SIEM alerts, and following structured investigation workflows in a simulated enterprise environment.
