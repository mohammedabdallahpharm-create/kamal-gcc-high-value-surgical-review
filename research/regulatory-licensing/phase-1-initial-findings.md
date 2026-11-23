# Regulatory & Licensing Intelligence — Initial Findings

**Research date:** 23 November 2026  
**Status:** Initial source-backed scan; not a legal opinion  
**Scope:** UAE federal framework, Dubai, and Abu Dhabi. Other emirates remain to be mapped.

## Executive finding

The proposed Kamal GCC service model must not be treated as one undifferentiated activity. The regulatory perimeter changes depending on whether the entity:

1. provides a clinical second opinion;
2. administers health-insurance claims or delegated payer functions;
3. coordinates cases and documents without making clinical or insurance decisions; or
4. supplies technology or analytical support to a licensed entity.

The strongest verified finding is that Dubai’s DHA Telehealth Standard Version 4 expressly recognises virtual second opinions for complex or specialist cases. It limits these to advisory consultations by DHA-licensed specialists/consultants, without prescriptions or medical orders, and leaves clinical responsibility with the treating physician. The standard became effective 26 November 2025. [REG-UAE-001]

Abu Dhabi separately requires authorisation for entities administering health-insurance policies, and its health-insurance legislation defines a TPA as a company licensed to administer insurance claims. [REG-UAE-005, REG-UAE-006]

**No conclusion is yet made that a new standalone company can lawfully perform both functions under one licence.**

## 1. Regulatory map

| Layer | Authority / instrument | What it governs | Research status |
|---|---|---|---|
| Federal health data | Federal Law No. 2 of 2019 | Health information, confidentiality, access, cross-border processing/storage, retention | Inspected |
| Federal health data implementation | Cabinet Resolution No. 32 of 2020 | Executive controls under the ICT health law | Identified; full review pending |
| Federal TPA regulation | CBUAE TPA instructions | TPA licensing and business conduct | 2026 page identified; downloadable instrument not yet inspected |
| Legacy TPA rules | IA Board Resolution 9/2011, consolidated amendments through 2020 | TPA staffing, agreements, claims, independence, conduct | Inspected as legacy rules; current applicability pending reconciliation |
| Dubai clinical service | DHA Telehealth Standard Version 4 | Telehealth and virtual second opinions | Inspected |
| Dubai healthcare licensing | Dubai Administrative Resolution 25/2025 and licensing manuals | Healthcare facility and professional activity licensing | Identified; activity-level review pending |
| Dubai health insurance | DHA Health Insurance Permit services | Permits for insurers, brokers, TPAs and providers | Identified; TPA checklist pending |
| Abu Dhabi health insurance | DoH Book 2 Health Insurance Legislation | Insurer, TPA and provider participation | Inspected |
| Abu Dhabi authorisation | DoH participation manual, Chapter IV | Certificate of Authorisation for insurers, brokers and TPAs | Inspected; latest revision pending |
| Abu Dhabi contracting | DoH Circular 180/2024 / Standard Provider Contract | Payer-provider contractual framework | Circular inspected; contract text pending |
| Medical liability | Federal Medical Liability Law and 2023 amendment | Professional and institutional liability | Amendment identified; consolidated review pending |

## 2. Dubai: virtual second opinion is a recognised regulated service

DHA Telehealth Standard Version 4:

- Issue date: 26 September 2025.
- Effective date: 26 November 2025.
- Code: DHA/HRS/HPSD/ST-14.
- Review date: 26 September 2030.

The standard describes virtual second opinions as advisory consultations for complex or specialist medical cases through telehealth. It identifies three models:

1. Treating physician requests a second opinion from a DHA-licensed specialist.
2. Treating physician and patient jointly consult a DHA-licensed specialist.
3. Patient directly requests a second opinion.

Core controls:

- Secure upload of relevant records through DHA-approved encrypted platforms.
- Detailed advisory report based on the information reviewed.
- Treating physician retains full clinical responsibility and treatment decisions.
- Patient consent and the report must state that the consultation is advisory only.
- The treating physician and relevant jurisdiction remain accountable for clinical management and legal responsibility.

**Implication:** A business that itself delivers clinical opinions cannot assume it is merely an administrative coordinator. The clinical service must be delivered through the appropriate DHA-licensed professional and facility arrangement. The exact facility activity/licence category still needs confirmation from DHA.

## 3. Abu Dhabi: TPA is a defined licensed activity

The DoH Health Insurance Legislation compendium defines a TPA as a company licensed to carry on insurance-claim administration in Abu Dhabi.

Article 14 provides, among other things:

- authorised insurers may contract with registered companies to administer health-insurance affairs;
- insurer and TPA are jointly liable for performance of insurer obligations;
- the TPA licence is issued by DoH under the relevant licensing requirements;
- a TPA may not own, manage or co-manage healthcare-provider facilities.

The DoH participation manual states that insurers, brokers and TPAs wishing to sell or administer health-insurance policies in Abu Dhabi must obtain a Certificate of Authorisation before doing so.

**Implication:** A company should not perform delegated claims-administration functions in Abu Dhabi on the assumption that a general commercial licence or a clinical-services arrangement is enough.

## 4. Federal health-data controls: a major design constraint

Federal Law No. 2 of 2019 applies to ICT use in healthcare across the UAE, including free zones.

Key provisions inspected:

- Article 4: confidentiality, integrity and authorised availability of health information.
- Article 13: health data related to healthcare services provided in the UAE may not be stored, processed, generated or transferred outside the UAE unless a decision by the Health Authority permits it in coordination with MOHAP.
- Article 16: patient information must remain confidential and be used for health purposes; it includes a defined exception for information requested by health insurers or health-service funders for review, approval or verification of financial entitlements.
- Article 20: health information retained through ICT must be kept for a period appropriate to need and no less than 25 years from the last health procedure.

**Implication:** The proposed case platform, document exchange, cloud hosting, AI tools, external medical reviewers and cross-border specialist network require a data-flow and hosting assessment before any real patient information is used.

Do not assume the general Personal Data Protection Law alone resolves health-data obligations. The sector-specific ICT health law and local health rules must be assessed.

## 5. TPA rules: important historical requirements, but a 2026 update must be reconciled

The CBUAE official website now identifies dedicated TPA licensing instructions and displays a last-updated date of 24 February 2026. The downloadable instrument has not yet been successfully inspected. [REG-UAE-007]

The CBUAE Rulebook also exposes the older Insurance Authority Board Resolution No. 9 of 2011, consolidated with amendments through 2020. It contains provisions on:

- corporate form and licensing;
- legacy minimum capital and professional-indemnity requirements;
- key management and staffing;
- independent licensed physician involvement in treatment-case verification;
- insurer/TPA/provider agreements;
- records, reporting, confidentiality and professional conduct.

**Critical caveat:** The older rulebook text includes AED 5 million paid-up capital and AED 3 million professional indemnity cover. These figures are recorded as legacy rule text only. They must not be used as the current 2026 entry-cost assumption until the 24 February 2026 CBUAE instructions are retrieved, read and reconciled.

## 6. Three possible operating models to test

| Model | Scope | Preliminary regulatory exposure |
|---|---|---|
| A. Clinical Second Opinion Provider | A licensed specialist issues the advisory clinical report through the proper licensed facility/service | Healthcare facility and professional licensing; telehealth controls; clinical liability; health data |
| B. Licensed TPA / delegated payer administrator | Company performs claims administration and delegated payer functions | CBUAE and relevant emirate TPA authorisation/licensing; governance, staffing, contracts and controls |
| C. Specialist Case Coordination / Review Support | Company organises records, timelines, documentation, expert referrals and administrative coordination; clinical opinion remains with a separately licensed provider and payer decision remains with insurer/TPA | Perimeter depends on actual activities, contractual authority, data access and whether any regulated clinical or claims function is performed |

These are analytical models, not confirmed licence categories. The final structure must be classified by the competent authorities and qualified UAE counsel.

## 7. Questions requiring written regulator or legal confirmation

1. Can a non-clinical company coordinate a second opinion between a payer and an independently licensed specialist without itself being licensed as a healthcare facility?
2. What exact DHA facility activity/licence is required where the company arranges the consultation and hosts the case workflow?
3. Does a specialist review commissioned by an insurer/TPA and used for medical-necessity assessment fall within TPA activity, clinical consultation, or both?
4. Can a licensed TPA subcontract independent specialist opinions, and what approval, credentialing, audit and liability clauses are required?
5. Which CBUAE TPA instructions apply after the February 2026 update, and what happened to legacy capital, insurance and staffing requirements?
6. What DoH authorisation is needed for a specialist review-support vendor operating in Abu Dhabi?
7. Which health-data hosting, retention, access, consent and cross-border rules apply to each proposed data flow?
8. How must clinical independence, conflicts of interest, and separation between clinical advice and payer coverage decisions be documented?

## 8. Next research actions

**Priority 1 — CBUAE 2026 TPA instructions:** Retrieve the actual downloadable instrument and compare it article-by-article against the 2011/2020 consolidated rulebook. No current capital estimate until complete.

**Priority 2 — DHA licensing classification:** Inspect the 2025 facility and professional licensing manuals and identify the closest activity classification for a virtual second-opinion service and a non-clinical case-coordination vendor.

**Priority 3 — DoH Abu Dhabi:** Obtain the current authorisation checklist and latest participation manual, then review the Standard Provider Contract and its amendments.

**Priority 4 — Federal data controls:** Inspect Cabinet Resolution 32/2020 and map data flows for records, imaging, AI processing, external specialists, hosting, audit and retention.

**Priority 5 — Medical liability:** Review the consolidated Medical Liability Law after Federal Decree-Law 18/2023 and identify the responsibilities of the specialist, treating physician, facility, coordinator, insurer and TPA.

## 9. Source audit

The master source register records each source, direct URL, inspection status and limitations. It distinguishes inspected primary documents from search-result-only leads and links that still require full inspection.

### Current conclusion

The regulatory landscape supports the existence of a recognised virtual second-opinion model in Dubai and a separately regulated TPA/claims-administration model in the UAE insurance system.

It does **not** yet establish that a new independent “Second Opinion TPA” can combine both functions under one licence.

The next decision should be based on the actual service boundary and the regulator's written classification — not the proposed company name.
