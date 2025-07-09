# 📦 Daily Newly Registered Domains – Full Dataset

This repository provides full daily datasets of newly registered domain names, maintained and published by [ABTdomain.com](https://abtdomain.com) — a domain intelligence platform for professionals, investors, and researchers.

Each file contains **all domain names registered on a specific day**, including their top-level domain (TLD), registration date, and expiration date.

---
## 📚 Data Source
The dataset is generated from daily zone files, DNS records, and non-personal WHOIS metadata (such as registration and expiration dates).
No private registrant data is included. We fully respect ICANN and GDPR data protection rules.

ABTdomain combines zone monitoring with registry-level WHOIS timestamps to ensure accurate tracking of domain creation and expiration activity.

---
### 📄 Dataset Format

Each CSV file is named in the format:
/YYYY-MM/newly-YYYY-MM-DD.csv


#### ✅ Columns

| Column Name       | Description                                  |
|-------------------|----------------------------------------------|
| `domain`          | Full domain name (e.g., `coolproject.com`)   |
| `suffix`          | Top-level domain (TLD), e.g., `com`, `ai`    |
| `registration_date` | Date the domain was registered (YYYY-MM-DD) |
| `expiration_date`   | Date the domain is set to expire (YYYY-MM-DD) |

---

## 🔍 Example

```csv
domain,suffix,registration_date,expiration_date
quantumcloud.ai,ai,2025-07-09,2026-07-09
marketboost.com,com,2025-07-09,2026-07-09
nextech.xyz,xyz,2025-07-09,2026-07-09


📁 Folder Structure
Each month has its own folder:


/2025-07/
    newly-2025-07-09.csv
    newly-2025-07-08.csv
    ...
/2025-06/
    newly-2025-06-30.csv
    ...

🔗 License & Full-Featured Platform

This dataset is provided under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. You are free to use, copy, and build upon this data, even for commercial purposes, as long as you provide attribution to ABTdomain.com.
While this dataset provides the essential "what" and "when," our full platform provides the "who," "how," and "why."

For deep insights like real-time WHOIS lookups (to find the registrar), DNS analysis, security checks, keyword-based searches, and AI-powered investment reports, please visit our professional toolset:

🔧 Free Online Tools: https://tools.abtdomain.com
👥 Members Portal: https://members.abtdomain.com



