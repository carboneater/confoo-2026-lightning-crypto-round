---
layout: section
transition: none
---

# Certificate Lifetime Reduction

## Ever had an outage due to an expired Certificate?

#### (I know I did!)

---

# Max TTLs

| Date       | TTL (d) |
| ---------- | ------- |
| (Current)  | 398     |
| 2026-03-15 | 200     |
| 2027-03-15 | 100     |
| 2029-03-15 | 47      | 



<v-click>

## Rationale

- Reducing the duration of the impacts of a compromised certificate
- Driving adoption of certificate automations (eg: ACME)

</v-click>

---
layout: center
---

## 90-days corporate renewal policy?

Please Share Tips on How to Update it?

---
layout: center
---

> This is just $hrinkflation!  
> They want more money for the same service!  
> En-💩-ification!  
>  
> - Someone who probably pays for Extended Validation (EV) Certificate

---

# Paying for a certificate?

LetsEncrypt:

    - A Free CA
    - 90d or 7d certificates
    - DV only

---

# Automation

- **ACME: Automated Certificate Management Environment**
- SCEP: Simple Certificate Enrollment Protocol
- CMP: Certificate Management Protocol
- EST: Enrollment over Secure Transport