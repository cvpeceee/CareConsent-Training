# CareConsent training: references and scope

**Reference review: 29 October 2026.** This edition is recorded from local application build **27bf584**, using invented people and a dedicated synthetic hospital/database. It replaces the earlier course as the current training edition while preserving the 27 October release. The new privacy workspace and related changes were locally qualified; they had **not been deployed to the hosted demo when recording began**. A hosted installation can therefore show fewer features. Check its actual version, role and configuration before following a chapter.

## Read before using the course

The DPDP Act and Rules have **phased commencement**. Their publication does not make every provision immediately effective. The commencement notification and Rule 1 specify separate publication, one-year and eighteen-month phases. Confirm the authoritative publication date, applicable phase and any subsequent notification before relying on a legal deadline. Existing medical, security and other applicable obligations need separate assessment during the transition.

The video demonstrates product workflows and simulated delivery. It does not establish legal approval, regulator submission, registered Consent Manager status, a qualified production deployment or hospital permission to use real patient data.

## Official primary references reviewed

| Instrument | Relevant sections / rules and purpose |
| --- | --- |
| [Digital Personal Data Protection Act, 2023](https://www.meity.gov.in/static/uploads/2024/02/Digital-Personal-Data-Protection-Act-2023-1.pdf) | Sections 5–6: notice and purpose-specific affirmative consent; section 7(f): medical emergencies; section 9: children and applicable lawful guardians; sections 11–14: patient/data-principal rights; section 2(g): the distinct registered Consent Manager role. |
| [G.S.R. 843(E): Act commencement notification, November 2025](https://www.meity.gov.in/static/uploads/2025/11/c56ceae6c383460ca69577428d36828b.pdf) | Clauses (a)–(c) set the separate commencement phases. Core processing, notice, consent and rights provisions are in the eighteen-month phase; this course does not describe every duty as already enforceable. |
| [Final DPDP Rules, 2025 — G.S.R. 846(E)](https://www.meity.gov.in/static/uploads/2025/11/53450e6e5dc0bfa85ebd78686cadad39.pdf) | Rule 1: Rules commencement; Rule 7: breach intimations and detailed report; Rule 8 and Third Schedule: specified inactivity/erasure classes; Rules 10–12 and Fourth Schedule: guardian and conditional-exemption provisions; Rule 14: rights/grievance arrangements. Use this final text, rather than the January 2025 draft. |
| [G.S.R. 892(E): December 2025 corrigendum](https://www.meity.gov.in/static/uploads/2025/12/3c7ebbae0e5456f493f486e6845df86b.pdf) | Read alongside the final Rules. Corrections include Rule 1's publication wording and other English-text references. |
| [Removal of Difficulties Order, 2026 — S.O. 5458(E)](https://www.meity.gov.in/static/uploads/2026/10/daf495a7b5798a3dfa72a944b51fc176.pdf) | Order dated 5 October, Gazette dated 6 October 2026. Clarifies section 9(1)'s guardian wording and section 10(2)(c)(ii)'s data-audit wording. It does not replace the commencement notification. |
| [CERT-In Directions of 28 April 2022](https://www.cert-in.org.in/PDF/CERT-In_Directions_70B_28.04.2022.pdf) | Paragraph (ii): specified reportable incidents within six hours of noticing or being notified; paragraph (iv): specified ICT-log obligations. Assess applicability separately. A CareConsent DPDP workflow does not complete CERT-In reporting. |

## Important distinctions in the tutorial

- **OTP:** supports a selected-purpose verification flow; it is not blanket permission, proof of age/authority or a clinical procedure signature.
- **Breach workflow:** once the relevant DPDP provisions apply, the detailed Board report has a 72-hour rule, subject to an allowed extension. Initial and affected-person intimations are without delay. The course's delivery is simulated; external reporting remains a separate hospital responsibility.
- **Retention:** the demo's 48-hour notice is a configured safeguard, **not a blanket hospital obligation under Rule 8(2)**. That subsection concerns specified inactivity classes in the Third Schedule. Medical-record retention, legal holds and other applicable requirements must be determined separately.
- **Response targets:** the demo's 30-day target is hospital/product policy. Rule 14(3)'s 90-day ceiling concerns grievance response; it must not be presented as the statutory deadline for every type of rights request.
- **Guardians:** disability alone does not remove an adult's decision-making rights or automatically require a guardian. Applicable lawful authority must be verified. Child-healthcare exemptions are conditional.
- **Board channels:** this application's real Board delivery is unconfigured. That is not a claim that the Board has no official or future submission channel. No live submission API is established by the course.

## Product boundaries

An existing verified patient or authorised guardian can sign in through a browser on a phone, tablet or computer and withdraw an individual purpose remotely. No hospital visit, new consent OTP, withdrawal reason or staff approval is required for that own-account action. New account enrolment and lost-factor recovery still require verified hospital procedures. A limited delegate cannot grant or withdraw consent. Handovers, example passwords and authenticator material in this course are synthetic; learners must never reuse them for operational accounts.

The privacy workspace supplies typed records and internal review for all 20 areas assessed from the uploaded readiness framework: inventory, data flows, obligations, policies, responsibilities, trackers, cross-channel choices, marketing, rights fulfilment, retention, children, vendors, agreements, transfers, impact assessments, security, breach exercises, training, continuous review and the consolidated evidence index. Creating or internally approving a record does not establish complete coverage, legal compliance, authentic external documents, performed remote deletion or an independent assessment. These are metadata/reference workflows, not automatic discovery, document-issuer verification, an LMS or universal hospital-system enforcement. The framework is a commercial programme guide, not a government certificate.

The live marketing preview checks local purpose-specific consent, age, erasure/retention state and an authorised personal SMS route. It does not send a campaign or grant reusable dispatch permission. A real sender must enforce withdrawal immediately before sending.

The prepared edge buffer covers staff-assisted withdrawal intents. Canonical branch feeds, conflict review and managed-node metadata credentials are implemented separately; they are not general offline registration/grants, an autonomous clinical replica or complete multi-writer/fleet operation. A receiver acknowledgement is not independent proof that downstream processing stopped.

FHIR/HL7 is disabled by default and is a scoped custom OAuth facade, without a SMART Backend Services conformance claim. ABDM supports only an explicitly configured local synthetic mock; real NHA sandbox/production exchange is not qualified. The course does not contact live providers. Selecting one of the 23 draft UI languages does not approve a legal notice; patient PDFs remain within the English/Tamil/Telugu/Hindi qualification boundary. Exact-version reviewed recordings and separately labelled on-device speech have different assurance; a matching installed voice and actual language/audio review remain necessary.

Directory administrators are trusted identity operators. Direct patient-read denial for an administrator session is not strong separation from its ability to provision privileged roles or reset staff credentials. Stronger privileged appointment/recovery approval is an open engineering gate. Internal record approval does not resolve this boundary, commission managed key custody or qualify a production deployment.

Before real patient use, obtain approved notices/translations, applicable legal and retention policies, verified identity/alternative/emergency procedures, live-provider and HIS integration evidence, security/accessibility assessment, managed key/backup recovery and operational acceptance. The public training contains no application source, real patient records, operational credentials or private assessment reports.

These are the official instruments reviewed for this release. The MeitY final Rules/commencement publications and official news index were rechecked on 29 October; no later relevant change was located in those checks. This is not an exhaustive legal register or an automatically maintained promise of future currency. Recheck official notifications and hospital counsel before operational reliance. The course teaches the recorded software and its current limits; it is not hospital legal approval or permission to enter real patient information.
