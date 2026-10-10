# Arogyam — Business Requirements Document

## Document Control

| Field | Value |
|---|---|
| Product | Arogyam |
| Document | Business Requirements Document (BRD) |
| Primary market | India |
| Regional focus | Tamil Nadu |
| Category | Integrative wellbeing and digital health |
| Status | Research and product-definition draft |

## 1. Executive Summary

Arogyam is an Indian integrative-wellness application that will connect users with qualified Ayurveda and Siddha practitioners, evidence-based nutrition education, supervised diet plans, reviewed wellness activities and traditional remedies, accredited laboratory services, personal health records, and nearby care facilities.

The central concept is:

> **Food as medicine, Ayurveda as informed preventive and supportive care, and qualified medical guidance when treatment is needed.**

Arogyam will communicate the potential benefits, limitations, risks, and uncertainty associated with each intervention. It will not claim that food, Ayurveda, Siddha medicine, or home remedies cure disease unless high-quality clinical evidence and applicable regulatory authorization support the claim.

Recommended positioning:

> **Evidence-informed traditional wellbeing with verified professional care.**

## 2. Business Need

Users in India seeking preventive care and traditional wellness services often encounter fragmented services, inconsistent practitioner verification, exaggerated claims, unsafe self-medication, uncertain remedy quality, and confusion about when conventional or emergency medical care is necessary.

Arogyam will address these problems through a coordinated service combining:

- Verified Ayurveda and Siddha care
- Evidence-based food and nutrition education
- Professionally supervised personalized guidance
- Safe wellness activities
- Reviewed traditional and home-remedy content
- Laboratory and health-record services
- Nearby facility discovery
- Ordering prescribed Ayurveda and Siddha medicines from verified, appropriately licensed pharmacies
- Safe medicine delivery with order tracking, prescription validation where required, storage instructions, and delivery-quality controls
- Access to authenticated traditional medicinal ingredients and raw products from verified suppliers, supported by clear botanical identity, source, batch, expiry, usage, and safety information
- Product traceability and quality documentation to reduce the risk of adulteration, contamination, substitution, incorrect dosage, and unsafe self-medication
- Emergency escalation and misinformation protection

Medicine commerce must be treated as a regulated healthcare service rather than a general lifestyle marketplace. Arogyam must verify sellers and products, require a valid prescription whenever applicable, preserve pharmacist or practitioner oversight, and prevent the sale or promotion of prohibited, unverified, contaminated, endangered, or high-risk ingredients. Raw traditional products must not be described as inherently safe or as substitutes for qualified diagnosis and treatment.

## 3. Product Vision

Enable people in India to make safer, culturally relevant, and better-informed wellbeing decisions by combining traditional-health knowledge, evidence-based nutrition, verified professional care, and responsible digital-health services.

## 4. Product Principles

1. **Evidence before promotion:** Claims must match the strength and relevance of available evidence.
2. **Safety before engagement:** Emergency escalation and contraindication controls take priority over retention and revenue.
3. **Qualified human oversight:** Higher-risk or individualized health decisions require an appropriately qualified professional.
4. **Transparent uncertainty:** Limited, conflicting, or absent evidence must be clearly disclosed.
5. **Respectful integration:** Traditional knowledge must be described accurately without presenting traditional theory as established biomedical fact.
6. **Food supports care:** Diet may support health and reduce selected risks but is not a universal cure.
7. **Consent and privacy:** Users must retain meaningful control over their health information and sharing decisions.
8. **Cultural accessibility:** The experience should support regional foods, Tamil and English, local practices, and differing levels of health and digital literacy.
9. **Ethical monetization:** Revenue must not depend on unnecessary tests, supplements, consultations, or treatments.

## 5. Business Objectives

The product and research programme must determine:

1. Which user problems are valuable and appropriate to solve.
2. Which services belong in the minimum viable product.
3. Which health claims can be communicated responsibly.
4. Which features require practitioner or dietitian supervision.
5. How traditional knowledge can coexist with evidence-based medicine.
6. How users can be protected from misinformation, unsafe self-medication, and delayed treatment.
7. How “food as medicine” should appear throughout the product experience.
8. How Arogyam can differentiate itself from wellness, consultation, diagnostic, and health-record applications.

## 6. Geographic Scope

India is the primary market. Tamil Nadu receives additional focus because of Siddha practice, Tamil-language needs, regional food customs, and facility-discovery requirements.

All research and product content must state whether a finding applies to:

- India nationally
- Tamil Nadu specifically
- Another country or region
- A global population

International findings must not be generalized to Indian users without discussing their relevance and limitations.

## 7. Target Users

- Prevention-focused healthy adults
- People managing chronic conditions
- Older adults
- Women managing personal and family wellbeing
- Rural and semi-urban users
- Existing Ayurveda or Siddha care users
- People interested in traditional remedies but uncertain about safety
- Caregivers
- Users with low health literacy
- Users with limited digital literacy

Research must document each segment’s goals, behaviours, frustrations, trust concerns, accessibility and language needs, safety risks, desired features, and reasons for abandonment.

## 8. Product Pillars

1. **Understand:** Accessible, evidence-labelled health education.
2. **Nourish:** Culturally appropriate food and nutrition support.
3. **Consult:** Access to verified professionals.
4. **Practice:** Realistic daily wellness activities.
5. **Track:** Consent-based health records and progress.
6. **Locate:** Nearby trusted facilities and laboratories.
7. **Protect:** Medical escalation, contraindication, privacy, and misinformation safeguards.

## 9. Functional Requirements

### FR-01: Onboarding and Consent

The application shall:

- Explain its purpose, limitations, and safety boundaries in plain language.
- Collect only information needed for defined services.
- Obtain specific, informed, and withdrawable consent where required.
- Use separate consent for location, health records, caregiver access, and data sharing.
- Present emergency-care guidance before health questionnaires.
- Support English and Tamil for the initial Tamil Nadu release.

### FR-02: Practitioner Discovery and Verification

The application shall:

- Let users find and filter Ayurveda and Siddha practitioners.
- Display qualifications, registration details, experience, languages, consultation modes, fees, and verified locations.
- Verify credentials through an authoritative registry or documented manual process.
- Display verification status and date.
- Flag or suspend profiles whose credentials cannot be reconfirmed.

### FR-03: Consultation Booking

The application shall:

- Support online and in-person appointments.
- Support eligible video, audio, and text consultations under applicable guidance.
- Record identities, consent, appointment status, and required care documentation.
- Allow practitioners to require in-person assessment when teleconsultation is insufficient.
- Support cancellation, rescheduling, follow-up, and escalation.

### FR-04: Food and Nutrition Education

The application shall:

- Present evidence-based dietary guidance relevant to Indian users.
- Cover dietary diversity, whole grains, millets, pulses, vegetables, fruit, nuts, seeds, protein, fibre, salt, free sugar, fats, portions, and energy balance.
- Offer affordable, seasonal, regional, vegetarian, and non-vegetarian examples.
- Separate general education from individualized medical nutrition therapy.
- Route higher-risk users to a registered dietitian or qualified clinician.
- Avoid automated disease-treatment meal plans without professional review.

### FR-05: Supervised Diet Plans

The application shall:

- Allow an authorized professional to create, approve, revise, and expire personalized plans.
- Record relevant allergies, intolerances, conditions, medicines, pregnancy status, age, and kidney or liver considerations.
- Provide reliable food–medicine and herb–medicine interaction warnings where available.
- Display the responsible professional and latest review date.

### FR-06: Wellness Activities

The application shall:

- Provide reviewed movement, yoga, breathing, sleep, stress-management, and daily-routine activities.
- Identify intended users, expected supportive benefit, duration, ability level, contraindications, evidence level, and review date.
- Offer accessible alternatives for older adults and users with limited mobility.
- Restrict higher-risk activities unless screening and professional supervision are available.

### FR-07: Traditional and Home Remedies

Every remedy shall be labelled as:

- Generally low risk for healthy adults
- Requires professional advice
- Avoid in certain populations
- Insufficient evidence
- Potentially dangerous

The application shall distinguish traditional use from demonstrated clinical benefit and state ingredients, intended supportive use, evidence, limitations, contraindications, interactions, and warning signs. It shall apply specific restrictions for pregnancy, children, older adults, liver or kidney disease, and medicine use.

### FR-08: Facility Locator

The application shall:

- Locate Ayurveda and Siddha hospitals, clinics, pharmacies, practitioners, and accredited laboratories.
- Request permission before using precise location.
- Display address, contact details, directions, service type, verification source, and latest verification date.
- Let users report inaccurate or closed listings.
- Avoid unverified accreditation or government-recognition claims.

### FR-09: Laboratory-Test Booking

The application shall:

- Display laboratory accreditation or verification status.
- Provide reliable preparation instructions and test limitations.
- Avoid encouraging unnecessary testing.
- Require professional guidance where test selection needs clinical context.
- Record bookings, reports, consent, and sharing permissions.

### FR-10: Lab-Report Management

The application shall:

- Accept supported report formats.
- Protect reports during transfer and storage.
- Let users view, download, share, and request deletion subject to applicable requirements.
- Log access and sharing activity.
- Separate report organization from clinical interpretation.
- Avoid diagnosis from an uploaded report without qualified review.

### FR-11: Lab-Result Education

The application may explain common report terminology and show laboratory-provided reference ranges. It must not diagnose from isolated results, direct medication changes, or reassure users solely because a result falls within a reference range.

### FR-12: Personal Health Records and ABHA Readiness

Where ABDM integration is implemented, the application shall use consent-based record discovery, linking, viewing, and sharing. Users must know what information is requested, why it is requested, who will receive it, and for how long.

### FR-13: Caregiver Access

Users shall be able to grant, limit, review, and revoke caregiver access. Additional protections shall apply to children and users requiring supported decision-making.

### FR-14: Emergency Escalation

The application shall:

- Screen for clinically approved red-flag symptoms before offering self-care guidance.
- Direct users to emergency or urgent care when triggered.
- Stop wellness-only flows when immediate evaluation may be necessary.
- Use rules approved by qualified medical professionals and supported by authoritative clinical sources.
- Record the version and review date of escalation logic.

### FR-15: Notifications

The application shall support consent-based reminders for appointments, approved plans, follow-ups, wellness activities, report review, and expiring practitioner credentials or clinical content.

### FR-16: Evidence Labels

Health and wellness content shall use one of these labels:

- Strong clinical evidence
- Moderate clinical evidence
- Limited or preliminary evidence
- Traditional use with insufficient clinical evidence
- Evidence of no meaningful benefit
- Safety concern or insufficient safety data

Each label shall link to a plain-language definition and supporting sources.

### FR-17: Corrections and Adverse Events

Users and professionals shall be able to report inaccurate information, unsafe advice, adverse events, and practitioner concerns. Reports shall support severity triage, investigation, correction or withdrawal, notification, and audit history.

## 10. Food-as-Medicine Framework

For Arogyam, “food as medicine” means using food and nutrition to support health, prevent deficiencies, reduce selected disease risks, and complement appropriate clinical care. It does not mean that food is a universal cure or substitute for required treatment.

### 10.1 General Education Suitable for Automation

- Building a balanced Indian plate
- Increasing dietary diversity
- Choosing affordable protein sources
- General salt and added-sugar awareness
- Increasing appropriate whole grains, pulses, fruit, and vegetables
- Understanding portions and food labels
- Choosing seasonal and culturally relevant foods

### 10.2 Professional Review Required

Individual advice requires professional review for diabetes, hypertension, cardiovascular disease, kidney or liver disease, pregnancy, childhood, frailty, allergy, eating-disorder risk, multiple medicines, significant lab abnormalities, and other conditions requiring medical nutrition therapy.

### 10.3 Initial Educational Pathways

1. Building a balanced Indian plate
2. Reducing excessive salt
3. Increasing dietary diversity
4. Choosing affordable protein sources
5. Understanding added sugar and highly processed foods

Each pathway shall define learning objectives, eligible users, exclusions, behaviour goals, evidence, evaluation questions, and escalation criteria.

## 11. Evidence Requirements

### 11.1 Source Priority

1. WHO, FAO, and authoritative international health bodies
2. ICMR and ICMR–National Institute of Nutrition
3. Ministry of Health and Family Welfare
4. Ministry of AYUSH
5. CCRAS and CCRS
6. National Commission for Indian System of Medicine
7. National Health Authority and ABDM
8. FSSAI, CDSCO, and NABL
9. Government of Tamil Nadu health and Indian-medicine departments
10. Cochrane systematic reviews
11. Peer-reviewed systematic reviews and meta-analyses
12. Well-designed randomized controlled trials
13. Official registries, including CTRI
14. Large representative national surveys

Promotional clinics, supplement brands, influencers, and wellness blogs shall not be used as evidence of effectiveness. Commercial market reports may be used only for market estimates with methodology and conflicts disclosed.

### 11.2 Evidence Matrix

| Field | Required information |
|---|---|
| Intervention | Exact practice, ingredient, or programme |
| Intended outcome | What it is intended to support |
| Population | Who was studied |
| Evidence type | Systematic review, RCT, cohort, observational, preclinical, or traditional use |
| Study quality | High, moderate, low, or very low |
| Main result | Effect size and confidence interval where available |
| Limitations | Bias, sample size, duration, comparator, and generalizability |
| Safety | Adverse effects, interactions, and contraindications |
| Product implication | Educate, supervised offering, restrict, or exclude |
| Approved wording | Permitted user-facing claim |
| Prohibited wording | Claim the product must not make |
| Sources | DOI, PMID, or direct authoritative URL |

Laboratory, animal, mechanistic, or other preclinical findings must not be presented as proof of clinical effectiveness.

## 12. Safety and Clinical Governance

### 12.1 Mandatory Controls

- Emergency red-flag screening
- Referral to urgent or conventional care
- No diagnosis from a questionnaire alone
- No replacement of prescribed medicines
- No delay of vaccination, testing, or necessary treatment
- Practitioner review for higher-risk advice
- Contraindication and interaction checks where dependable data exists
- Pregnancy, paediatric, kidney, and liver safeguards
- Adverse-event reporting
- Content owners, review dates, and expiry dates
- Clear separation of education from medical advice
- Documented correction and recall procedures

### 12.2 Governance Roles

Arogyam shall appoint:

- A clinical-safety lead
- Ayurveda and Siddha reviewers
- A conventional-medicine escalation reviewer
- A registered dietitian or qualified nutrition lead
- Pharmacology or interaction-review capability
- Privacy and security owners
- A content approval and audit committee
- A serious-incident investigation owner

### 12.3 Prohibited Claims

Arogyam must not:

- Promise guaranteed prevention, reversal, detoxification, or cure.
- Present dosha, prakriti, agni, or food compatibility as scientifically proven diagnostic facts without validated evidence.
- Imply that “natural” means safe.
- Treat government recognition as proof that every intervention works.
- Treat historical use or popularity as proof of benefit or safety.
- Recommend changing prescribed treatment without an authorized clinician.
- Use fear or misinformation to sell services or products.
- Present testimonials as clinical evidence.

## 13. Regulatory and Privacy Requirements

The team shall obtain current Indian professional and legal review for:

- Telemedicine
- Practitioner registration and verification
- Advertising and health claims
- Ayurveda and Siddha medicines
- Ayurveda Aahara and food regulation
- Laboratory accreditation
- E-pharmacy, if introduced
- Consent and health-record handling
- ABDM and ABHA integration
- Digital Personal Data Protection requirements
- Precise location data
- Children’s data
- Medical-device regulation if the product performs clinical interpretation or decision support

The compliance register shall distinguish mandatory law, professional guidance, voluntary standards, and recommended product practices. Formal Indian legal advice is required before launch and after material product changes.

The application shall implement data minimization, purpose limitation, clear notices, consent withdrawal, encryption, least-privilege access, audit logs, retention rules, appropriate deletion and correction, explicit location permission, incident response, and partner security assessment. Identifiable health data must not be used for advertising profiles.

## 14. User Research Requirements

Research shall include:

- Participant screening criteria
- Semi-structured interviews
- Quantitative survey questions
- Sample sizes justified by the research objective
- Urban, semi-urban, and rural recruitment
- English and Tamil participation
- Informed consent and privacy measures
- Inclusive recruitment and bias-reduction practices
- Accessibility testing
- Testing of evidence-label and warning comprehension

Proposed research must be separated from completed research. Participant findings, quotes, and statistics must never be invented.

## 15. Competitive Research

The assessment shall cover active Indian services offering Ayurveda or Siddha consultations, nutrition guidance, telemedicine, laboratory booking, health records, facility discovery, wellness programmes, or home-remedy content.

For each competitor, record the verified URL, features, practitioner-verification method, business model, languages, coverage, safety and evidence communication, privacy approach, strengths, and opportunity gaps. Do not state pricing, user counts, partnerships, or features without verification.

## 16. Feature Priority

| Feature | Proposed priority | Rationale |
|---|---|---|
| Verified practitioner profiles | MVP | Foundation of trust and consultation safety |
| Consultation search and booking | MVP | Core service |
| Eligible video/audio/text consultation | MVP | Improves access with professional judgement |
| Evidence-labelled education | MVP | Essential to responsible positioning |
| General food education | MVP | Central concept with manageable risk |
| Emergency escalation | MVP | Mandatory safety layer |
| Consent and privacy controls | MVP | Required for sensitive information |
| English and Tamil | MVP for Tamil Nadu | Regional accessibility |
| Facility locator | MVP or staged MVP | Supports nearby care discovery |
| Supervised diet plans | Second release or pilot | Requires professional governance |
| Wellness library | Curated MVP or second release | Requires review and contraindication controls |
| Lab-report upload | Second release | Requires strong security and governance |
| Lab-test booking | Second release | Requires accredited partners and anti-overuse controls |
| Caregiver access | Second release | Requires detailed permissions |
| Personal health-record integration | Second release | Depends on interoperability readiness |
| Herb–drug interaction warnings | Later validated pilot | High-consequence knowledge requirement |
| Automated lab interpretation | Restrict; later validation | Risk of false diagnosis or reassurance |
| Automated disease-treatment plans | Exclude without professional review | Unacceptable clinical risk |

## 17. Experience and Content Strategy

### Core Value Proposition

> Make informed everyday wellbeing choices, learn how food supports health, and connect with verified care when you need it.

Trust indicators shall include verified credentials, verification dates, evidence labels, named reviewer roles, limitations, contraindications, clear data-use notices, sponsorship disclosure, and correction tools.

The design should feel calm, credible, contemporary, culturally rooted, and accessible. It should avoid mystical symbolism, miracle language, fear-based imagery, or cues implying guaranteed healing.

Core journeys shall cover onboarding, practitioner discovery, consultation, food education, supervised plans, wellness activities, remedy review, laboratory services, facility discovery, emergency escalation, and error or adverse-event reporting.

## 18. Business Model

Possible revenue sources include:

- Consultation commission
- User subscriptions
- Employer wellness programmes
- Clinic software partnerships
- Accredited laboratory partnerships

Commercial relationships must be disclosed and must not influence clinical recommendations. The business must not encourage unnecessary tests, supplements, consultations, or treatments.

## 19. Measurement Framework

### Product Metrics

- Onboarding completion
- Practitioner-profile views
- Search-to-booking conversion
- Consultation completion
- Follow-up adherence
- Education completion
- Wellness participation
- Successful facility discovery

### Trust and Comprehension Metrics

- Understanding of evidence labels
- Understanding of education versus medical advice
- Practitioner trust
- Misinformation reports
- Content-correction time
- User trust and satisfaction

### Safety Metrics

- Red-flag detection and escalation
- Adverse events
- Contraindication warnings
- Serious safety incidents
- Clinical audit findings
- Practitioner-verification failures

### Privacy and Quality Metrics

- Unauthorized-access incidents
- Consent-withdrawal completion
- Data-request response time
- Partner-compliance issues
- Expired content awaiting review
- Facility-listing accuracy

Clinical improvement must not be claimed unless the study design, population, comparison, duration, consent, and analysis justify that conclusion.

## 20. Non-Functional Requirements

- **Accessibility:** Readable text, good contrast, screen-reader support, keyboard support where relevant, captions or transcripts, and plain-language alternatives.
- **Localization:** Professional Tamil and English localization with medical and safety review; no unreviewed machine translation.
- **Reliability:** Defined availability and recovery targets for consultation, consent, report, and emergency workflows.
- **Auditability:** Traceable changes to clinical content, evidence labels, credentials, consent, and health records.
- **Maintainability:** Owners, review schedules, version history, and expiry behaviour for evidence, regulation, safety logic, and facility information.

## 21. Anti-Hallucination Protocol

- Never invent statistics, studies, regulations, institutions, registries, or citations.
- Open and inspect every source before citing it.
- Cite original documents instead of search-result summaries.
- Cite every numerical or clinical claim inline.
- Include DOI, PMID, or direct authoritative URL where available.
- Record publication and access dates.
- Exclude sources that cannot be verified.
- Present conflicting reliable sources and explain the difference.
- Mark missing evidence as “not established” or “unable to verify.”
- Do not convert association into causation.
- Do not treat lack of reported harm as proof of safety.
- Separate facts, expert interpretation, and product recommendations.
- Maintain a complete bibliography and evidence-audit table.

## 22. Twelve-Month Roadmap

### Months 1–2: Discovery and Governance

- Establish clinical, nutrition, legal, privacy, and evidence-governance roles.
- Conduct desk research, evidence review, and competitive analysis.
- Recruit representative users.
- Define safety architecture and prohibited claims.

### Months 3–4: Concept Validation

- Test positioning, trust indicators, evidence labels, and core journeys.
- Validate English and Tamil comprehension.
- Confirm practitioner and facility data sources.
- Finalize MVP scope and compliance register.

### Months 5–7: MVP Development

- Build onboarding, consent, practitioner discovery, booking, education, food pathways, facility discovery, and emergency escalation.
- Establish content review and audit workflows.
- Complete partner due diligence.

### Months 8–9: Controlled Pilot

- Pilot with a restricted user and practitioner cohort.
- Audit consultation quality, escalation, accessibility, comprehension, security, and support.
- Resolve critical safety and usability problems.

### Months 10–12: Regional Launch and Evaluation

- Launch in a selected Tamil Nadu geography.
- Monitor trust, safety, privacy, conversion, and service quality.
- Evaluate supervised diets, laboratory services, caregiver access, and health-record integration for the next release.

## 23. Key Risks

- Unsupported or exaggerated health claims
- Unsafe self-treatment or delayed conventional care
- Incorrect practitioner or facility credentials
- Herb–drug interactions and contaminated products
- Misinterpretation of laboratory results
- Sensitive-data privacy or security incidents
- Regulatory change
- Biased or incomplete evidence
- Inaccurate medical translation
- Commercial conflicts of interest
- Connectivity and digital-literacy barriers
- Users mistaking education for personalized medical advice

## 24. MVP Acceptance Criteria

The MVP is ready for controlled release only when:

1. Every practitioner has a documented verification status and date.
2. Every health-content item has an owner, evidence label, source, safety review, and expiry date.
3. Emergency rules have documented clinical approval.
4. Consent, privacy, access controls, and logging have passed review.
5. English and Tamil safety wording has passed comprehension testing.
6. Education is clearly separated from medical advice.
7. No prohibited health claim appears in the product or marketing.
8. Users can report inaccurate content, adverse events, and credential concerns.
9. Consultation workflows meet applicable legal and professional requirements.
10. The serious-incident process has been tested.

## 25. Required Research Deliverables

1. Executive summary
2. Product background and problem statement
3. Indian healthcare and nutrition context
4. Ayurveda and Siddha evidence review
5. Food-as-medicine research
6. User segments and unmet needs
7. Competitive analysis
8. Feature-priority matrix
9. Safety and clinical-governance framework
10. Regulation and privacy checklist
11. UX and content recommendations
12. Final Arogyam product concept
13. MVP recommendation
14. Twelve-month research and product roadmap
15. Risks, assumptions, and unanswered questions
16. Evidence-audit table
17. Full bibliography with working links

The research report shall conclude with ten strongest verified insights, ten claims Arogyam must avoid, ten priority user-research questions, ten MVP features, and ten clinical or operational safeguards.

## 26. Initial Authoritative Sources

These are starting points; each study and current requirement still requires individual evaluation.

1. [WHO Global Traditional Medicine Strategy 2025–2034](https://www.who.int/publications/i/item/9789240113176)
2. [ICMR–NIN Dietary Guidelines for Indians 2024](https://nin.res.in/dietaryguidelines/pdfjs/locale/DGI_2024.pdf)
3. [WHO Healthy Diet Guidance](https://www.who.int/en/news-room/fact-sheets/detail/healthy-diet)
4. [AYUSH Research Portal](https://arp.ayush.gov.in/)
5. [ICMR Integrative Medicine Ethics Addendum](https://www.icmr.gov.in/icmrobject/uploads/Guidelines/1740984016_icmraddendumethicalrequirementsforresearchinintegrativemedicine.pdf)
6. [Indian Telemedicine Practice Guidelines](https://esanjeevani.mohfw.gov.in/assets/guidelines/Telemedicine_Practice_Guidelines.pdf)
7. [ABDM Health Data Management Policy](https://abdm.gov.in/static/media/health_management_policy_bac9429a79.80f74bc3e039c00acd4f.pdf)
8. [NCCIH Ayurvedic Medicine: In Depth](https://www.nccih.nih.gov/health/ayurvedic-medicine-in-depth)

## 27. Final Product Position

Arogyam will be a trustworthy bridge between culturally familiar wellbeing practices and responsible modern healthcare. It will help users understand potential benefits, limitations, and risks; improve access to verified professionals; make everyday nutrition practical; and direct users to appropriate medical care when self-care is not enough.

Arogyam will not be marketed as a source of “natural cures for every disease.”
