# 🛡️ Phishing Email Detection & Awareness

![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-blue)
![Future Interns](https://img.shields.io/badge/Future%20Interns-Task%202-purple)
![Focus](https://img.shields.io/badge/Focus-Phishing%20Analysis-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

This project was completed as part of **Future Interns Cyber Security Task 2**.

The objective is to examine suspicious email scenarios, identify phishing indicators, assess the possible impact, and prepare practical awareness guidance for users.

The four samples used in this project are controlled educational emails created for analysis. Their links use the reserved `.invalid` domain and are not intended to lead to real websites.

---

## 🎯 Objectives

- Analyze suspicious email content.
- Review sender addresses and domains.
- Inspect URLs and their intended purpose.
- Identify social-engineering techniques.
- Classify the potential risk of each email.
- Document the main warning signs.
- Provide practical prevention guidance.

---

## 📧 Email Scenarios

Four controlled phishing scenarios were reviewed.

| # | Scenario | Main Theme | Risk |
|---|---|---|---|
| 01 | Microsoft MFA Verification | Credential Phishing | 🔴 High |
| 02 | Bank Transaction Verification | Financial Phishing | 🔴 High |
| 03 | Payroll Profile Update | Information Theft | 🔴 High |
| 04 | Shared Compensation Document | Credential Phishing | 🔴 High |

---

## 🔍 Investigation Approach

Each email was reviewed using a simple investigation flow:

```text
Email Sample
     ↓
Sender & Subject Review
     ↓
Domain Inspection
     ↓
URL Inspection
     ↓
Phishing Indicator Analysis
     ↓
Risk Classification
     ↓
Impact & Prevention Guidance
```

### Main areas reviewed

- Sender address
- Claimed organization
- Sender domain
- Subject and message wording
- Urgency or pressure
- Requested action
- Link destination/domain
- Requests for credentials or financial information
- Unexpected document or account-related prompts

> **Header limitation:** The supplied samples contain basic `From`, `To`, and `Subject` information but do not include complete delivery headers such as `Received`, `Return-Path`, SPF, DKIM, or DMARC results. Therefore, the assessment focuses on the email content, sender/domain information, and URLs rather than making claims about mail-server authentication.

---

# 🚨 Scenario Analysis

## 01 — Microsoft MFA Verification

**Sender:** `security@microsoft-account-alert.invalid`

The message claims that an unusual sign-in was detected and asks the recipient to complete MFA verification within 24 hours.

### Indicators

- Microsoft branding/identity is implied by the sender name.
- The sender domain does not match Microsoft's normal domain.
- The message creates a 24-hour deadline.
- The recipient is asked to complete an account verification process.
- The supplied URL uses an unrelated domain.

**Risk:** 🔴 High

**Likely objective:** Credential or account-information theft.

---

## 02 — Bank Transaction Verification

**Sender:** `fraud-alert@securebank-notice.invalid`

The email reports a transaction of **INR 32,750** and asks the recipient to confirm account details immediately.

### Indicators

- Financial transaction used as the lure.
- Urgent verification request.
- Generic greeting.
- Sender domain does not identify a legitimate banking domain.
- Link directs the recipient to an unrelated verification domain.
- References sensitive information such as OTP/PIN.

**Risk:** 🔴 High

**Likely objective:** Banking credential or financial-information theft.

---

## 03 — Payroll Profile Update

**Sender:** `payroll@company-benefits-update.invalid`

The email claims that a payroll system update requires the employee to confirm payment information before a deadline.

### Indicators

- Payroll/payment information is used as the lure.
- Generic employee greeting.
- Request to review payment details.
- Deadline creates pressure to act.
- Sender domain is not tied to a verified organization.
- External link is provided for the supposed update.

**Risk:** 🔴 High

**Likely objective:** Collection of employee or financial information.

---

## 04 — Shared Compensation Document

**Sender:** `shared-file@cloud-document-alert.invalid`

The message claims that an **"Annual Compensation Review.pdf"** has been shared and asks the recipient to open a secure viewer.

### Indicators

- Unexpected document-sharing notification.
- Compensation information creates curiosity and urgency.
- Sender domain is not associated with a verified document-sharing provider.
- The recipient is encouraged to open an external link.
- The limited-availability message adds pressure.

**Risk:** 🔴 High

**Likely objective:** Redirecting the recipient to a fraudulent page or collecting account information.

---

# 📊 Risk Classification

| Level | Description |
|---|---|
| 🟢 Safe | No meaningful phishing indicators identified |
| 🟡 Suspicious | Some unusual characteristics require verification |
| 🟠 Medium | Multiple indicators suggest elevated risk |
| 🔴 High | Strong phishing indicators or potential credential/information theft |

All four samples were classified as **High Risk** because each combines multiple phishing indicators with a request to follow an external link or provide/verify sensitive information.

---

# 🛡️ Phishing Prevention

### ✅ Recommended

- Check the complete sender address, not only the display name.
- Examine the domain before trusting an email.
- Hover over links before opening them.
- Access important services through their known official website or application.
- Verify unusual requests through an independent communication channel.
- Enable Multi-Factor Authentication.
- Report suspicious messages to the IT/security team.
- Keep browsers, operating systems, and security software updated.

### ❌ Avoid

- Clicking unexpected verification links.
- Entering passwords or financial information through email links.
- Sharing OTPs, PINs, or account credentials.
- Opening unexpected files or documents.
- Allowing urgency to replace normal verification.
- Trusting an email simply because it uses a familiar company name.

---

# 🧰 Tools & Documentation

- Email file (`.eml`) inspection
- Browser-based URL/domain review
- Email header analysis concepts
- Microsoft Word / PDF
- Git and GitHub

---

# 📁 Repository Structure

```text
Phishing-Email-Detection-Awareness/
│
├── README.md
├── report/
│   └── Phishing_Detection_Awareness_Report.docx
│
└── evidence/
    ├── Phishing-email.1.eml
    ├── Phishing-email.2.eml
    ├── Phishing-email.3.eml
    └── Phishing-email.4.eml
```

---

# 📸 Evidence

The repository can contain supporting evidence for:

- Sender and domain inspection
- Suspicious URL analysis
- Identified phishing indicators
- Risk classification
- Relevant email content

Any real personal, organizational, or confidential information should be removed before publishing screenshots or samples.

---

# 🧠 Skills Demonstrated

- 📧 Phishing Email Analysis
- 🔎 Sender & Domain Investigation
- 🔗 URL Inspection
- 🧩 Social Engineering Analysis
- 🚨 Threat Identification
- 📊 Risk Classification
- 📝 Security Documentation
- 🛡️ Security Awareness

---

# 🎓 Learning Outcome

This task demonstrates a basic workflow for investigating suspicious emails from a defensive cybersecurity perspective.

The analysis focuses on questions such as:

1. Who appears to have sent the email?
2. Does the sender domain match the claimed organization?
3. What action is the recipient being pressured to take?
4. Where does the supplied link appear to lead?
5. What information could an attacker be attempting to obtain?
6. What should the recipient do instead?

---

# ⚠️ Safety Notice

This repository is intended for **cybersecurity education, phishing awareness, and defensive analysis**.

The email samples are controlled examples and use non-operational `.invalid` domains. They are not intended to deceive real users, collect credentials, or operate as real phishing infrastructure.

---

## 👤 Author

**Rahul**

Cybersecurity | Ethical Hacking | Security Analysis

---

**Future Interns — Cyber Security Internship**  
**Task 02: Phishing Email Detection & Awareness**
