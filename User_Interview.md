# VårdAI — Clinic receptionist interview

**Author:** Ikbal Ismail
**Persona:** Sara — clinic receptionist
**Date:** June 2026

---

## Part 1 — Discussion guide (reusable template)

Run this with 2–3 receptionists at clinics you know. Keep it to 15–20 minutes. Ask open questions, then go quiet — let them talk.

**Warm-up**
1. Walk me through a typical day handling patient calls and messages.
2. What's the most repetitive question patients ask you?

**Pain points**
3. What happens when a patient calls outside opening hours?
4. Tell me about a time a booking was missed or mishandled. What went wrong?
5. Do you ever struggle to communicate with patients who don't speak Swedish well?

**Reaction to AI reception**
6. If an AI handled basic questions and bookings automatically, what would worry you about that?
7. What would you need to see to trust it with real patients?
8. What should it never be allowed to do on its own?

**Closing**
9. If you could automate one part of your day, what would it be?

---

## Part 2 — Example summary

> **Note:** the insights below are a realistic illustrative example of what this interview might surface, written to show the format. Replace this section with real responses once the interview has actually been run — that's what turns this into genuine user research rather than a hypothetical exercise.

### Pain point — After-hours calls go fully unanswered
Receptionist estimated 10–15 missed calls per week outside clinic hours, with no way to know how many became lost bookings.

### Pain point — Language gap with Arabic-speaking patients
Described relying on translation apps or a bilingual colleague when available — both slow and inconsistent.

### Trust requirement — Wants full visibility before adopting AI
Said she would need to read every AI conversation log for the first few weeks before trusting it unsupervised — directly validates the conversation history feature in the PRD.

### Direct reaction
> "As long as it never tells someone what's wrong with their teeth, I'm fine with it answering the easy stuff."

---

## Takeaways

**Validates:** Hard triage guardrails, conversation logging, and Arabic support — all already P0/P1 priorities in the PRD.

**New signal:** Trust is built gradually. Consider a "supervised mode" toggle for the first 2–4 weeks per clinic, where staff approve AI responses before they're sent.
