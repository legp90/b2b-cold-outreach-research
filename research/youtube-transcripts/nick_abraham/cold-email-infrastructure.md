# Video: Cold Email Infrastructure Setup Guide

**Expert:** Nick Abraham (Founder of Scrubby & InboundVids)  
**Source URL:** https://www.youtube.com/watch?v=8i2p_S5S6f4  

## Core Insights & Transcript Breakdown

### 1. Domain Setup and Spreading Risk
* Do not use your primary company domain for cold outreach. If it gets flagged for spam, your corporate emails will fail.
* Buy alternative domains (e.g., if your company is `company.com`, buy `getcompany.com` or `companyb2b.com`).
* Limit to a maximum of 2 to 3 email accounts per domain to isolate risk.

### 2. DNS Configuration (The Technical Pillars)
* **SPF (Sender Policy Framework):** Specifies which mail servers are authorized to send email on behalf of your domain.
* **DKIM (DomainKeys Identified Mail):** Adds a digital signature to emails, ensuring the content wasn't tampered with in transit.
* **DMARC (Domain-based Message Authentication, Reporting, and Conformance):** Uses SPF and DKIM to determine the authenticity of an email message. Set the policy to `p=quarantine` or `p=reject` once stable.

### 3. The Warmup Process
* Never send emails from a brand-new domain immediately.
* Use automated warmup tools (like Instantly or Smartleads) for at least 14 to 21 days before launching campaigns.
* Gradually ramp up sending volume: start with 5 emails per day, increasing slowly until reaching a safe cap of 30 to 35 cold emails per account daily.