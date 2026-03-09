# Project 02: NIST CSF Gap Analysis

**Framework:** NIST Cybersecurity Framework 2.0  
**Case Study:** Change Healthcare Breach (February 2024)  
**Analysis Basis:** Publicly available information (congressional testimony,
SEC filings, CISA advisories, industry reporting)  
**Effort:** ~22 hours

---

## What This Project Is

A retrospective gap analysis of the 2024 Change Healthcare ransomware attack
mapped against NIST CSF 2.0. The analysis covers all six functional areas:
Govern, Identify, Protect, Detect, Respond, and Recover.

Deliverables include:
- Maturity tier scoring (Pre-breach estimated vs. Target state)
- 8 detailed control gaps mapped to specific NIST CSF 2.0 subcategories
- Three-phase remediation roadmap (0-90 days, 90-180 days, 180-365 days)
- Executive lessons learned section written for a non-technical audience

## Why I Built It

I chose the Change Healthcare breach because the root cause — no MFA on a
remote access portal — illustrates the gap between compliance theater and
genuine risk reduction. The contrast between a catastrophic outcome and an
elementary control failure is exactly what GRC analysis should surface.

> Note: All analysis is based on publicly available information.
> This is an educational portfolio project and does not represent an
> official assessment of Change Healthcare or UnitedHealth Group.

## Frameworks & Standards Referenced
- NIST Cybersecurity Framework 2.0 (2024)
- CISA Secure by Design Principles
- CIS Critical Security Controls v8

## Files in This Folder

| File | Description |
|------|-------------|
| `NIST_CSF_Gap_Analysis.pdf` | Full gap analysis with maturity scoring and roadmap |
| `Analyst_Note_NIST.pdf` | Project context, methodology decisions, and accounting angle |

