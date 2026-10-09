# Design Skills

A collection of 94 Claude Code skills for UI, visual design, branding, animation, 3D, mobile UI and AI video, grouped by folder.

## Install

Copy whichever skill folders you want into `~/.claude/skills/` (personal) or `.claude/skills/` (one project):

```sh
cp -R 05-web-animation/gsap-core ~/.claude/skills/
# or everything:
for d in */*/; do cp -R "${d%/}" ~/.claude/skills/; done
```

Each folder contains a `SKILL.md` (Claude loads it automatically when relevant) plus any references/scripts it needs.

## [Design Direction & Taste](01-design-direction-and-taste/) — 12

| Skill | What it does |
|---|---|
| [`frontend-design`](01-design-direction-and-taste/frontend-design/) | Distinctive, intentional visual direction for new or reshaped UI — typography, aesthetic, avoiding generic looks. |
| [`design-taste-frontend`](01-design-direction-and-taste/design-taste-frontend/) | Anti-"AI slop" frontend skill (v2): infers a design direction from the brief and ships landing pages/portfolios that look designed. |
| [`design-taste-frontend-v1`](01-design-direction-and-taste/design-taste-frontend-v1/) | The original v1 taste skill, kept for projects that rely on its exact behaviour. |
| [`gpt-taste`](01-design-direction-and-taste/gpt-taste/) | Editorial UX/UI + GSAP motion rules: randomized layout variance, AIDA page structure, wide editorial type. |
| [`high-end-visual-design`](01-design-direction-and-taste/high-end-visual-design/) | Design like a high-end agency: exact fonts, spacing, shadows, card structures and animations that feel expensive. |
| [`minimalist-ui`](01-design-direction-and-taste/minimalist-ui/) | Clean editorial interfaces: warm monochrome, typographic contrast, flat bento grids, no gradients or heavy shadows. |
| [`industrial-brutalist-ui`](01-design-direction-and-taste/industrial-brutalist-ui/) | Raw mechanical UI: Swiss print typography meets military terminal — rigid grids, extreme type contrast. |
| [`modern-web-design`](01-design-direction-and-taste/modern-web-design/) | Current web design trends, principles and implementation patterns. |
| [`redesign-existing-projects`](01-design-direction-and-taste/redesign-existing-projects/) | Audits an existing site/app, finds generic patterns, and upgrades it to premium quality without breaking it. |
| [`impeccable`](01-design-direction-and-taste/impeccable/) | Large design toolkit: design, critique, audit, polish, distill, harden, animate, colorize and more on any UI. |
| [`stitch-design-taste`](01-design-direction-and-taste/stitch-design-taste/) | Generates DESIGN.md files for Google Stitch that enforce premium, non-generic UI standards. |
| [`apple-design`](01-design-direction-and-taste/apple-design/) | Apple's interface and fluid physical-motion approach translated for the web (springs, gestures, drag). |

## [UI Systems & Styling](02-ui-systems-and-styling/) — 10

| Skill | What it does |
|---|---|
| [`design`](02-ui-systems-and-styling/design/) | All-round design skill: brand identity, tokens, UI styling, logo generation, corporate identity deliverables. |
| [`design-system`](02-ui-systems-and-styling/design-system/) | Token architecture (primitive → semantic → component), CSS variables, spacing/type scales, component specs. |
| [`ui-styling`](02-ui-systems-and-styling/ui-styling/) | Accessible UIs with shadcn/ui (Radix + Tailwind) and Tailwind utility-first styling. |
| [`ui-ux-pro-max`](02-ui-systems-and-styling/ui-ux-pro-max/) | Searchable UI/UX database: styles, colour palettes, font pairings, product types, UX guidelines for web + mobile. |
| [`theme-factory`](02-ui-systems-and-styling/theme-factory/) | 10 preset colour/font themes to style slides, docs, reports and HTML pages, or generate a new one. |
| [`web-design-guidelines`](02-ui-systems-and-styling/web-design-guidelines/) | Reviews UI code against Web Interface Guidelines (accessibility, UX, best practice). |
| [`web-artifacts-builder`](02-ui-systems-and-styling/web-artifacts-builder/) | Builds multi-component HTML artifacts with React, Tailwind and shadcn/ui. |
| [`mobile-native`](02-ui-systems-and-styling/mobile-native/) | CSS and meta-tag fixes that make a web app feel installed/native on a phone. |
| [`shadcn`](02-ui-systems-and-styling/shadcn/) | shadcn/ui CLI, component installation, composition, custom registries and theming. |
| [`a11y-debugging`](02-ui-systems-and-styling/a11y-debugging/) | Accessibility audits and debugging in Chrome DevTools, based on web.dev guidelines. |

## [Brand & Graphics](03-brand-and-graphics/) — 11

| Skill | What it does |
|---|---|
| [`brand`](03-brand-and-graphics/brand/) | Brand voice, visual identity, messaging frameworks and brand consistency. |
| [`brand-guidelines`](03-brand-and-graphics/brand-guidelines/) | Applies Anthropic's official brand colours and typography (good template for your own brand skill). |
| [`brandkit`](03-brand-and-graphics/brandkit/) | Generates premium brand-guideline boards, logo systems and identity decks as images. |
| [`banner-design`](03-brand-and-graphics/banner-design/) | Banners for social, ads, website heroes and print, with multiple art-direction options. |
| [`canvas-design`](03-brand-and-graphics/canvas-design/) | Posters and visual art as .png/.pdf from a written design philosophy (ships with fonts). |
| [`algorithmic-art`](03-brand-and-graphics/algorithmic-art/) | Generative art with p5.js, seeded randomness and interactive parameters. |
| [`slides`](03-brand-and-graphics/slides/) | Strategic HTML presentations with Chart.js, design tokens and slide copywriting formulas. |
| [`unsplash`](03-brand-and-graphics/unsplash/) | Search and fetch Unsplash photos with correct attribution. |
| [`image`](03-brand-and-graphics/image/) | Create, generate, edit and optimize marketing images: blog heroes, social graphics, product shots. |
| [`ad-creative-generation`](03-brand-and-graphics/ad-creative-generation/) | On-brand ad creatives (visuals + copy) for Google, Meta and other ad platforms. |
| [`slack-gif-creator`](03-brand-and-graphics/slack-gif-creator/) | Animated GIFs sized and optimized for Slack. |

## [AI Image Design References](04-ai-image-design-references/) — 3

| Skill | What it does |
|---|---|
| [`image-to-code`](04-ai-image-design-references/image-to-code/) | Generate a design image first, analyze it, then implement the website to match it. |
| [`imagegen-frontend-web`](04-ai-image-design-references/imagegen-frontend-web/) | Generates premium, conversion-aware website design reference images. |
| [`imagegen-frontend-mobile`](04-ai-image-design-references/imagegen-frontend-mobile/) | Generates premium app-native mobile screen concepts and flows (iOS/Android). |

## [Web Animation](05-web-animation/) — 23

| Skill | What it does |
|---|---|
| [`gsap-core`](05-web-animation/gsap-core/) | Official GSAP: core API — to/from/fromTo, easing, stagger, matchMedia, reduced motion. |
| [`gsap-timeline`](05-web-animation/gsap-timeline/) | Official GSAP: timelines, position parameter, nesting, playback. |
| [`gsap-scrolltrigger`](05-web-animation/gsap-scrolltrigger/) | GSAP ScrollTrigger: scroll-driven animation, pinning, scrubbing. |
| [`gsap-plugins`](05-web-animation/gsap-plugins/) | Official GSAP: plugins — Flip, Draggable, SplitText, ScrollSmoother, SVG, physics. |
| [`gsap-react`](05-web-animation/gsap-react/) | Official GSAP: React/Next.js — useGSAP, refs, context, cleanup. |
| [`gsap-frameworks`](05-web-animation/gsap-frameworks/) | Official GSAP: Vue, Svelte and other frameworks — lifecycle and cleanup. |
| [`gsap-performance`](05-web-animation/gsap-performance/) | Official GSAP: performance — transforms, avoiding layout thrash, batching. |
| [`gsap-utils`](05-web-animation/gsap-utils/) | Official GSAP: gsap.utils helpers — clamp, mapRange, interpolate, snap, wrap. |
| [`motion-framer`](05-web-animation/motion-framer/) | Motion (Framer Motion) for React: variants, gestures, layout animations. |
| [`animejs`](05-web-animation/animejs/) | Anime.js: timelines, staggers, SVG morphing, keyframes. |
| [`react-spring-physics`](05-web-animation/react-spring-physics/) | Physics-based animation with React Spring and Popmotion. |
| [`lottie-animations`](05-web-animation/lottie-animations/) | Lottie (After Effects JSON) animations in web and React. |
| [`rive-interactive`](05-web-animation/rive-interactive/) | Rive state-machine vector animations with runtime interactivity. |
| [`barba-js`](05-web-animation/barba-js/) | Barba.js page transitions between website pages. |
| [`locomotive-scroll`](05-web-animation/locomotive-scroll/) | Locomotive Scroll smooth scrolling, parallax and viewport detection. |
| [`scroll-reveal-libraries`](05-web-animation/scroll-reveal-libraries/) | Simple scroll-triggered reveals with AOS for marketing/landing pages. |
| [`animated-component-libraries`](05-web-animation/animated-component-libraries/) | Ready-made animated React components from Magic UI and React Bits. |
| [`vercel-react-view-transitions`](05-web-animation/vercel-react-view-transitions/) | React View Transition API for smooth native-feeling page/state transitions. |
| [`remotion-motion-graphics`](05-web-animation/remotion-motion-graphics/) | Motion-graphics videos built in React with Remotion. |
| [`expo-animation`](05-web-animation/expo-animation/) | Animations in React Native and Expo, decided in the order that matters for performance. |
| [`remotion-best-practices`](05-web-animation/remotion-best-practices/) | Router/entry point for all the Remotion video skills. |
| [`remotion-markup`](05-web-animation/remotion-markup/) | Remotion content, animation and effects best practices. |
| [`remotion-captions`](05-web-animation/remotion-captions/) | Transcribe, display and animate captions in Remotion videos. |

## [3D & WebGL](06-3d-and-webgl/) — 11

| Skill | What it does |
|---|---|
| [`threejs-webgl`](06-3d-and-webgl/threejs-webgl/) | Three.js: 3D scenes, WebGL/WebGPU, product configurators. |
| [`react-three-fiber`](06-3d-and-webgl/react-three-fiber/) | React Three Fiber: declarative Three.js scenes in React. |
| [`babylonjs-engine`](06-3d-and-webgl/babylonjs-engine/) | Babylon.js real-time 3D engine for web experiences and games. |
| [`playcanvas-engine`](06-3d-and-webgl/playcanvas-engine/) | PlayCanvas WebGL/WebGPU engine with entity-component architecture. |
| [`pixijs-2d`](06-3d-and-webgl/pixijs-2d/) | PixiJS fast 2D WebGL rendering: particles, interactive graphics. |
| [`aframe-webxr`](06-3d-and-webgl/aframe-webxr/) | A-Frame: HTML-based 3D, VR and AR (WebXR) experiences. |
| [`spline-interactive`](06-3d-and-webgl/spline-interactive/) | Spline: no-code 3D scene design and web export. |
| [`lightweight-3d-effects`](06-3d-and-webgl/lightweight-3d-effects/) | Decorative pseudo-3D with Zdog, Vanta.js and Vanilla-Tilt. |
| [`web3d-integration-patterns`](06-3d-and-webgl/web3d-integration-patterns/) | Combining Three.js, GSAP, R3F, Motion and React Spring in one 3D site. |
| [`blender-web-pipeline`](06-3d-and-webgl/blender-web-pipeline/) | Blender → glTF export and optimization for the web. |
| [`substance-3d-texturing`](06-3d-and-webgl/substance-3d-texturing/) | Adobe Substance 3D Painter PBR materials and texture export. |

## [Mobile Native UI](07-mobile-native-ui/) — 9

| Skill | What it does |
|---|---|
| [`expo-design-system`](07-mobile-native-ui/expo-design-system/) | Design-token theme system (colour, spacing, type, radius, motion) inside an Expo app. |
| [`expo-native-ui`](07-mobile-native-ui/expo-native-ui/) | Native-feeling Expo screens: Apple HIG, semantic colours, SF Symbols, native controls. |
| [`expo-ui`](07-mobile-native-ui/expo-ui/) | @expo/ui: real SwiftUI on iOS and Jetpack Compose on Android. |
| [`mobile-android-design`](07-mobile-native-ui/mobile-android-design/) | Material Design 3 and Jetpack Compose patterns for Android. |
| [`compose-animations`](07-mobile-native-ui/compose-animations/) | Jetpack Compose motion: enter/exit, property, colour and size transitions. |
| [`adaptive`](07-mobile-native-ui/adaptive/) | Make an Android app's UI adapt to phones, tablets, foldables and desktop. |
| [`edge-to-edge`](07-mobile-native-ui/edge-to-edge/) | Migrate a Jetpack Compose app to adaptive edge-to-edge layout. |
| [`styles`](07-mobile-native-ui/styles/) | Jetpack Compose Styles API integration. |
| [`ios-accessibility`](07-mobile-native-ui/ios-accessibility/) | SwiftUI/UIKit accessibility: VoiceOver, Dynamic Type, focus, contrast. |

## [AI Video Prompts](08-ai-video-prompts/) — 15

| Skill | What it does |
|---|---|
| [`01-cinematic`](08-ai-video-prompts/01-cinematic/) | Cinematic film-style video prompts (Seedance 2.0 / Higgsfield). |
| [`02-3d-cgi`](08-ai-video-prompts/02-3d-cgi/) | 3D CGI / rendered-look video prompts. |
| [`03-cartoon`](08-ai-video-prompts/03-cartoon/) | Cartoon and animation-style video prompts. |
| [`04-comic-to-video`](08-ai-video-prompts/04-comic-to-video/) | Turn comic panels, manga and storyboards into animated video. |
| [`05-fight-scenes`](08-ai-video-prompts/05-fight-scenes/) | Action and fight-scene video prompts. |
| [`06-motion-design-ad`](08-ai-video-prompts/06-motion-design-ad/) | Motion-design ads for software/tech products (SaaS promos, UI showcases). |
| [`07-ecommerce-ad`](08-ai-video-prompts/07-ecommerce-ad/) | E-commerce product ad video prompts. |
| [`08-anime-action`](08-ai-video-prompts/08-anime-action/) | Anime-style video prompts. |
| [`09-product-360`](08-ai-video-prompts/09-product-360/) | 360° product showcase video prompts. |
| [`10-music-video`](08-ai-video-prompts/10-music-video/) | Music video and beat-synced visual prompts. |
| [`11-social-hook`](08-ai-video-prompts/11-social-hook/) | Scroll-stopping social media hook videos. |
| [`12-brand-story`](08-ai-video-prompts/12-brand-story/) | Brand storytelling / narrative video prompts. |
| [`13-fashion-lookbook`](08-ai-video-prompts/13-fashion-lookbook/) | Fashion lookbook and model showcase video prompts. |
| [`14-food-beverage`](08-ai-video-prompts/14-food-beverage/) | Food and beverage commercial video prompts. |
| [`15-real-estate`](08-ai-video-prompts/15-real-estate/) | Real estate, architecture and interior showcase video prompts. |

## Credits

These skills come from various open-source authors (Anthropic, GreenSock, Expo, Google/Android, Vercel, and community authors). Licence files that shipped with a skill are kept in its folder; check them before redistributing further.
