# TLD Reputation Data

This repository contains per-TLD reputation metrics derived from domain categorization data from Palo Alto Networks. We report the malicious ratio, malicious-to-benign ratio, and non-benign ratio for all TLDs with at least 1,000 domains, beginning from June 2021.

Each TLD is labeled with its generation based on when it was introduced: **Legacy** (before 2012), **First Wave** (2012--2015), **Second Wave** (2016--2020), **Third Wave** (2021--2025), **Fourth Wave** (2026--onwards), or **ccTLD** (country-code TLDs). This generational classification follows ICANN's New gTLD Program, which began in 2012 and represents the most significant expansion of the DNS namespace to date.

## Our Research
This data accompanies our study on the impact of the expanding gTLD namespace on the DNS ecosystem. Our analysis shows that newer generations of gTLDs are increasingly used for malicious purposes: first, second, and third wave gTLDs are 2.3, 2.7, and 4.2 times more malicious than legacy gTLDs, respectively. We will continue to update this repository periodically with new data.

Research Papers:
- [Not What It Used To Be: Generational Analysis of Top-level Domain Reputation](https://dx.doi.org/10.14722/madweb.2026.23030).
Janos Szurdi, Reethika Ramesh, Ram Sundara Raman, Daiping Liu.
To appear at **MADWeb 2026** (Workshop on Measurements, Attacks, and Defenses for the Web, co-located with NDSS 2026)
## Data Files

- [2021-06-15](20210615_tld_rep.md)
- [2022-01-20](20220120_tld_rep.md)
- [2022-06-16](20220616_tld_rep.md)
- [2023-02-16](20230216_tld_rep.md)
- [2023-04-06](20230406_tld_rep.md)
- [2024-10-17](20241017_tld_rep.md)
- [2025-02-27](20250227_tld_rep.md)
- [2025-09-06](20250906_tld_rep.md)
- [2025-11-30](20251130_tld_rep.md)
- [2026-02-03](20260203_tld_rep.md)

## Definitions

| Metric | Definition |
| --- | --- |
| Malicious Ratio | malicious / total |
| Malicious-to-Benign Ratio | malicious / benign |
| Non-Benign Ratio | (malicious + low-content) / total|
