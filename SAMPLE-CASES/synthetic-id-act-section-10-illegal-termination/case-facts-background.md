# Case Facts Background — Industrial Disputes Act Section 10 reference · illegal termination

All party names, employee codes, plant locations, monetary figures, charge-sheet / dismissal-order numbers, and ancillary dates are fictional placeholders.

## Parties

- **Workman / Petitioner:** [Workman-A], aged about [Workman-Current-Age-Placeholder] years, permanent workman within the meaning of Section 2(s) of the Industrial Disputes Act, 1947. Period of service: 01 March 2005 to 28 October 2025 — 20 years and 8 months of unblemished service.
- **Management / Respondent:** M/s [Employer-Company-Placeholder] Private Limited, registered office at [Employer-Registered-Office-Placeholder], manufacturing unit at [Employer-Plant-Placeholder]. Industrial establishment within the meaning of Section 2(j) ID Act 1947.

## Employment history

- **Appointment letter dated 15 February 2005** — designating workman as PERMANENT, NON-SUPERVISORY, governed by Certified Standing Orders. (See `01-letter-of-appointment-2005-02-15.docx`.)
- **Effective date of appointment:** 01 March 2005.
- **Designation throughout service:** [Designation-Placeholder]. Never promoted to supervisory cadre — workman status preserved.
- **Service record:** Unblemished prior to August 2025 charge sheet. No prior warnings, no prior misconduct entries.

## Charge sheet and domestic enquiry

- **Charge sheet HR/CS/[CS-No-Placeholder]/2025 dated 15 August 2025** alleging (a) wilful disobedience, (b) habitual late attendance, (c) intemperate language.
- **Reply submitted by workman:** 28 August 2025 — denial.
- **Enquiry conducted by external Enquiry Officer ([Enquiry-Officer-Placeholder]):** [Enquiry-Date-Placeholder] — single-day enquiry, less than 3 hours.
- **Enquiry vitiated on multiple grounds** (see workman's protest letter at `03-workman-protest-letter-2025-11-12.docx`):
  - Less than 48 hours' notice of enquiry (Certified Standing Orders require 7 days).
  - Union representation denied without recorded reasons.
  - Cross-examination of two witnesses denied on "time constraint".
  - Workman's documentary evidence refused.
  - External Enquiry Officer on Management pay-roll (Rs. [Enquiry-Officer-Fee-Placeholder]/- per day).
  - Conclusory findings without application of mind.

## Termination

- **Dismissal order dated 28 October 2025** — Order No. HR/DISC/[Dismissal-Order-No-Placeholder]/2025 (see `02-termination-order-2025-10-28.docx`).
- **Effect:** Termination with effect from 28 October 2025. Workman directed to surrender all company property.

## Workman's protest

- **Protest letter dated 12 November 2025** — see `03-workman-protest-letter-2025-11-12.docx` — demanding withdrawal of dismissal, reinstatement, full back-wages, continuity of service.
- **Management's response:** No response received within the 15-day window.

## Forum and case type

- **Statutory route:** Industrial Disputes Act, 1947.
- **Initial step:** Conciliation under Section 12 — workman raises industrial dispute through the Recognised Union / individually.
- **Failure of conciliation → Section 10 reference** by the appropriate Government to the Labour Court / Industrial Tribunal.
- **Case type:** `id-act-section-10-reference`.
- **State:** Karnataka (Labour Court at Bengaluru, per state exemplar).

## Reliefs sought

1. Setting aside of the dismissal order dated 28 October 2025.
2. Reinstatement of the workman in service with continuity of service.
3. Full back-wages from 28 October 2025 till the date of actual reinstatement, with interest.
4. Direction to expunge all adverse entries from the workman's service record.
5. Costs and incidental reliefs.

## Ingredient check (Verifier-stage)

- ✅ Workman status under Section 2(s) ID Act — appointment letter confirms PERMANENT, NON-SUPERVISORY designation.
- ✅ Industrial dispute under Section 2(k) — dispute between workman and employer concerning conditions of employment / dismissal.
- ✅ Industry under Section 2(j) — manufacturing establishment.
- ✅ Vitiation of enquiry — multiple natural-justice violations particularised (Crompton Greaves Ltd., Tata Engineering & Locomotive Co. line).
- ✅ Disproportionate punishment — 20 years' unblemished service vs alleged minor lapses (Workmen of Hindustan Steel framework).
- ✅ Section 11A ID Act — Labour Court has powers to reappraise evidence and substitute lesser punishment.
- ✅ Limitation — Section 2A(2) ID Act — 3 years from date of dispute (post-2010 amendment). Filed well within time.

## How to use this fixture

1. Point `read_case_folder(path)` at this directory.
2. Reader extracts facts from the 3 `.docx` files plus this `case-facts-background.md`.
3. Call `get_case_type_format("id-act-section-10-reference")`.
4. Call `get_state_exemplar("karnataka")` for Karnataka-specific Labour Court / Bengaluru conventions.
5. The remaining 5 agents (Format → Drafter → Verifier → Refiner → Overseer) run end-to-end to produce `final-draft.docx` containing the Section 10 reference application + Statement of Claim + List of Documents + List of Witnesses + Verification + Affidavit.
