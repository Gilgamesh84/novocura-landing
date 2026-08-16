# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Three audiences of roughly equal weight:

1. **Patients/clients** seeking homeopathy consultations — Edinburgh-based, plus remote clients based in Turkey. Booking is the primary job.
2. **Practitioners seeking supervision** — homeopaths who want ongoing case supervision from Hande.
3. **Practitioners/students seeking training** — advanced homeopathy education and training registration.

## Product Purpose

Novocura is a boutique homeopathy practice run by Hande Özçıkrıkçı (18 years' experience), based in Edinburgh, serving both local and remote (Turkey-based) clients. Beyond seeing patients, the practice also supervises other practitioners and runs training. Success is a booking — consultation, supervision, or training registration — initiated by email.

## Positioning

The practice's real differentiator is a specific, somewhat contrarian clinical stance, not a generic "caring practitioner" claim:

- **Explicit rejection of the "structural/constitutional remedy" myth.** Many homeopaths treat toward a fixed constitutional type; Novocura argues this is a widely-held misconception (with clinical counter-examples, e.g. critiquing the Kentian approach) and instead treats toward the momentary similimum — strict adherence to Organon.
- **"The body doesn't lie" — observation before theory.** Speculative, spiritual/energetic interpretation is avoided in favor of case observation.
- **Unhurried is a pacing philosophy, not just a longer first session.** Concretely: ~90-minute initial consultation (vs. the ~60 min typical elsewhere), 6–7 week follow-up intervals (vs. ~4 weeks typical), biweekly WhatsApp check-ins between sessions, a 4–5 session / 7–8 month course. The lack of hurry is expressed by the whole rhythm of care, not the session length alone.
- **No conflict of interest in remedy dispensing.** Remedies are prescribed but not sold directly; clients are referred to Helios.
- **"Complementary practice," not a treatment claim.** No curative claims are made — both a regulatory necessity (UK ASA/CAP advertising rules for homeopathy) and a stated ethical position.
- **Practice + pedagogy.** Supervision and training sit alongside patient care, positioning Novocura as expertise/mastery rather than "just another practitioner."

**Known gap (not a directive to fix visually — recorded as product fact):** the current site's tagline/message ("Hikâyenizi dinleyen homeopati" — "homeopathy that listens to your story") reads as warmth/listening, and does not carry the sharper differentiator above (myth-challenging, evidence/observation-first stance). Future messaging work should be aware this mismatch exists between the real mechanism and what the site currently communicates.

## Operating Context

- Bilingual site: Turkish and English, with parallel page sets (e.g. `index.html`/`en.html`, `hakkimda.html`/`about.html`, `randevu.html`/`booking.html`).
- No online payment or scheduling system. All booking flows through `mailto:hande@novocura.co.uk` with subject-routed intents: Booking (Randevu), Supervision (Süpervizyon), Training registration (Eğitim kaydı).
- Static, self-contained HTML site (no framework, no build step, no `node_modules` at the source level for the pages themselves).
- Custom domain: novocura.co.uk (CNAME on file).

## Capabilities and Constraints

- No e-commerce or remedy sales on-site — remedy fulfillment is referred out to Helios, deliberately, to avoid conflict of interest. Do not add a "buy remedies" flow without the user's explicit direction; it would contradict a stated positioning choice.
- All marketing/UX copy must stay within "complementary practice" framing — no language implying diagnosis, cure, or guaranteed outcomes (UK ASA/CAP compliance for homeopathy advertising).
- The "structural/constitutional remedy" critique is a genuine clinical position of the practitioner, not a generic marketing claim — future copy should not soften it into vague "personalized approach" language, which would erase the actual differentiator.
- Undecided: whether/how the myth-challenging positioning should become more visible on the site is an open strategic question, not yet resolved by the user.

## Brand Commitments

- Name: Novocura. Practitioner: Hande Özçıkrıkçı.
- Domain: novocura.co.uk.
- Bilingual delivery (Turkish/English) is a binding commitment, not incidental — both audiences (Edinburgh and Turkey-based clients) are actively served.

## Evidence on Hand

None currently on file — no testimonials, case studies, press mentions, or credentials/certifications have been supplied. Future work must not fabricate any of these; if social proof is needed, it must be sourced from the user first.

## Product Principles

1. Observation before theory — treat the case in front of you (the momentary similimum), not a fixed constitutional type.
2. Unhurried is a rhythm, expressed across the whole course of care (follow-up cadence, check-in frequency), not just a longer first meeting.
3. No conflict of interest — prescribe, don't sell; remedies are sourced through Helios.
4. Complementary, not curative — every claim stays inside that frame, both for regulatory compliance and as a stated ethical stance.
5. Practice and pedagogy together — supervision and training are core to the identity, not an add-on service.

## Accessibility & Inclusion

Bilingual Turkish/English delivery is the practice's stated inclusion commitment, serving both Edinburgh-based and Turkey-based clients in their preferred language. No other accessibility requirement has been established yet.
