# Aevum Pre-Launch Compliance Checklist

Work through every item before the site accepts real traffic.

## Licensing gates (hard blockers)

- [ ] FL 2-15 individual license issued and active
- [ ] FL agency license issued; agent-in-charge designated
- [ ] Agency legal name / registered DBA matches site branding EXACTLY in all four states
- [ ] MD, VA, PA non-resident individual + agency licenses issued
- [ ] VA: LLC foreign-qualified with VA SCC (within 90 days of VA license or it terminates)
- [ ] Footer populated: FL agency L-number, NPN, licensed-states line

## Site content

- [ ] Jurisdiction limiter present (FL, MD, VA, PA residents only)
- [ ] Independent-agency-not-insurer disclosure present
- [ ] No carrier names/logos/products/rates without that carrier's written ad approval (keep approvals + dated screenshots 5 years)
- [ ] No prohibited terms: guaranteed approval; financial advisor/planner without credential; investment/savings/retirement plan framing; government-lookalike anything
- [ ] All speed/no-exam claims qualified (most applicants; as fast as same day)
- [ ] Testimonials: real, current, disclosed if compensated; none fabricated (FTC review rule)
- [ ] No fake scarcity or countdowns (age-banded rate urgency is the only legal urgency)

## Forms, consent, privacy

- [ ] Lead form collects contact info + coverage interest ONLY - no SSN, no detailed health data
- [ ] TCPA/FTSA consent: unchecked checkbox, names the agency LLC, autodialer disclosure, not-a-condition-of-purchase, STOP honored within 15 days (FTSA) / revocation within 10 business days (FCC)
- [ ] Consent logging live (timestamp, IP, form snapshot - TrustedForm or equivalent)
- [ ] Privacy Policy published (GLBA posture; health info opt-in only; no sale of data)
- [ ] NO Meta/TikTok/Google pixels or session-replay on quote/health pages; consent banner blocks marketing tags pre-consent
- [ ] Quote engine embed (BackNine / Ethos) live; carrier data flows carrier-direct
- [ ] AI chatbot clearly disclosed as automated; never states approval/denial; hands off to licensed advisor

## Security (day-1)

- [ ] WISP written (VA has NO small-agency exemption)
- [ ] Incident response plan with regulator clocks: VA 3 business days, PA 5, MD 3, FL 30 days to consumers + AG at 500+
- [ ] MFA everywhere; password manager; full-disk encryption
- [ ] Cyber liability policy bound (~$1M incl. regulatory coverage)
- [ ] Vendor SOC 2 reports collected; breach-notice clauses in contracts

## Accessibility and quality

- [ ] WCAG 2.1 AA audit passed
- [ ] Accessibility statement page published
- [ ] Core Web Vitals pass on mobile

## Ongoing

- [ ] Ad file: every page/email/ad archived with dates, kept 5 years
- [ ] Site snapshots on every deploy (automated in CI)
- [ ] Annual: CE, WISP review, vendor review, consent-language recheck
