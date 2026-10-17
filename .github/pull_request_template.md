## Summary

<!-- What does this PR do and why? Keep it short. -->

Closes #

## Type of change

- [ ] 🐞 Bug fix
- [ ] ✨ Feature
- [ ] ♻️ Refactor (no behaviour change)
- [ ] 📝 Docs
- [ ] 🔧 Build / CI / tooling
- [ ] 💥 Breaking change (API, data schema, sync protocol or migration)

## Affected area

- [ ] Flutter app(s) — flavor(s): <!-- patient / PRO / Dawaa / Hub / Connect -->
- [ ] Backend API (.NET)
- [ ] Web (Next.js)
- [ ] Sync
- [ ] Auth
- [ ] FHIR resources / integrations
- [ ] Database migration

## How was this tested?

<!-- Unit / widget / integration tests, manual steps, devices used. -->

**Platforms checked:** <!-- Android / iOS / Web / Windows / macOS / Linux -->

## Screenshots / recordings

<!-- Required for UI changes. Show Arabic (RTL) and English (LTR). Test data only. -->

| Arabic (RTL) | English (LTR) |
| --- | --- |
|  |  |

## Balsm checklist

- [ ] **No PHI leaves the workspace server** — nothing patient-identifiable is sent to Balsm's cloud, logs, analytics or crash reports (ADR-10)
- [ ] **Works offline** and recovers cleanly when connectivity returns
- [ ] **Arabic / RTL** layout and copy verified
- [ ] New IDs use **UUID v7**
- [ ] Data models stay **FHIR R4**-conformant
- [ ] Migrations are reversible and safe for existing self-hosted installs
- [ ] No secrets, keys or real patient data in code, tests, fixtures or screenshots

## General checklist

- [ ] Self-reviewed the diff
- [ ] Tests added or updated, and passing locally
- [ ] Docs / changelog updated where needed
- [ ] I agree to the [Balsm Contributor License Agreement](https://github.com/balsm-health/Balsm-Core/blob/main/legal/cla.md) (platform repositories only; MIT packages don't need it)

## Notes for reviewers

<!-- Anything tricky, follow-ups, or areas you want a careful look at. -->
