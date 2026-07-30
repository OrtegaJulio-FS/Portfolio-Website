# Buyer Analysis — julioortega.design

Purpose: model the actual humans who'd hire a Des Moines web designer, and figure out what the site currently fails to show them. This is analysis only — no code changes in this file's scope. Written against the site as of the current build (single hero, "I design websites/interfaces/..." cycling headline, "Remote / worldwide" availability line, three self-directed concept projects in a wheel, no phone number, no price info, no location signal).

---

## 1. Three buyer personas

### Persona A — Marisol, taquería owner
- **Business**: Runs a 30-seat taquería with her brother. Been open four years. Word travels through regulars and a Facebook Page with ~1,800 followers where she posts specials with her phone camera.
- **Business pressure**: A new taco spot opened two exits away with a real website and it's showing up on Google Maps before her. She's not losing regulars, she's losing people searching "tacos near me" who've never heard of her.
- **Tech comfort**: Comfortable with Facebook, Instagram, texting, maybe Square for payments. Has never touched a CMS. Doesn't know what a "CMS" is. Would call "hosting" and "domain" the same thing.
- **What she types into Google**: "website for restaurant cheap," "how much does a website cost," "web designer near me," possibly in Spanish first.
- **What she's afraid of**: Getting quoted a number with no idea what it includes. A recurring monthly bill she doesn't understand and can't cancel. Being talked down to or handed jargon. Paying upfront and the person disappearing.
- **The one thing that makes her feel safe reaching out**: Seeing a real price range stated plainly, and a way to see something (even a mockup) before she commits any money.

### Persona B — Dave, café owner
- **Business**: Owns a neighborhood café. Had a Squarespace site built by a nephew or a one-time freelancer in 2019. It still has the old logo, an outdated menu, and doesn't work right on phones.
- **Business pressure**: He knows the site is bad — customers have told him the menu is wrong. He's not in crisis, just embarrassed, and it's been "on the list" for a year.
- **Tech comfort**: Higher than Marisol — he's logged into Squarespace before, knows what a domain renewal email looks like, but doesn't want to be the one maintaining it going forward.
- **What he types into Google**: "web designer Des Moines," "update my website," "small business website design Iowa."
- **What he's afraid of**: Paying for a rebuild and ending up in the same spot — a site he still can't update himself, that still looks generic, from someone he can't reach after the invoice clears.
- **The one thing that makes him feel safe reaching out**: Evidence the designer actually finishes things and sticks around — a clear process with named steps and an end point, not an open-ended engagement.

### Persona C — Ray, landscaper
- **Business**: One-truck landscaping and lawn-care operation. All work comes from referrals and a sign on the truck. No website at all — just a phone number.
- **Business pressure**: He's started losing quotes to competitors who show up in a Google search with a real site and reviews. A prospective customer googled him mid-quote and found nothing, which cost him credibility on the spot. He doesn't need more traffic — he needs to look legitimate to people who already found him.
- **Tech comfort**: Lowest of the three. Runs his business by phone call and handshake. Will open a link from a text message on his phone, will not sit down at a laptop to fill out a form.
- **What he types into Google**: Honestly, probably nothing — he'd search "web designer near me" once, on his phone, between jobs, or ask around. If he does search: "get a website for my landscaping business."
- **What he's afraid of**: Sounding stupid asking basic questions. Being sold a bunch of add-ons he doesn't need (SEO packages, "branding," social media management) when he just wants a page that says he's real, with his number on it.
- **The one thing that makes him feel safe reaching out**: A visible phone number and the option to just call — not a contact form as the only path. Plain language that never requires him to ask "what does that mean?"

**Cross-persona pattern**: none of the three fears "will it look bad" — none of them doubt the craft once they see it. All three fear the *transaction*: the money, the jargon, the vanishing act. That reframes the whole site's job: prove competence fast (it's a portfolio, that part is easy), then spend the rest of the page defusing the money/trust/hassle fears, which the current site doesn't address at all.

---

## 2. The decision journey — first 60 seconds

### What the current first screen actually shows
A giant animated "Julio Ortega." headline, a cycling word ("I design websites / interfaces / interactions / experiences / systems"), a sentence about "art-directed, motion-driven sites," and "Available for freelance / Remote / worldwide."

### What each persona needs answered before they'll scroll
In order, all three personas run the same silent checklist. The current site answers **zero of the four** on screen one.

1. **"Is this a real business/person, not a scam?"** — answered by a name, a face, a location. Site has a name and (later, in the About section) a face — but "Remote / worldwide" actively signals *not local*, which for Ray and Marisol reads as "not someone I can walk up to."
2. **"Can this guy actually do it?"** — this is the one thing the current site nails, eventually. The work section is strong. But it's screen two, and a low-trust visitor may not scroll to see it if screen one felt like it wasn't talking to them.
3. **"Will it be expensive?"** — never answered anywhere on the page. No price, no range, not even "starting at." Silence here reads as "expensive" by default, and expensive-by-assumption is a silent exit — the visitor leaves without ever finding out they were wrong.
4. **"Will this be a hassle?"** — never answered. No process, no timeline, no "here's what happens after you email me."

### Objection order and where each persona breaks
The three personas hit these in a consistent sequence:

1. **"Is this for me?"** (0–3 sec) — Marisol and Ray, both low-tech-comfort, land on a cycling word like "interfaces" / "systems" and a phrase like "art-directed, motion-driven" and immediately feel like they wandered into a page meant for other designers, not for them. This is the single biggest first-screen failure. Dave (higher comfort, already knows what a website should look like) survives this beat longest but still doesn't see his business reflected.
2. **"Can this guy do it?"** (3–15 sec, if they scroll) — solved well once they reach Work. The three concepts (landscaping, coffee shop, boutique) are, by lucky accident, close analogues to all three personas' actual businesses. That's a real asset, currently under-leveraged because nothing on screen one tells them to keep scrolling to find it.
3. **"Will it be expensive?"** (15–30 sec) — no answer anywhere. This is where Marisol specifically leaves: she came in already anxious about cost, found no number, and won't email a stranger to ask, because asking feels like exposing that she can't afford it.
4. **"Will this be a hassle / will I get ghosted?"** (30–45 sec, only for the ones who reach About/Contact) — partially addressed by "Replies within a couple of days," which is actually a small positive signal, but there's no description of what happens *after* that reply — no named steps, no timeline.
5. **"Can I trust him specifically, right now, enough to send the first message?"** (45–60 sec) — the contact section is an email address and three off-site links (GitHub, LinkedIn, Fiverr). For Ray, there's no phone number and no "just call me" option — the single highest-friction possible ask for his profile.

### Where they reach out vs. leave
- Dave is the most likely to convert on the current site as-is, because he has enough tech fluency to look past the jargon and judge the work on its merits, and he's patient enough to reach About.
- Marisol and Ray are likely to leave in the first 15 seconds, before ever reaching the work that would actually convince them, because the entry copy doesn't signal "this is for a business like yours."

---

## 3. Ranked conversion principles — top 10 changes for this audience

Ranked by (impact on the 60-second journey above) × (how many of the three personas it unblocks).

1. **Speak to the buyer's business, not the designer's craft, in the first screen.** *Failure*: hero copy is entirely about the designer's process ("I design experiences," "art-directed, motion-driven"). *Fix*: hero must say, in plain words, who this is for (small local businesses) before it says anything about style. This single change unblocks the "is this for me?" objection that currently loses Marisol and Ray before they scroll.
2. **Answer the price question before they have to ask it.** *Failure*: no pricing information anywhere on the page. Unanswered price questions cause silent exits — visitors don't email to ask, they just leave. *Fix*: a plain-language pricing section, even just ranges tied to project types, framed around what's included.
3. **State a local signal early.** *Failure*: "Remote / worldwide" is the only geographic claim, and it points away from local. *Fix*: "Des Moines" (or "Iowa") needs to appear in the first screen. Local signals build outsized trust for local buyers — it's the difference between "some designer" and "someone in my city."
4. **Give a friction-free first contact path.** *Failure*: contact is a single mailto link plus off-site social/portfolio links; no phone number, no text-friendly path. *Fix*: a tap-to-call or tap-to-text phone option alongside email, since the personas will open this from a phone.
5. **Name the process so "will this be a hassle" gets answered before it's asked.** *Failure*: nothing on the page describes what happens between "I email you" and "I have a website." *Fix*: a short numbered process (e.g., "1. Free preview → 2. You approve → 3. I build → 4. It goes live"), because friction/ambiguity kills action even when price is acceptable.
6. **Offer a concrete risk-reversal, not just an invitation to contact.** *Failure*: the CTA is generically "get in touch," which asks the buyer to take on all the risk of the first step. *Fix*: a specific low-risk offer (e.g., a free homepage preview before any money changes hands) gives the anxious buyer a reason to say yes that doesn't feel like signing up for anything.
7. **One primary call to action, repeated, not diluted by three outbound social links of equal visual weight.** *Failure*: footer treats GitHub, LinkedIn, and Fiverr as equal-weight actions next to the email — none of which is the actual conversion goal. *Fix*: one clear primary action (call/text/email to start a preview) with social links demoted to a quieter, secondary role.
8. **Be specific instead of impressive.** *Failure*: copy like "kinetic type, custom interaction, interfaces that feel like something instead of just displaying it" is vivid but tells a café owner nothing about their outcome. *Fix*: specificity — "a site that loads fast, works on a phone, and gets you found on Google" — builds more trust with this audience than clever language, even though it's less impressive to other designers.
9. **Reduce jargon density across the page.** *Failure*: "art-directed," "motion-driven," "kinetic type," "scroll choreography" are all designer-industry terms. *Fix*: rewrite in the voice a neighbor would use, per the voice guidance — this directly defuses the "will I understand what I'm buying" fear for Marisol and Ray.
10. **Make "can this guy do it" land faster by pulling relevant proof toward the top.** *Failure*: the strongest asset on the page — three concept builds that map almost exactly to the three personas' businesses — sits behind a full scroll past a hero that hasn't earned the scroll. *Fix*: either shorten the distance to Work, or seed a preview of it (a name, a thumbnail, a "see a landscaping site I built" hint) inside the first screen so low-trust visitors have a reason to keep going.

*Note on things the site already does right, so they aren't accidentally undone in Phase 3*: the "Replies within a couple of days" line is a real trust signal (sets an honest expectation) and should be kept or strengthened, not cut. The concept-project labeling ("Self-directed concept builds... not live client work") is already honest and should stay exactly that honest — the fix is presentation and reach, not removing the disclosure.

---

## 4. The honesty constraint — legitimate trust signals for a zero-client freelancer

No fabricated proof, ever — no fake testimonials, no implied clients that don't exist, no invented review counts. The three portfolio pieces stay labeled as concepts. Given that constraint, here's what's actually available, ranked by trust-per-effort for these three personas (high-impact/low-effort first):

1. **A concrete risk-reversing offer (free homepage preview before any commitment).** *Effort*: low — it's a line of copy plus a workflow change, not a new deliverable system. *Trust-per-effort*: highest. This single move answers "will I get ripped off" directly, because there's no money at risk on the first step. It's the strongest lever available precisely because it doesn't require any fabricated history — it's a forward-looking promise, not a past-performance claim.
2. **Plain-language pricing guidance.** *Effort*: low — a short section with ranges. *Trust-per-effort*: very high. Removes the single most common silent-exit trigger (see principle #2) and costs nothing to be honest about.
3. **Showing face and location.** *Effort*: already have the portrait; needs the location added in copy/metadata. *Trust-per-effort*: high. A named person, in a real place, is inherently more trustworthy to a wary local buyer than an anonymous "available worldwide" freelancer — and it's just true, no fabrication involved.
4. **A "what you get" deliverables list.** *Effort*: low-medium — needs to be written honestly (e.g., "a mobile-friendly site, a working contact form, help pointing your domain") without overpromising like "SEO guaranteed." *Trust-per-effort*: high. Concrete deliverables read as more trustworthy than adjectives ("motion-driven," "art-directed").
5. **Transparent process (numbered steps, named endpoint).** *Effort*: medium — needs real thought about what the actual steps are, since there's no established client workflow yet to describe. *Trust-per-effort*: high, but slightly lower than 1–4 because it takes more work to make believable and specific rather than generic.
6. **A real, phone-friendly contact path.** *Effort*: low (add a phone number/text link) but requires the user's actual willingness to be reachable by phone, which is a personal decision, not just a copy decision. *Trust-per-effort*: high for Ray specifically, moderate overall — flag this for the user to confirm before Phase 3, since it's the one item here that isn't purely a copy change.
7. **Speed and quality of the site itself as proof of skill.** *Effort*: mostly already true (hand-built, no bloat) but currently not stated as a selling point. *Trust-per-effort*: medium — it's a legitimate signal ("this loads instantly, imagine yours") but it's an inference the buyer has to make themselves; it doesn't defuse a named fear the way 1–4 do, it just reinforces "can this guy do it," which was already the site's strongest area.
8. **Honest framing of the concept projects as concepts.** *Effort*: already done. *Trust-per-effort*: this is a floor requirement, not a lever — keep it, but don't expect it to actively build trust beyond preventing a mistrust it could otherwise cause if it read as deceptive.

**Explicitly rejected as too costly-for-trust or borderline dishonest, even though listed as "to evaluate" in the brief**: nothing on the evaluation list requires rejection — all eight items above are legitimate and available without fabrication. The only caution is #6 (phone number) is a personal-boundary decision for the user, not a pure content decision, and #7 shouldn't be oversold as if speed alone answers the price/trust objections it doesn't touch.

---

## Summary for Phase 2

The site's core problem isn't craft — the work is genuinely good and, by coincidence, already speaks to this exact audience's businesses. The problem is that the first screen talks to other designers, the middle of the page never answers price or process, and the contact block treats "email me" as if it carries no risk for a first-time buyer who's never hired anyone like this before. Phase 2 should prioritize, in order: hero reframing (principle #1, #3), a new pricing/process section (principle #2, #5, #6 with signal #1 and #2 from the honesty section), and a contact block redesign (principle #4, #7, plus honesty signal #6, pending the user's confirmation on publishing a phone number).
