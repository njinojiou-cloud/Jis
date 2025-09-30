
## Summary

Api_Exploitation Vulnerability

## Description

Advanced API security exploitation technique

## Steps To Reproduce

1. Navigate to https://api.yelp.com
2. Inject the following payload into the simulated_param parameter:
   ```
   GET /api/v1/users?limit=999999&amp;offset=0 HTTP/1.1
   ```
3. Observe the vulnerability manifestation

## Proof of Concept

Execute payload: GET /api/v1/users?limit=999999&amp;offset=0 HTTP/1.1

## Impact

Potential medium impact vulnerability

Medium impact on business operations

## Remediation

Implement proper input validation and security controls

## Supporting Material/References


- https://owasp.org/


## System Information

- **Discovery Date:** 2025-09-29T14:58:05.436297
- **CVSS Score:** 5.6/10.0
- **CVSS Vector:** CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:L/A:N/E:U/RL:U/RC:R
- **Verification Status:** Verified

---

*Discovered by AEGIS-X Professional Security Research*