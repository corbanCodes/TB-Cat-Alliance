# Florida Dealz — Demo Site

Demo site for **Florida Dealz** — a monthly digital 3D flipbook of local business ads/coupons for the Tampa Bay area. Pure ad-space business: she sells the spots, businesses send their ads, a new issue publishes monthly. Built by [60MinuteSites](https://60minutesites.com).

> Note: originally branded around Tampabay Cat Alliance (client's former org — now defunct). Rebranded 8/14/2026 per Corban: no rescue angle, but the cat mascot stays for fun (it wears sunglasses now). Repo name still `TB-Cat-Alliance`.

## Status

- **Demo** — built 8/14/2026 from call notes. Client sells ad spots in person / with flyers (email outreach doesn't work for her); starting two counties (Pasco + Hernando), bigger county next.
- Forms submit to 60MinuteSites Formspree (`xojeqvng`) for testing, with `_subject` prefixed `Florida Dealz DEMO —` and auto-redirect to `thank-you.html`.
- Payment links go to `60minutesites.com/checkout-information.html?plan=monthly|annual`.

## Pages

- `index.html` — hero, **working interactive 3D flipbook** (8 demo pages, click/swipe/keyboard), how it works, ad rates, county coverage, our story, ad-spot inquiry form + reader email capture
- `pricing.html` — custom 60MS pricing ($150 + $50/mo, or $500/yr) with checkout links
- `thank-you.html` — form redirect target

## Placeholders the client should confirm

- **Name** "Florida Dealz" spelling/logo treatment.
- **Ad rates** ($249 front cover / $199 back cover / $99 full / $59 half, 2+1 free bundle, 12-mo founding lock) — placeholder numbers, she hasn't set pricing.
- **Sample ads** in the flipbook are fictional (labeled "SAMPLE" on-page and disclaimed in the footer).
- Launch counties shown as Pasco + Hernando, "Hillsborough & Pinellas next" — matches her 2-then-1-bigger plan but not final.
- No domain chosen yet (floridadealz.com etc. — check availability).

## To make it live for real

1. Client pays via pricing page.
2. Buy + point her domain.
3. Swap Formspree IDs (or keep routing to 60MS inbox), remove demo bars/disclaimers, remove `noindex`.
4. Replace demo flipbook pages with her real first issue (each page is plain HTML — or embed a PDF-based flipbook tool later if she prefers uploading PDFs).
