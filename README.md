# REYDLEON

**Paulo Reydleon** | Civil & Rail Engineering | PMP

Engineering professional focused on rail infrastructure, track installation, special trackwork, and construction delivery.

### [Visit my official website — reydleon.ca →](https://reydleon.ca)

Explore my professional experience, projects, credentials, and CV at **[reydleon.ca](https://reydleon.ca)**.

---

*Reydleon is my primary professional brand. This GitHub profile is a gateway to my official website.*

## Preliminary internal code audit (2026-11-13)

**Review item (not a confirmed defect):** Keep the profile link, professional description, and destination website accurate; no application runtime is maintained here.

**Verification status:** Static review only; automated tests, dependency scanning, and production deployment checks have not been completed. Prioritize validation before treating this item as resolved. This note does not imply that a live defect has been reproduced.

## Language and architecture

- **Primary language:** Undetermined (documentation/profile repository).
- **Implementation classification:** Unverified.
- **Verification:** Primary language is based on GitHub language-filtered repository search (2026-11-14). Architecture notes are based on existing README documentation; source-level class verification remains pending unless explicitly documented above.

## GOLDEN RULE — ONE CLASS-BASED PYTHON FILE

For each repository, keep all production Python implementation in one canonical `.py` file, organized as multiple classes using object-oriented design. Do not split production behavior across separate Python modules. Test files may remain separate under `tests/`; entry points may remain only as thin delegates to the canonical file, with no duplicate implementation. When consolidating an existing project, preserve its behavior and update every deployment command, container build, and runtime import that points to the old modules.


## GOLDEN RULE — Revision Logic

Every release revision MUST follow `vYYYYMMDD[L][N]`, where `YYYYMMDD` is the release date, `[L]` is a lowercase letter (`a`–`z`), and `[N]` is a positive integer starting at 1. Examples: `v20261122a1`, `v20261122a2`, `v20261122b1`. Never add extra leading zeros, separators, or spaces. Each new release must have a unique revision identifier; use a new date when the release date changes. Display the actual current revision in the application footer where applicable, and keep README release history consistent with actual releases. Do not claim a release occurred merely because this rule was documented.
