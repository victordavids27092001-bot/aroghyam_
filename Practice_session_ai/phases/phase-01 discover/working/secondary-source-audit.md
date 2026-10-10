# Secondary Research Source Audit — Working File

Access date for this audit: **2026-10-10**

This is a working acquisition log, not the final evidence review.

| Source ID | Source | Authority/type | Inspection result | Use status | Reason and limitation |
|---|---|---|---|---|---|
| SRC-TEL-001 | [Telemedicine Practice Guidelines, 25 March 2020](https://esanjeevani.mohfw.gov.in/assets/guidelines/Telemedicine_Practice_Guidelines.pdf) | Board of Governors in supersession of MCI; official professional guidance | Opened; 48-page PDF inspected | Include with current-law review | Defines appropriateness, identification, consent, evaluation, records, privacy, prescribing, platform due diligence, and emergency referral for Registered Medical Practitioners covered by the document. It is dated 2020 and must be checked against later legal/professional developments. It does not by itself establish rules for every Ayurveda or Siddha professional. |
| SRC-TEL-002 | [Lok Sabha Unstarred Question 4663, answered 20 March 2026](https://abdm.gov.in/strapicms/uploads/AU_4663_kpy_VQG_c47376a51b.pdf) | Government of India, Ministry of Health and Family Welfare; parliamentary answer | Opened; 4-page PDF inspected | Include for government-reported platform scale and structure | Reports eSanjeevani operational figures and state totals as of 16 March 2026. Administrative service counts do not prove user satisfaction, clinical effectiveness, equitable access, or demand for Arogyam. |
| SRC-DATA-001 | [NDHM Health Data Management Policy](https://abdm.gov.in/static/media/health_management_policy_bac9429a79.80f74bc3e039c00acd4f.pdf) | National Digital Health Mission policy/guidance | Opened; 21-page PDF inspected | Include as ABDM ecosystem guidance; verify current status | Describes voluntary participation, consent, federated architecture, privacy and security by design, and health-data ecosystem roles. The document says it is dynamic and read with applicable law; it is not a complete statement of Arogyam's current legal obligations. |
| SRC-NUT-001 | [ICMR–NIN Dietary Guidelines for Indians 2024](https://nin.res.in/dietaryguidelines/pdfjs/locale/DGI_2024.pdf) | ICMR–National Institute of Nutrition | Direct PDF identified; browser could not open because of file size | Pending alternate inspection; do not cite findings yet | Authoritative candidate, but the full source was not inspectable through the current browser route. |
| SRC-NFHS-001 | NFHS-5 Phase I government PDF candidate | Ministry of Health and Family Welfare | Link returned not found | Exclude until working original is opened | Search text is not sufficient for verified statistics. |
| SRC-NFHS-002 | NFHS-5 Phase II government PDF candidate | Ministry of Health and Family Welfare | Search result found; open returned an error | Exclude until working original is opened | Do not use extracted search snippets as verified national data. |
| SRC-AYUSH-001 | [AYUSH Research Portal](https://arp.ayush.gov.in/) | Ministry of AYUSH research catalogue | Direct access timed out | Pending; do not use counts or studies yet | A catalogue is not itself proof of quality or effectiveness; each included study would require appraisal. |
| SRC-NABL-001 | [NABL introduction](https://nabl-india.org/introduction/) | National Accreditation Board for Testing and Calibration Laboratories | Direct page returned access-forbidden error | Pending alternate verification | Search text indicated medical-laboratory accreditation context, but strict protocol requires an opened source before use. |

## Initial Verified Findings

### F-TEL-001 — Telemedicine requires professional judgement and platform controls

The 2020 Telemedicine Practice Guidelines address appropriateness, practitioner and patient identification, consent, patient evaluation, mode selection, records, privacy, prescribing, fees, and emergency referral. They state that emergency teleconsultation should generally be limited to first aid, life-saving measures, counselling, and referral when in-person care is available. The document also requires platforms to perform due diligence before listing a Registered Medical Practitioner and display the practitioner's name, qualification, registration number, and contact details. It states that AI/ML platforms may assist practitioners but may not independently counsel or prescribe.

**UX implication:** Arogyam's consultation flow needs visible identity and registration details, consent, channel-appropriateness decisions, records, clear emergency diversion, grievance support, and an explicit human professional responsible for counselling or prescribing.

**Limitation:** The guideline's stated RMP definition and scope are tied to the professional framework described in the document. Arogyam must separately verify the current requirements applicable to Ayurveda and Siddha practitioners rather than generalizing automatically.

### F-TEL-002 — Assisted and direct-to-user telemedicine are both established service patterns

The 20 March 2026 parliamentary answer describes eSanjeevani AB-AAM as a provider-to-provider hub-and-spoke service assisted locally by community health and frontline workers, and eSanjeevani OPD as a patient-to-provider service. It reports more than 45 crore patients served nationally as of 16 March 2026, with 1,38,504 spokes, 18,573 hubs, 776 online OPDs, and more than 2.31 lakh providers. The annexure reports 72,827,908 cumulative teleconsultations for Tamil Nadu across the two variants.

**UX implication:** Arogyam should research both self-service and assisted-digital care. The government-reported scale shows that both models are operationally possible in India, but it does not establish which model Arogyam users prefer or whether the same conditions apply to private integrative-wellness services.

**Limitation:** These are administrative cumulative counts, not a population survey or outcome evaluation. They do not measure unique users, satisfaction, clinical benefit, access quality, repeat use, or digital exclusion.

### F-DATA-001 — ABDM participation and sharing are framed around voluntariness and consent

The Health Data Management Policy describes a federated ecosystem and states that individual participation is voluntary. It says refusal to use Aadhaar should not result in denial of a health facility or service, and it defines Health Information Users as entities that request access with the data principal's consent.

**UX implication:** If Arogyam later integrates with ABDM, health services should not be made dependent on unnecessary ABHA/Aadhaar participation. Record discovery and sharing need explicit purpose, recipient, scope, duration, and revocation controls.

**Limitation:** This policy is guidance within the digital-health ecosystem and says it may be revised. Current data-protection law, implementation specifications, and formal legal advice remain necessary.

## Primary-Research Questions Created by These Findings

1. When do users prefer a direct teleconsultation, an assisted consultation, or an in-person visit?
2. Which practitioner credentials do users understand and actually check?
3. What information helps users accept an in-person referral rather than continuing an unsuitable remote consultation?
4. How do users experience consent for audio, video, text, reports, and caregiver involvement?
5. Would users understand that ABHA participation and Aadhaar use are separate from access to Arogyam's ordinary services?
6. Which users require a local facilitator because of devices, connectivity, literacy, disability, language, or trust?

## Next Acquisition Priorities

- Obtain an inspectable original NFHS-5 national and Tamil Nadu source.
- Obtain an inspectable copy of ICMR–NIN Dietary Guidelines for Indians 2024.
- Verify current Ayurveda and Siddha telemedicine/professional guidance.
- Verify current practitioner registries and registration processes.
- Verify current DPDP, health-data, location, and children's-data requirements with original sources and legal review.
- Verify NABL laboratory search and scope data through an accessible authoritative route.
- Identify representative studies on trust, health literacy, medicine commerce, report use, and rural/urban access.
