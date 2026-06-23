# SOC Alert Investigation: Brute Force Login Detection

## Environment

Type:
Training / Simulated Lab Exercise

Purpose:
To practice SOC alert triage, suspicious activity analysis, and security reporting.

---

## Project Overview

This project simulates a Security Operations Center (SOC) investigation involving repeated failed authentication attempts.

The objective was to analyze suspicious login activity, identify indicators of a potential brute-force attack, and recommend mitigation actions.

---

# Scenario

A security monitoring system generated an alert for multiple failed login attempts against a user account.

This project simulates a SOC analyst investigation workflow.

---

# Alert Information

Alert Type:
Multiple Failed Login Attempts

Category:
Authentication Attack / Possible Brute Force

Severity:
Medium

Affected Asset:
User authentication system

---

# Investigation Process

## 1. Reviewed Authentication Events

The authentication logs were reviewed to identify:

- Failed login attempts
- Source IP addresses
- Login timestamps
- Target usernames
- Login frequency

---

## 2. Identified Suspicious Patterns

Observed indicators:

- Multiple failed login attempts within a short timeframe
- Repeated access attempts against the same account
- Unusual login behaviour compared to normal activity

---

# Analysis

The activity pattern was consistent with a possible brute-force attack where an attacker attempts multiple password combinations to gain unauthorized access.

Further investigation would include:

- Checking IP reputation
- Reviewing successful login events
- Correlating events with other security alerts

---

# Recommended Response Actions

Immediate actions:

- Temporarily lock suspicious accounts if required
- Reset compromised credentials
- Enable Multi-Factor Authentication (MFA)

Preventive measures:

- Implement account lockout policies
- Monitor authentication logs continuously
- Configure SIEM correlation rules for repeated failures

---

# Tools and Concepts Applied

Concepts:

- Incident response
- Log analysis
- Threat detection
- Security monitoring

Tools:

- SIEM concepts
- Authentication logs
- Security event analysis

---

# Skills Demonstrated

- SOC alert triage
- Incident documentation
- Threat investigation
- Security reporting

---

# Lessons Learned

This exercise improved my understanding of how SOC analysts investigate alerts, analyze suspicious activity, and communicate security findings.

---

## Evidence

Screenshots and supporting evidence will be added from authorized training lab environments.
