# SOC Incident Report – Splunk

## Incident Overview
This report documents the investigation of a simulated intrusion using Splunk in the TryHackMe “Incident Handling with Splunk” lab.  
The objective was to use Splunk’s search capabilities to identify, investigate, and analyze different stages of an attack.

---

## Task 1 – Brute Force Login Attempts
Using Splunk queries, multiple failed login attempts were detected from a single source IP.  
This indicated a brute force attempt against user accounts.

**Screenshot:**  

---

## Task 2 – Command & Control (C2) Activity
Further analysis revealed suspicious beaconing traffic consistent with C2 communications.  
Splunk queries highlighted unusual outbound connections to known malicious IP addresses.

**Screenshot:**  


---

## Task 3 – Website Defacement
Logs confirmed malicious actions where the attacker successfully altered a webpage (defacement).  
This represented the final “actions on objective” stage.

**Screenshot:**  


---

## Conclusion
The Splunk investigation successfully identified:  
- Brute force attempts leading to initial access.  
- C2 communications establishing persistence.  
- Final actions on objective with a website defacement.  

This exercise demonstrated how Splunk can be used to detect, investigate, and document cyber incidents across different stages of an attack lifecycle.

---

**Made by: Xavier Mota**

**20/08/2025**
