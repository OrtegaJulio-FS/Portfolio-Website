# From Web Designer to Web Artist

## The core shift

Generic web design optimizes for "does this work and look clean." Web art optimizes for "does this make someone feel something, remember it, or want to touch it." The gap between the two is rarely skill — it's usually one of these three things missing: a point of view, a signature interaction, or the willingness to break a grid on purpose.

A useful test for any project going forward: if you swapped the logo and copy, could this be any brand's site? If yes, it's still a deliverable, not art.

## What actually separates "art" sites from generic ones

**They have one weird idea, not ten safe ones.** Sites like Bruno Simon's portfolio (a drivable 3D car you steer through his work) or Jeton's fintech site (serious financial product, but navigated through hands-on scroll-based movement) commit hard to a single conceit instead of stacking trendy components. Pick one unusual idea per project and let it run through the whole site — navigation, transitions, even error states.

**Motion is authored, not templated.** The difference between a fade-in-on-scroll and something that feels alive is choreography: staggered timing, easing curves that overshoot or settle unevenly, elements that respond to cursor position or scroll velocity rather than just scroll position. This is where GSAP (specifically ScrollTrigger) earns its reputation — it lets you script motion like a director blocks a scene instead of applying a canned "animate on scroll" library.

**Depth and texture over flat vectors.** WebGL/Three.js shader backgrounds, grain/noise overlays, distortion on hover, and cursor-driven parallax all push a site from "print layout on a screen" toward something that feels dimensional and tactile. You don't need full 3D — even a subtle canvas-based grain texture or a shader gradient that reacts to mouse movement changes the whole feel.

**Typography as a visual instrument, not just a vessel for words.** Oversized, kinetic, or distorted type; text that reveals character-by-character; type that bends around cursor position — these treat words as shapes with weight, not just content to be read quickly.

**Custom cursors and micro-interactions as signature, not decoration.** A custom cursor that morphs based on what it's hovering, magnetic buttons that pull toward the pointer, hover states that reveal a second layer of content — these are small, but they're often what people screen-record and share.

**Sound and rhythm, used sparingly.** A handful of award-winning sites use subtle sound design (a click, a whoosh on transition) synced to motion. Riskier and easy to overdo, but almost nobody does it, which is exactly why it stands out when done well.

**Transitions between pages/sections are treated as their own design problem.** Studios like Active Theory and Resn choreograph page transitions like theatrical scene changes rather than defaulting to an instant cut or a generic fade — this is one of the highest-leverage places to inject a signature.

## A working process for making something that isn't generic

1. Start from a feeling or metaphor, not a layout. Before opening Figma, write one sentence: "this should feel like ___." (Weightless, claustrophobic, glitchy, ceremonial, tactile — anything specific.) Every decision downstream should serve that sentence.
2. Design the one moment first. Pick the single interaction or transition that will define the site, prototype that in code before laying out full pages. If that moment isn't interesting, no amount of grid polish will save the project.
3. Break the grid exactly once, deliberately. A full page of intentional rule-breaking reads as chaos; a system with one calculated violation reads as confident.
4. Build motion with a real animation library, not CSS transitions alone. GSAP + ScrollTrigger (or Framer Motion in React) gives you the control needed for choreography rather than uniform fades.
5. Add one layer of texture. Grain, noise, a subtle shader, or a distortion effect on hover/scroll — pick one, not all four.
6. Cut anything that's there because "sites like this usually have it." Sliders, generic stock-photo heroes, and stock icon grids are the fastest way back to generic.

## Tools worth learning

- **GSAP + ScrollTrigger** — the standard for scroll-driven choreography and complex sequenced animation; this is what most award-winning motion work is actually built on.
- **Three.js** — WebGL 3D scenes, product visualizers, drivable/explorable environments.
- **Shader-driven backgrounds** (raw GLSL, or approachable wrappers like Shader Park / Paper Shaders) — for gradient distortion, liquid, grain, and generative backgrounds without needing full 3D expertise.
- **Lenis** — smooth-scroll library that most of these "buttery" scrolling sites use under the hood.
- **Barba.js / native View Transitions API** — for choreographed page-to-page transitions instead of hard reloads.
- **Rive or Lottie** — for designed (not coded) vector animation that's lighter than full WebGL.
- **Codrops (tympanus.net/codrops)** — the single best source of open-source code tutorials for exactly this kind of work; most "how did they do that" effects trace back to a Codrops writeup.

## Where to study, regularly

- **Awwwards** (awwwards.com), especially the [Experimental](https://www.awwwards.com/websites/experimental/) category — filter by "experimental" rather than the general Site of the Day feed, since the general feed skews toward polished-but-safe agency sites.
- **FWA** (thefwa.com) — historically the home of the weirder, more interactive/experimental end of the web.
- **Studio sites as case studies**: Active Theory, Resn, Locomotive, and Bruno Simon's personal portfolio are worth dissecting frame-by-frame (open dev tools, watch the network tab, read the page source) — not to copy, but to reverse-engineer *how* a specific moment was built.
- **Codrops** — for the actual code behind shader/scroll/WebGL effects you admire.

## The honest caveat

Every one of these techniques can also make a site worse — slower, less accessible, harder to navigate. The sites that read as "art" and still work are the ones where the flourish serves one idea and everything else gets out of its way. Restraint around *where* you spend the unusual is what separates "artist" from "over-decorated." Test on real connections and with keyboard/screen-reader navigation before shipping anything WebGL-heavy.

---

## Sources

- [Awwwards — Experimental Websites](https://www.awwwards.com/websites/experimental/)
- [Awwwards — Winning Websites](https://www.awwwards.com/websites/)
- [Codrops — Building a Scroll-Revealed WebGL Gallery with GSAP, Three.js, Astro and Barba.js](https://tympanus.net/codrops/2026/02/02/building-a-scroll-revealed-webgl-gallery-with-gsap-three-js-astro-and-barba-js/)
- [Codrops — WebGL for Designers: Creating Interactive, Shader-Driven Graphics Directly in the Browser](https://tympanus.net/codrops/2026/03/04/webgl-for-designers-creating-interactive-shader-driven-graphics-directly-in-the-browser/)
- [Codrops — WebGL tag archive](https://tympanus.net/codrops/tag/webgl/)
- [Harley Oliver — 7 Inspiring Websites Of The Day To Explore In 2026](https://www.harleyoliver.com/blog/7-inspiring-websites-of-the-day-to-explore-in-2026)
- [Really Good Designs — Top 10 Web Design Trends 2026](https://reallygooddesigns.com/web-design-trends-2026/)
- [positioniseverything.net — 19 Best Web Design Portfolio Examples 2026](https://www.positioniseverything.net/19-best-web-design-portfolio-examples-2026-update/)
