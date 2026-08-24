# Join-VPR-FL

Recruiting landing site for VPR United's Orlando/Florida office. Cloned from
Join-VPR-AL (Alabama) & reskinned. Every future office (Tampa, etc.) clones
from this template, so office-specific values must be isolated, not scattered.

## Files
- index.html — landing page. Inline <style>, EN/ES/ZH i18n string objects, tracking + form JS at the bottom.
- calculator.html — brokerage wealth calculator. Shares the same design tokens.

## Rules
- No build step. Static HTML, deployed to Vercel, later pasted into GHL Sites.
- Deliver targeted diffs. Never rewrite a whole file without asking.
- All three languages (EN/ES/ZH) must stay in sync. A string changed in one gets changed in all three.
- Reserve precision for VPR's own numbers. Never invent plan facts, fees, or program names.
- Ampersands over "and" in any copy. No em dashes.

## Known state
- SUPABASE_ANON_KEY is live & correct.
- GHL_WEBHOOK still points at the Alabama sub-account. Pending.
- Phone (251) 620-5646 is Alabama's. Pending a Florida number.
- License #000178551-0 is Alabama's. MUST NOT ship on a Florida page.
- Coaching section & its coaches are Alabama people. Pending Florida answers.
