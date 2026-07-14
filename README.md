# uiskills

A curated collection of **85 Claude Code skills** for UI/design engineering

Every skill is installed under `.claude/skills/` and works automatically in Claude Code (and other agents via the [`skills`](https://github.com/vercel-labs/skills) CLI). `skills-lock.json` pins every source repo and version.

## Installing / updating

```bash
# add a single skill
npx skills add <github-repo> --skill <name>

# restore everything from the lockfile
npx skills experimental_install
```

## Notes

- Skills were installed with `--copy` (real files, committed to this repo) targeting Claude.
- Skills run with full agent permissions — review before use.
- `rams` (from `ui-skills.com`) is **not** included: its source repo `github.com/rams/rams-ai` returns 404.
- A few site entries are facets of one skill (e.g. the 18 `pbakaus` entries all live inside `impeccable`; AccessLint's 5 map to `audit`/`diff`/`scan`), so the real installable count (85) is lower than the site's listing count.

## Skills (85)

- **12-principles-of-animation** — Audit animation code against Disney's 12 principles adapted for web. Use when reviewing motion, implementing animations,
- **agent-browser** — Browser automation CLI for AI agents. Use when the user needs to interact with websites, including navigating pages, fil
- **antfu** — Anthony Fu's opinionated tooling and conventions for JavaScript/TypeScript projects. Use when setting up new projects, c
- **audit** — Find and fix WCAG 2.2 accessibility issues. Two modes — report (sweep a codebase or page, produce a prioritized writte
- **baseline-ui** — Validates animation durations, enforces typography scale, checks component accessibility, and prevents layout anti-patte
- **bencium-innovative-ux-designer** — Create distinctive, production-grade frontend interfaces with high design quality. Use this skill when the user asks to 
- **budge** — Use when making single-property CSS or Tailwind visual changes in Next.js App Router projects. Presents a floating contr
- **canvas-design** — Create beautiful visual art in .png and .pdf documents using design philosophy. You should use this skill when the user 
- **create-adaptable-composable** — Create a library-grade Vue composable that accepts maybe-reactive inputs (MaybeRef / MaybeRefOrGetter) so callers can pa
- **design-lab** — Conduct design interviews, generate five distinct UI variations in a temporary design lab, collect feedback, and produce
- **design-taste-frontend** — Anti-slop frontend skill for landing pages, portfolios, and redesigns. The agent reads the brief, infers the right desig
- **diff** — "Diff a live page's accessibility violations against a baseline — by default compares uncommitted changes (stash-based
- **emil-design-eng** — This skill encodes Emil Kowalski's philosophy on UI polish, component design, animation decisions, and the invisible det
- **fixing-accessibility** — Audit and fix HTML accessibility issues including ARIA labels, keyboard navigation, focus management, color contrast, an
- **fixing-metadata** — >
- **fixing-motion-performance** — Audit and fix animation performance issues including layout thrashing, compositor properties, scroll-linked motion, and 
- **frontend-design** — Guidance for distinctive, intentional visual design when building new UI or reshaping an existing one. Helps with aesthe
- **frontend-slides** — Create stunning, animation-rich HTML presentations from scratch or by converting PowerPoint files. Use when the user wan
- **frontend-ui-engineering** — Builds production-quality UIs. Use when building or modifying user-facing interfaces. Use when creating components, impl
- **full-output-enforcement** — Overrides default LLM truncation behavior. Enforces complete code generation, bans placeholder patterns, and handles tok
- **generating-sounds-with-ai** — Audit Web Audio API code for sound synthesis best practices. Use when reviewing procedural audio, implementing UI sounds
- **gpt-taste** — Elite UX/UI & Advanced GSAP Motion Engineer. Enforces Python-driven true randomization for layout variance, strict AIDA 
- **high-end-visual-design** — Teaches the AI to design like a high-end agency. Defines the exact fonts, spacing, shadows, card structures, and animati
- **impeccable** — Use when the user wants to design, redesign, shape, critique, audit, polish, clarify, distill, harden, optimize, adapt, 
- **industrial-brutalist-ui** — Raw mechanical interfaces fusing Swiss typographic print with military terminal aesthetics. Rigid grids, extreme type sc
- **interaction-design** — Design and implement microinteractions, motion design, transitions, and user feedback patterns. Use when adding polish t
- **interface-design** — This skill is for interface design — dashboards, admin panels, apps, tools, and interactive products. NOT for marketin
- **make-interfaces-feel-better** — Design engineering principles for making interfaces feel polished. Use when building UI components, reviewing frontend c
- **mastering-animate-presence** — Audit Motion/Framer Motion code for AnimatePresence best practices. Use when reviewing exit animations, modals, or prese
- **minimalist-ui** — Clean editorial-style interfaces. Warm monochrome palette, typographic contrast, flat bento grids, muted pastels. No gra
- **morphing-icons** — Build icon components where any icon morphs into any other through SVG line transformation. Use when asked to "create mo
- **next-best-practices** — Next.js best practices - file conventions, RSC boundaries, data patterns, async APIs, metadata, error handling, route ha
- **next-cache-components** — Next.js 16 Cache Components - PPR, use cache directive, cacheLife, cacheTag, updateTag
- **next-upgrade** — Upgrade Next.js to the latest version following official migration guides and codemods
- **nuxt** — Nuxt full-stack Vue framework with SSR, auto-imports, and file-based routing. Use when working with Nuxt apps, server ro
- **oklch-skill** — OKLCH color space for web projects. Convert hex/rgb/hsl to oklch, generate palettes, check contrast, handle gamut bounda
- **pinia** — Pinia official Vue state management library, type-safe and extensible. Use when defining stores, working with state/gett
- **playwright-cli** — Automate browser interactions, test web pages and work with Playwright tests.
- **pnpm** — Node.js package manager with strict dependency resolution. Use when running pnpm specific commands, configuring workspac
- **pseudo-elements** — Audit CSS for pseudo-element best practices and View Transitions API usage. Use when reviewing hover effects, decorative
- **react-doctor** — Use when finishing a feature, fixing a bug, before committing React code, or when the user types `/doctor`, asks to scan
- **react-native-best-practices** — Provides React Native performance optimization guidelines for FPS, TTI, bundle size, memory leaks, re-renders, and anima
- **react-router-framework-mode** — Build full-stack React applications using React Router's framework mode. Use when configuring routes, working with loade
- **redesign-existing-projects** — Upgrades existing websites and apps to premium quality. Audits current design, identifies generic AI patterns, and appli
- **remotion-best-practices** — Best practices for Remotion - Video creation in React
- **scan** — "Audit a live page for accessibility issues and locate each violation precisely — pass a URL, a config target name (e.
- **shadcn** — Manages shadcn components and projects — adding, searching, fixing, debugging, styling, and composing UI. Provides pro
- **slidev** — Create and present web-based slidedecks for developers using Slidev with Markdown, Vue components, code highlighting, an
- **sounds-on-the-web** — Audit UI code for audio feedback best practices. Use when reviewing sound implementation, checking audio UX decisions, o
- **stitch-design-taste** — Semantic Design System Skill for Google Stitch. Generates agent-friendly DESIGN.md files that enforce premium, anti-gene
- **svelte-code-writer** — CLI tools for Svelte 5 documentation lookup and code analysis. MUST be used whenever creating, editing or analyzing any 
- **swiftui-ui-patterns** — Best practices and example-driven guidance for building SwiftUI views and components, including navigation hierarchies, 
- **swiss-design** — Apply a Swiss International Style design system using Tailwind CSS. Use when asked to style a webpage, clean up a UI, ap
- **threejs-animation** — Three.js animation - keyframe animation, skeletal animation, morph targets, animation mixing. Use when animating objects
- **threejs-fundamentals** — Three.js scene setup, cameras, renderer, Object3D hierarchy, coordinate systems. Use when setting up 3D scenes, creating
- **threejs-geometry** — Three.js geometry creation - built-in shapes, BufferGeometry, custom geometry, instancing. Use when creating 3D shapes, 
- **threejs-interaction** — Three.js interaction - raycasting, controls, mouse/touch input, object selection. Use when handling user input, implemen
- **threejs-lighting** — Three.js lighting - light types, shadows, environment lighting. Use when adding lights, configuring shadows, setting up 
- **threejs-loaders** — Three.js asset loading - GLTF, textures, images, models, async patterns. Use when loading 3D models, textures, HDR envir
- **threejs-materials** — Three.js materials - PBR, basic, phong, shader materials, material properties. Use when styling meshes, working with tex
- **threejs-postprocessing** — Three.js post-processing - EffectComposer, bloom, DOF, screen effects. Use when adding visual effects, color grading, bl
- **threejs-shaders** — Three.js shaders - GLSL, ShaderMaterial, uniforms, custom effects. Use when creating custom visual effects, modifying ve
- **threejs-textures** — Three.js textures - texture types, UV mapping, environment maps, texture settings. Use when working with images, UV coor
- **to-spring-or-not-to-spring** — Audit animation code for correct timing function selection. Use when reviewing motion implementations, debugging animati
- **transitions-dev** — Production-ready CSS transitions for web apps. Use when implementing notification badges, dropdowns, modals, panel revea
- **tsdown** — Bundle TypeScript and JavaScript libraries with blazing-fast speed powered by Rolldown. Use when building libraries, gen
- **turborepo** — |
- **ui-ux-pro-max** — "UI/UX design intelligence for web and mobile. Includes 50+ styles, 161 color palettes, 57 font pairings, 161 product ty
- **unocss** — UnoCSS instant atomic CSS engine, superset of Tailwind CSS. Use when configuring UnoCSS, writing utility rules, shortcut
- **vercel-react-best-practices** — React and Next.js performance optimization guidelines from Vercel Engineering. This skill should be used when writing, r
- **vite** — Vite build tool configuration, plugin API, SSR, and Vite 8 Rolldown migration. Use when working with Vite projects, vite
- **vitepress** — VitePress static site generator powered by Vite and Vue. Use when building documentation sites, configuring themes, or w
- **vitest** — Vitest fast unit testing framework powered by Vite with Jest-compatible API. Use when writing tests, mocking, configurin
- **vue** — Vue 3 Composition API, script setup macros, reactivity system, and built-in components. Use when writing Vue SFCs, defin
- **vue-best-practices** — MUST be used for Vue.js tasks. Strongly recommends Composition API with `<script setup>` and TypeScript as the standard 
- **vue-debug-guides** — Vue 3 debugging and error handling for runtime errors, warnings, async failures, and SSR/hydration issues. Use when diag
- **vue-jsx-best-practices** — JSX syntax in Vue (e.g., class vs className, JSX plugin config).
- **vue-options-api-best-practices** — "Vue 3 Options API style (data(), methods, this context). Each reference shows Options API solution only."
- **vue-pinia-best-practices** — "Pinia stores, state management patterns, store setup, and reactivity with stores."
- **vue-router-best-practices** — "Vue Router 4 patterns, navigation guards, route params, and route-component lifecycle interactions."
- **vue-testing-best-practices** — Use for Vue.js testing. Covers Vitest, Vue Test Utils, component testing, mocking, testing patterns, and Playwright for 
- **vueuse-functions** — Apply VueUse composables where appropriate to build concise, maintainable Vue.js / Nuxt features.
- **wcag-audit-patterns** — Conduct WCAG 2.2 accessibility audits with automated testing, manual verification, and remediation guidance. Use when au
- **web-design-guidelines** — Review UI code for Web Interface Guidelines compliance. Use when asked to "review my UI", "check accessibility", "audit 
- **web-quality-audit** — Comprehensive web quality audit covering performance, accessibility, SEO, and best practices. Use when asked to "audit m
