# Aster Care — clinic website concept

A static, multi-page website for a fictional London GP, dental and pharmacy practice.
No build step: the deployable site lives in `mockups/clinic_landing/` (Vercel and Netlify are already configured to publish it).

**Pages:** home, services & prices, about & team, health guides, contact & locations, privacy, accessibility, 404.

**Interactive features (all client-side, nothing is sent or stored):**
- 4-step booking flow: service → clinician → live-looking date/time slots → details, with validation, a confirmation reference and an "Add to calendar" `.ics` download
- "Next available GP" card and "Open now / Closed" badges computed from each studio's opening hours
- Health-guide library with topic filters, search and full-article dialogs
- Urgent-help dialog (999 / NHS 111), contact form and newsletter validation

All names, prices, addresses (Ofcom drama-range phone number, `.example` email) and patient stories are illustrative.

**Sharing:** pages carry Open Graph / Twitter card tags with a purpose-made 1200×630 preview (`assets/og.jpg`) and an Apple touch icon.

**Photography:** clinician portraits and interior/guide photos in `assets/img/` are from [Unsplash](https://unsplash.com) under the Unsplash License, cropped for the site. They are stock photos of models, not real clinicians — the people pictured have no connection to this fictional practice.
