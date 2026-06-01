# Sample Cases — Reviewer Examples

## Example 1 — ID Act Section 10 reference (Karnataka)

> *"Draft an Industrial Disputes Act Section 10 reference application before the Labour Court at Bengaluru (Karnataka) for illegal termination of workman [EMPLOYEE] by [EMPLOYER]. Termination dated [DATE], domestic enquiry vitiated, full back-wages claimed."*

Tool sequence: list_case_types → get_case_type_format("id-act-section-10-reference") → list_states → get_state_exemplar("karnataka") → get_pleading_base → draft → save_draft_as_docx

## Example 2 — Gratuity claim (Maharashtra)

> *"Draft a gratuity application under Section 7 Payment of Gratuity Act 1972 for ₹[SUM-X] denied by [EMPLOYER]. Employee [E] completed 18 years of continuous service before resignation on [DATE]."*

Tool sequence: list_case_types → get_case_type_format("gratuity-claim-controlling-authority") → list_states → get_state_exemplar("maharashtra") → get_pleading_base → draft → save_draft_as_docx

## Example 3 — POSH internal complaint (Delhi)

> *"Draft a POSH Internal Committee complaint under the Sexual Harassment of Women at Workplace Act 2013 for incident dated [DATE] involving [COMPLAINANT] and [RESPONDENT] at [WORKPLACE-X]. Confidentiality framework + Section 19 employer obligations engaged."*

Tool sequence: list_case_types → get_case_type_format("posh-internal-complaint") → list_states → get_state_exemplar("delhi") → get_pleading_base → draft → save_draft_as_docx

## Notes
- All placeholders. No real client data. `save_draft_as_docx` requires `pandoc`.
