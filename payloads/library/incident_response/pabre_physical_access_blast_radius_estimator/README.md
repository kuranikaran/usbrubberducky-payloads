# Physical Access Blast Radius Estimator (PABRE)

PABRE is a **non-weaponized USB Rubber Ducky payload** that estimates the potential
impact of brief physical HID access to a macOS endpoint.

It performs a **read-only assessment** of execution context and privilege exposure
to estimate theoretical impact, without exploiting the system.

---

## Functionality

- Detects OS and active user context
- Checks local administrator group membership
- Detects Active Directory binding (if present)
- Estimates blast radius:
  - LOCAL ONLY
  - TEAM / SHARED
  - ORGANIZATION-WIDE
- Writes a local assessment report to the desktop

---

## Out of Scope

- No exploitation
- No credential access
- No persistence mechanisms
- No malware deployment
- No network communication

---

## Output


~/Desktop/PABRE_Report/PABRE_Report.txt


---

## Platform

- macOS

---

## Use Cases

- Incident response preparation
- Physical access risk assessment
- Red team scoping
- Defensive validation

---

## Disclaimer

For authorized testing and educational use only.
