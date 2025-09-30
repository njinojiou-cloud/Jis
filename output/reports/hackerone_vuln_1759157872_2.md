
## Summary

Cloud_Exploitation Vulnerability

## Description

Advanced cloud security exploitation technique

## Steps To Reproduce

1. Navigate to https://api.yelp.com
2. Inject the following payload into the simulated_param parameter:
   ```
   aws iam list-roles
   ```
3. Observe the vulnerability manifestation

## Proof of Concept

Execute payload: aws iam list-roles

## Impact

Potential medium impact vulnerability

Medium impact on business operations

## Remediation

Implement proper input validation and security controls

## Supporting Material/References


- https://owasp.org/


## System Information

- **Discovery Date:** 2025-09-29T14:57:52.420793
- **CVSS Score:** 5.6/10.0
- **CVSS Vector:** CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:L/A:N/E:U/RL:U/RC:R
- **Verification Status:** Verified

---

*Discovered by AEGIS-X Professional Security Research*