# CareConsent release update: hospital purposes, integrations, languages and security hardening

English training, build 431016c. Synthetic training information only.

## 01. Start here: the 10 November release

Role: All users

### 00:00:00.000 — Start here: the 10 November release

This update describes release four three one zero one six c. Watch it before the November seventh update and the dated November fifth course. It covers hospital consent purposes, integrations with health record systems, additional languages, and security changes that operators should understand. These cards explain the workflow; they are not recordings of clicks. Practise only with invented records. A hospital deployment still requires commissioning, approved notices and live providers.

- Watch this update first
- Then the 7 November update and dated course
- Practise with synthetic records only

Keep in mind: Current guidance; earlier footage stays dated.

## 02. Hospital consent purposes

Role: Privacy officers and reception

### 00:00:34.250 — Hospital consent purposes

A privacy officer can now draft a hospital purpose under one of the five base purposes, with its own notice wording in each language. A different privacy officer must confirm the translations were reviewed and approve it. A scoped purpose can only narrow its base purpose, never widen it. Reception records each purpose as a separate choice, and patients can withdraw one purpose without touching the others. Retiring a purpose stops new choices; earlier records stay in history.

- Draft wording under a base purpose
- A second privacy officer approves
- Record and withdraw each purpose separately

Keep in mind: Purpose wording remains a hospital and counsel decision.

## 03. Health record systems follow consent

Role: Integration and IT operators

### 00:01:08.208 — Health record systems follow consent

The hospital record system can now ask CareConsent for the current allow or deny decision through a signed request, and receives a signed answer. Requests outside the time window or repeating a used value are refused. Connected systems can authenticate with SMART backend services using a signed client key. The ABDM bridge supports mock and sandbox modes and verifies gateway signatures. Your vendor's adapter must still enforce the decision where records are opened, and ABDM use needs National Health Authority onboarding.

- Record system asks for the signed current decision
- SMART clients sign in with their own key
- ABDM sandbox only until onboarding

Keep in mind: Not ABDM or SMART certified.

## 04. Additional message and PDF languages

Role: Privacy officers and language reviewers

### 00:01:44.667 — Additional message and PDF languages

The pilot languages remain reviewed. Fifteen further Indian languages now have draft messages and patient PDFs using bundled fonts for each script. A draft language is not sent to patients until a named reviewer records an attestation that the wording was checked. Until then, those patients receive English messages. Ask your hospital's approved translator to review the wording, and report any confusing phrase rather than editing it during a patient conversation.

- Pilot languages are already reviewed
- Drafts need a named reviewer attestation
- Report unclear wording to the language owner

Keep in mind: Machine drafts are not sent until attested.

## 05. Security changes for operators

Role: Security and identity operators

### 00:02:17.000 — Security changes for operators

Sign-in and session records are now isolated per hospital. Configured keys must be full random keys; passphrases are rejected, and webhooks use their own key instead of reusing the multi-factor key. Each audit entry's hash now covers the branch, the person acting and the affected record. Recorded security events cannot be edited or deleted by the application. Webhooks to private network addresses are blocked, including names that resolve to them. If a configuration is refused at startup, correct it rather than weakening the setting.

- Use full random keys, separate per purpose
- Audit hashes cover branch, actor and record
- Webhooks only to approved public endpoints

Keep in mind: Independent penetration testing remains open.

## 06. Hardware-protected keys and audit anchoring

Role: Authorised operations staff

### 00:02:55.000 — Hardware-protected keys and audit anchoring

A deployment can now require its symmetric keys to be sealed by a hardware security module, so plain key material is not stored in configuration. Signed audit log heads can be published automatically to separately owned immutable storage and re-verified later, which helps show that history was not rewritten. The security monitor refuses the hospital or migration database connection and checks it is running under its own database role. Your team must provision the real key vault, storage and monitor role.

- Seal keys with the hardware module
- Publish and re-verify audit anchors
- Run the monitor under its own role

Keep in mind: Real HSM and storage need provisioning.

## 07. What has not changed

Role: All users

### 00:03:29.625 — What has not changed

Everyday reception, patient withdrawal, breach handling and offline branch workflows continue as taught in the earlier update and course. Board filings now need the actual filing time and a staff attestation, and guardian records need explicit verification before they can support consent. This release was tested locally with synthetic data; it is not a hospital production approval or a compliance certificate. Before real use, your team must commission providers, hosting, translations, integrations and an independent assessment.

- Earlier workflows remain valid
- Attest Board filing times and guardians
- Commission before real patients

Keep in mind: Not a production approval or compliance certificate.
