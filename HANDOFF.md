# Salsabil Construction — handoff at ~60%

**Live:** https://10elizabethbell.github.io/salsabilConstruction/ · **Repo:** https://github.com/10elizabethbell/salsabilConstruction · **Built:** 2026-10-20 from Muse brief (run 2026-10-20, Facebook group "NJ CONTRACTORS, BUILDERS & GC's" ad)

## What's built
- One page, calm band style: paper header (keyed-out logo left, tap-to-call (347) 243-9333 top right) → navy hero → "From the framing to the final coat" with a big Instagram row beside it on desktop → six service rows on navy → How it works on deep navy → quote form → closing band (white logo, "Call or text Sam.", big number) → footer.
- Palette from the flyer logo: orange #f8580a as the one accent fill (navy text on it), #a83c08 when orange is text on light, #ff7a33 for orange words on navy. The logo's black became steel navies #1b3358 / #10213b (page ground never black).
- Hero: **plain textured navy**. No job photos were reachable: Instagram posts need a login and the only image in the brief is the flyer, which isn't a work photo.
- H1 "Remodeling done right in NY & NJ." bounces in letter by letter; `.rise` fade-up below the first screen; both off under reduced motion and without JS.
- Contact: hero "Get a quote" (to the form) and "Text Sam" (sms: with a pre-written body); the form composes a text to Sam (with Open in Messages / Copy message / call fallbacks); tapping a service row pre-ticks its chip; floating text circle appears after the hero and hides near the form and row arrows.
- Logo keyed out of the flyer into dark and white transparent versions; favicon and home-screen icon are the house mark; og.png 1200×630.

## Assumptions I made
- **Instagram stands in for Facebook.** The only Facebook presence is Samandar Usmonov's personal profile, and the brief says his link to the business is unconfirmed, so I didn't link it. @salsabil_construction is printed on their flyer and is live (named "Salsabil Construction", 37 posts, 109 followers on 2026-10-20), so the "Click to see our work." row and the footer point there.
- "We" voice (their caption says "We deliver…"), with Sam named as the contact ("Call or Text Sam" on the flyer).
- Trust copy: "We do the framing, drywall, tile, floors and paint, so one call to Sam covers the whole job" is inferred from their service list, not stated by them. "We leave it the way we'd want ours left" is my line about care — check with Sam.
- How it works step 2 says only "Sam gets back to you with a price." (no pricing policy is claimed).
- Hero eyebrow "Home renovation contractor" (changed from "Renovations & remodeling" so it doesn't repeat the H1).
- Service names shortened from the flyer: Home renovations, Kitchens & bathrooms, Flooring & tile, Painting & drywall, Framing & carpentry, Interior & exterior.
- Area kept to "NY & NJ" / "New York and New Jersey" (flyer). No towns.

## Placeholders and gaps
- No work photos, before/afters or reviews anywhere on the page. Biggest gap: the proof is one Instagram link.
- No email (footer has none), hours, prices, licence/insurance, years in business.
- Facebook: no business page; personal profile not linked (see above).

## Questions for the owner
- Can we use photos from your Instagram? (Best ones for a photo hero and a work section with before/afters.)
- Which towns do you work in most? (Would let the H1 and close name real places.)
- Email for the footer? Hours? Licensed and insured in NY/NJ? Years in business?
- Is there a Facebook business page, or should Samandar's profile be linked?
- Any customer reviews you're happy to quote?

## Ideas not built (yours to pick)
- **Photo hero + work section** once Instagram photos are in hand (4:5 work cards over the Instagram row).
- **Desktop hero right half is empty.** The finish reviewer suggested centring the hero copy at 1024px+ (your Shamrock note); I kept the house left-aligned layout. Other option: a job photo once we have one. (The white logo there would repeat the header logo.)
- Their tagline as a three-item icon list (Quality work / Honest service / Professional results): cut because it repeated the hero promise word for word.
- Signature motion (opt-in), worlds from the trade:
  1. **Tile laying (best):** a grid of tiles that sets itself across the hero bottom, grout lines and all; drag to lay/lift tiles.
  2. Paint roller stroke that follows the finger, revealing the next colour.
  3. Framing studs rising into a wall frame as you scroll.
  4. Sawdust that drifts and parts around the pointer.
- Impeccable findings kept because they're your chosen calm-style features: eyebrow pills, H1 bounce-in, floating text circle, Cal Sans, the faint diagonal band texture (detector: "repeating-gradient stripes", suppressed for index.html in `.impeccable/config.json`). The detector's "flat type hierarchy" warning is suppressed too: it only sees the 14–20px text sizes, not the 30–80px clamp() headings; I merged 15/17/19px into 14/16/18px first.

## Not verified
- Real-device touch and the real SMS handoff on iOS/Android (tested in Playwright Chromium and WebKit: message text composes and encodes correctly).
- Facebook/Instagram in-app browser behaviour of `sms:` links.
- Frame rate on old phones.
