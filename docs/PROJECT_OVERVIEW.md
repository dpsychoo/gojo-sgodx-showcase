# Gojo SGODX — Project overview

## Project context

Gojo SGODX is an unofficial fan-oriented browser experience presented as five full-screen scenes. It is a creative frontend case study, not a full-stack product. The current deployed implementation adapts a pre-existing HTML base. The base author's identity, source repository, and redistribution terms have not been verified, so this overview describes observable product behavior and documented stack choices without exposing private implementation details.

## Experience flow

1. A cinematic SGODX preloader introduces the experience.
2. Visitors enter a five-scene sequence focused on Satoru Gojo.
3. Previous, next, and direct scene controls move through the experience.
4. Scene transitions coordinate typography, visuals, and silent video backgrounds.
5. Pointer and card interactions provide additional visual feedback; a sound control uses synthesized browser audio.

## Technology inventory

| Concern | Verified technology |
| --- | --- |
| Document and layout | HTML5, CSS |
| Interaction and navigation | Vanilla JavaScript |
| Timeline and motion | GSAP 3.15.0 via pinned CDN URL and SRI |
| Realtime visual effects | Canvas, WebGL and GLSL |
| Audio | Web Audio API oscillator synthesis |
| Local image variants | WebP |
| Background motion media | Silent H.264 MP4 |
| Development browser tests | Playwright Test 1.64.1 |

External typefaces use Google Fonts CSS and the production notices record their Open Font License terms. This case-study page does not load those fonts or any external JavaScript.

## Scope and implementation ownership

The production project includes SGODX customizations and technical improvements, including scene interaction, optimized media variants, fallbacks, accessibility controls, and test coverage. It also retains an inherited base and third-party material whose complete chain of rights has not been established. The public case study does not contain production code or separate media assets. It includes one owner-approved Gojo/SGODX cover; other production captures are excluded.

The separately hosted demo can be explored at <https://gojo-sgodx.vercel.app/>. A link does not grant permission to copy or redistribute the demo's contents.

## Verification notes

The source project has a Playwright suite for the five-scene experience, responsive viewports, and interaction behavior. Historical results belong to the source project's own test records and are not represented as a fresh run of this presentation repository. The static case-study page introduces no npm dependencies or browser-side library requirements.

## Distribution notes

- No production source or private backup is included.
- No additional production captures are distributed while their depicted artwork and footage remain uncleared.
- The owner-approved Gojo/SGODX cover is included as a WebP visual; separate production media assets are not bundled.
- See [NOTICE.md](../NOTICE.md) for fan-work and reuse notices.
