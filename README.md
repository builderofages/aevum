# Aevum — Independent Life Insurance Agency

*Aevum* (Latin): a lifetime; eternity.

Premium digital life insurance agency site. Static HTML, no build step — runs from GitHub, deploys free on GitHub Pages or Cloudflare Pages.

## Live preview

Once GitHub Pages is enabled (Settings → Pages → Deploy from branch `main` / root), the site is at: https://builderofages.github.io/aevum/

## Status: DRAFT — do not publish until licensing is complete

Hard blockers before this can solicit anyone:

1. FL 2-15 individual license issued
2. FL agency license issued for the LLC (name matches branding, or DBA registered)
3. Non-resident licenses (MD/VA/PA) issued
4. Footer license numbers / NPN populated in `index.html`
5. Quote embed wired (BackNine Quote & Apply or Ethos for Agents)
6. Privacy / Terms / Accessibility / Licensing pages written
7. `docs/compliance-checklist.md` fully passed

## Structure

- `index.html` — single-file landing page (Fraunces + Instrument Sans)
- `docs/brand.md` — brand system: colors, type, voice
- `docs/compliance-checklist.md` — pre-launch legal checklist
- `.github/workflows/deploy.yml` — CI: HTML validation + compliance red-flag scan

## Non-negotiable rules baked in

- No ad pixels / session replay on any page collecting health answers (pixel enforcement in this space has topped $100M).
- No SSNs or health data collected by this site — sensitive data flows carrier-direct via the embedded e-app.
- Any page naming a specific carrier/product/rate needs that carrier's ad approval first.
- Never: guaranteed approval, financial-advisor claims without credential, investment/savings framing, fake scarcity.
