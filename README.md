#  Mock Trial Master File — Phase III Breast Cancer Trial (NCT01275677)
### TMF Construction & Inspection-Readiness Assessment | CDISC TMF Reference Model v3.2

##  Overview

This project simulates the construction and inspection-readiness assessment of a **Trial Master File (TMF)** for a completed Phase III clinical trial, using the **CDISC TMF Reference Model v3.2** as the filing framework.

Built as an academic portfolio exercise to demonstrate practical knowledge of:
- TMF structure and the Zone/Section/Artifact hierarchy
- ICH E6(R2) Section 8 essential document requirements
- GCP documentation principles and inspection-readiness thinking
- The difference between sponsor-level and site-level TMF content

**No proprietary or confidential data was used. All assessments are based solely on publicly available sources.**

##  Trial Background

| Field | Detail |
|---|---|
| **Trial Name** | NSABP B-47 / NRG Oncology Phase III Adjuvant Breast Cancer Trial |
| **NCT Number** | [NCT01275677](https://clinicaltrials.gov/study/NCT01275677) |
| **Sponsor** | National Cancer Institute (NCI) — IND #113988 |
| **Lead Group** | NRG Oncology (formerly NSABP) |
| **Phase** | Phase III — Randomized, Open-Label, Multi-Center |
| **Indication** | High-risk invasive breast cancer (HER2-low: IHC 1+ or 2+, non-amplified by FISH) |
| **Intervention** | Adjuvant chemotherapy ± Trastuzumab (1 year) |
| **Primary Endpoint** | Invasive Disease-Free Survival (IDFS) |
| **Enrolment** | 3,270 patients across ~300 NCTN sites (US, Canada, Ireland, Australia) |
| **Activation** | January 2011 |
| **Outcome** | **Negative trial** — Trastuzumab did not improve IDFS in HER2-low population |
| **Publication** | Rastogi et al., *J Clin Oncol* 2020;38(5):444–453. [DOI: 10.1200/JCO.19.01455](https://doi.org/10.1200/JCO.19.01455) |

##  What's in the TMF Index

The Excel workbook (`NSABP_B47_Mock_TMF.xlsx`) contains three sheets:

### 1. Cover Page
Trial identity card with all key metadata, status legend, and methodology notes.

### 2. TMF Index
Full artifact mapping across all **11 CDISC TMF RM zones**:

| Zone | Name |
|---|---|
| Zone 01 | Trial Management |
| Zone 02 | Central Trial Documents |
| Zone 03 | Regulatory |
| Zone 04 | IRB/IEC and Other Approvals |
| Zone 05 | Site Management |
| Zone 06 | Investigational Product and Trial Supplies |
| Zone 07 | Safety Reporting |
| Zone 08 | Central and Local Testing |
| Zone 09 | Third Parties |
| Zone 10 | Data Management |
| Zone 11 | Statistics |

Each artifact is assessed with:
- **Artifact number and name** (per CDISC TMF RM v3.2)
- **Core vs. Recommended** classification
- **Filing level** (Trial / Country / Site)
- **Sponsor vs. Investigator** accountability
- **Source document** with public citation where available
- **Status** (see below)

### 3. Completeness Tracker
Every core artifact assessed against ICH E6(R2) Section 8, with inspection-readiness notes and auto-calculated summary counts.

##  Key Findings

**5 artifacts were fully available from public sources**, including:
-  Full protocol and Statistical Analysis Plan (published at ClinicalTrials.gov)
-  Trial registration (NCT01275677)
-  Cardiac safety monitoring protocol (embedded in B-47 protocol document)
-  HER2 testing reference ranges (defined in eligibility criteria)

**The largest inspection gap category is site-level documentation**, which is consistent with real-world TMF vulnerabilities in multi-site trials. Artifacts not recoverable from public sources include:
-  Delegation of Authority Logs (~300 sites)
-  Investigator CVs and medical licensure
-  IRB-stamped Informed Consent Forms (site-specific versions)
-  Monitoring visit reports
-  Signed protocol signature pages

**One artifact was marked Not Applicable:**
-  IP Randomization / Unblinding Procedures — B-47 is an open-label trial; no IP blinding was used

**Notable design feature:** B-47 used the **NCI Central IRB (CIRB)** rather than individual site IRBs — a detail relevant to Zone 04 artifact assessment and a real-world example of centralized IRB oversight.

##  Regulatory Framework

| Standard | Application |
|---|---|
| **CDISC TMF Reference Model v3.2** | Filing structure — all 11 zones, section and artifact hierarchy |
| **ICH E6(R2) Section 8** | Essential document requirements — Core artifact identification |
| **21 CFR Part 312** | IND regulations — regulatory submission and safety reporting artifacts |
| **21 CFR Part 56** | IRB regulations — Zone 04 artifact requirements |
| **FDA Guidance on TMF** | Inspection-readiness assessment criteria |

##  Limitations

This project demonstrates **structural knowledge** of TMF requirements, not access to an operational TMF.

- All assessments are based solely on publicly available sources
- A real TMF for this trial would contain hundreds of site-level documents not accessible here
- **INFERRED** status indicates the artifact is known to exist based on regulatory requirement or published reference, but the document itself was not publicly available
- This is an academic simulation — it should not be interpreted as a compliance assessment of the actual NSABP B-47 trial

## Data Sources

| Source | Link |
|---|---|
| ClinicalTrials.gov record | [NCT01275677](https://clinicaltrials.gov/study/NCT01275677) |
| Full protocol and SAP (PDF) | [ClinicalTrials.gov document](https://cdn.clinicaltrials.gov/large-docs/77/NCT01275677/Prot_SAP_000.pdf) |
| Primary results paper | [Rastogi et al., JCO 2020](https://doi.org/10.1200/JCO.19.01455) |
| CDISC TMF Reference Model | [tmfrefmodel.com](https://tmfrefmodel.com/) |
| NCI CIRB | [ncicirb.org](https://ncicirb.org) |

##  Tools Used

- **Microsoft Excel / Google Sheets** — TMF index and completeness tracker
- **CDISC TMF Reference Model v3.2 Excel Workbook** — artifact reference
- **ClinicalTrials.gov API** — trial data retrieval

##  Author

**[Nick Iver Majaw]**  
**[Pharm-D]**
Academic TMF Portfolio Project — June 2026  
*Aspiring Clinical Research / CRO Professional*

*This project was built to demonstrate TMF knowledge for entry-level clinical trials roles. Feedback welcome.*
