# AWS Cloud Practitioner — Study Journey

Living documentation of my **AWS Certified Cloud Practitioner (CLF-C02)** journey — what I'm studying, what I've studied, and what I've learned. It grows over time.


---

## Exam fast-facts

| | |
|---|---|
| **Exam code** | CLF-C02 |
| **Questions** | 65 (50 scored + 15 unscored) |
| **Time** | 90 minutes |
| **Format** | Multiple choice / multiple response |
| **Passing score** | 700 / 1000 |
| **Cost** | 100 USD |
| **Validity** | 3 years |

### The 4 exam domains (these organize my notes)

| # | Domain | Weight |
|---|--------|-------:|
| 1 | [Cloud Concepts](domains/1-cloud-concepts.md) | 24% |
| 2 | [Security and Compliance](domains/2-security-and-compliance.md) | 30% |
| 3 | [Cloud Technology and Services](domains/3-cloud-technology-and-services.md) | 34% |
| 4 | [Billing, Pricing, and Support](domains/4-billing-pricing-and-support.md) | 12% |

I study the AWS Skill Builder *Cloud Practitioner Essentials* course (13 modules), but I file lasting notes by **exam domain** because that's how the exam is weighted.

---

## How I use this

- **`daily-log/`** — one dated file per study session. This is the timeline: what I did and learned that day.
- **`domains/`** — distilled, lasting knowledge organized by the 4 exam domains. Daily insights get promoted here.
- **`progress-tracker.md`** — at-a-glance status across the 13 course modules, each tagged to its exam domain.

### Links

- 📊 [Progress tracker](progress-tracker.md)
- 📁 Domain notes: [1 Cloud Concepts](domains/1-cloud-concepts.md) · [2 Security & Compliance](domains/2-security-and-compliance.md) · [3 Cloud Technology & Services](domains/3-cloud-technology-and-services.md) · [4 Billing, Pricing & Support](domains/4-billing-pricing-and-support.md)
- 📝 [Daily-log template](daily-log/_TEMPLATE.md)

---

## Daily workflow

Start a new study day by copying the template to today's date:

```bash
cp daily-log/_TEMPLATE.md daily-log/$(date +%F).md
```

Then fill it in as you study. At the end of a session, promote anything worth keeping into the relevant `domains/` file and update `progress-tracker.md`.
