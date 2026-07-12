# Introduction to SIEM

## Room Information

**Platform:** TryHackMe  
**Category:** SOC Fundamentals  
**Status:** Completed

## Objective

This room introduced the fundamentals of Security Information and Event Management (SIEM). It explained how SIEM platforms collect, normalize, correlate, and analyze security logs from multiple systems to help security teams detect and investigate suspicious activity.

---

## Key Concepts

### What is a SIEM?

A Security Information and Event Management (SIEM) platform collects security logs from multiple devices and applications into a centralized location. By correlating events from different sources, a SIEM helps analysts detect suspicious activity that might not be visible from a single log source.

### Log Collection

A SIEM collects logs from many different sources, including:

- Firewalls
- Windows Event Logs
- Linux systems
- Active Directory
- Endpoint Detection and Response (EDR)
- Network devices
- Cloud services
- Applications

Centralizing these logs allows analysts to investigate security events more efficiently.

### Log Normalization

Different devices generate logs in different formats. A SIEM normalizes this information into a consistent format so events from multiple systems can be searched, compared, and analyzed together.

### Event Correlation

One of the primary functions of a SIEM is event correlation.

Rather than analyzing a single log entry, the SIEM identifies relationships between multiple events occurring across different systems. This helps analysts identify attack patterns that may otherwise go unnoticed.

### Alerting

SIEM platforms generate alerts when predefined rules or suspicious activity are detected.

Examples include:

- Multiple failed login attempts
- Privilege escalation
- Malware detections
- Unusual network traffic
- Impossible travel logins

Alerts help analysts prioritize investigations.

### Dashboards

SIEM dashboards provide analysts with visual representations of security events, including:

- Active alerts
- Event trends
- Authentication activity
- Network traffic
- Threat statistics

Dashboards help analysts quickly understand the overall security posture of an environment.

---

## What I Learned

After completing this room, I learned:

- The purpose of a SIEM platform.
- How logs are collected from multiple systems.
- Why log normalization is necessary.
- How event correlation helps identify potential attacks.
- How dashboards and alerts assist analysts during investigations.

---

## Skills Practiced

- SIEM fundamentals
- Log analysis
- Security monitoring
- Event correlation
- Alert investigation
- Threat detection concepts

---

## Notes

This room reinforced how important centralized logging is within a Security Operations Center (SOC). Rather than reviewing logs from individual systems, analysts can use a SIEM to search, correlate, and investigate events across an entire environment. Understanding how SIEM platforms organize and present security data provides a strong foundation for future work with platforms such as Splunk, Microsoft Sentinel, QRadar, and Elastic Security.
