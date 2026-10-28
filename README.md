# Gaznil's stack

Everything I use with Claude Code and Codex: skills, plugins, connectors, libraries and tools, sorted by job.
Purpose: start any new project without researching again, and rebuild my setup on a new PC.

Snapshot: 28 Oct 2026. 315 skills · 10 plugins · 30 connectors.

- **Public (this repo):** what each thing is, where it comes from, how to install it.
- **Private (`gaznil/stack-backup`):** copies of skills that have no public source, plus my Claude rules and
  project notes. Keys, passwords and login files are never copied.

## Pick a stack by job

| I'm making… | Start with |
|---|---|
| A website or landing page | [Web stack](#web-stack) + skills in [05 Web](skills/05-web.md) |
| A web app (Next.js) | [App stack](#app-stack) + [08 Dev](skills/08-dev.md) |
| A video, reel, promo or motion film | [Video stack](#video-stack) + [04 Video](skills/04-video.md) |
| A 3D model, logo or render | [3D stack](#3d-stack) + [03 3D](skills/03-3d.md) |
| SEO, a blog, ads, copy | [06 SEO and content](skills/06-seo.md) |
| Research or scraping | [02 Research](skills/02-research.md) + Firecrawl / Apify connectors |
| Word, PDF, PowerPoint, Excel | [07 Docs](skills/07-docs.md) |
| Notes and second brain | [01 Second brain](skills/01-brain.md) + the Obsidian plugin |

## Skills (all 315, by group)

| # | Group | Count |
|---|---|---|
| 1 | [Second brain and productivity (Obsidian)](skills/01-brain.md) | 2 |
| 2 | [Research, scraping and data](skills/02-research.md) | 36 |
| 3 | [3D, Blender and textures](skills/03-3d.md) | 36 |
| 4 | [Video, motion films, audio and image generation](skills/04-video.md) | 35 |
| 5 | [Web design, frontend and web motion](skills/05-web.md) | 80 |
| 6 | [SEO, blog, content and marketing](skills/06-seo.md) | 85 |
| 7 | [Documents, office files and slides](skills/07-docs.md) | 13 |
| 8 | [Coding workflow, databases, auth and agents](skills/08-dev.md) | 28 |

Skills live in `~/.claude/skills` (Claude Code), `~/.agents/skills` (shared, installed with `npx skills add`) and
`~/.codex/skills` (Codex). Each group file says where every skill came from.

## Web stack

The base for every website: **GSAP** (ScrollTrigger, SplitText) + **Lenis** smooth scroll. three.js or OGL only where
a 3D moment earns it. Libraries are installed per project with npm, only when used.

| Job | Library | Skill |
|---|---|---|
| Scroll motion, timelines, text splits | GSAP | `gsap-*`, `cinematic-gsap-lenis-motion-system` |
| Smooth scroll | Lenis | `cinematic-gsap-lenis-motion-system` |
| React motion | Motion (Framer Motion), react-spring | `motion-framer`, `react-spring-physics` |
| Ready animated components | Magic UI, React Bits, Motion Primitives, shadcn registries | `animated-component-libraries`, shadcn connector |
| 3D scenes | three.js, React Three Fiber, drei (glass material) | `threejs-*`, `react-three-fiber` |
| Light WebGL, gloss, shader backgrounds | OGL, Paper Shaders, gl-transitions | `web-motion-extras` |
| Effects to copy | Canvas UI, UI Layouts, Hyperiux, Trickle, Cursify | `web-motion-extras` |
| 2D physics / 3D physics | Matter.js / Rapier | `matterjs` / `web-motion-extras` |
| Interactive vector animation | Rive, Lottie, Spline | `rive-interactive`, `lottie-animations`, `spline-interactive` |
| 2D canvas graphics | PixiJS, p5.js | `pixijs-2d`, `algorithmic-art` |
| Page transitions | Barba, View Transitions | `barba-js`, `react-view-transitions` |
| Particles | tsParticles | `web-motion-extras` |
| 3D scene editing | Theatre.js | `web-motion-extras` |
| Share images per page | Satori / `next/og` | `web-motion-extras` |
| Design judgement | — | `impeccable`, `design-taste-frontend`, `ui-ux-pro-max`, `frontend-design`, `awwwards-animations` |

My taste sites (the look I like) are in the private repo `gaznil/taste`.

## App stack

Next.js + TypeScript + Prisma + PostgreSQL (Supabase or Neon) + Better Auth. Errors: Sentry. Hosting/CDN: Cloudflare.
Skills: `prisma-*`, `neon-*`, Supabase plugin, `better-auth-*`, `react-best-practices`, `webapp-testing`.

## Video stack

HyperFrames (HTML to video) is the engine; my skills `motion-king` (videos from nothing) and `edit-king` (my footage).
FFmpeg is installed. AI video and images: Higgsfield, Krea, Seedance skills. Captions and audio: `hyperframes-audio`.
Remotion is free for teams of up to 3 people, but it's not installed so it doesn't clash with HyperFrames.

## 3D stack

Blender (desktop app) + `blender-*` skills and the Blender connector inside the `blender-mcp` skill. Shrink GLB
files for the web: `gltf-transform optimize in.glb out.glb --compress draco --texture-compress webp` (installed globally).

## Plugins (Claude Code)

Install: `claude plugin marketplace add <source>` then `claude plugin install <name>@<marketplace>`.

| Plugin | Marketplace source | What it adds |
|---|---|---|
| `superpowers` | obra/superpowers-marketplace | Brainstorming, plans, debugging, TDD workflow |
| `codex` | openai/codex-plugin-cc | Hand tasks to OpenAI Codex |
| `github`, `context7`, `supabase`, `typescript-lsp` | anthropics/claude-plugins-official | GitHub, library docs, Supabase, TS language server |
| `chatcut` | github.com/ChatCut-Inc/agent-plugin | Video editing in ChatCut |
| `auth-skills` | better-auth/skills | Better Auth setup |
| `openseo` | every-app/open-seo | SEO research tools |
| `floorplan` | haydenschmitty/floorplan | Floor plans |
| neon skills | neondatabase/agent-skills | Neon Postgres |
| `obsidian-second-brain` | (skill folder with its own server) | Obsidian vault tools |

## Connectors

**claude.ai connectors** (turn on at claude.ai → Settings → Connectors; they follow my account to any PC):
Gmail, Google Drive, Google Calendar, Canva, Notion, Higgsfield, Krea, Apify, Composio, Indeed, Vibe Prospecting,
Claude Docs, Meta Ads, Porotta (my app).

**Claude Code connectors** (`claude mcp add …`):

| Name | Type | Address / command | For |
|---|---|---|---|
| firecrawl | web | https://mcp.firecrawl.dev/v2/mcp | Search and scrape |
| playwright | local | `npx -y @playwright/mcp@latest` | Real browser, screenshots |
| shadcn-registries | local | `npx -y shadcn@latest mcp` | ~390 component registries |
| sentry | web | https://mcp.sentry.dev/mcp | App errors |
| Cloudflare | web | https://mcp.cloudflare.com/mcp | DNS, workers |
| meta_social_technologies | web | https://mcp.facebook.com/devtools | Meta app settings, App Review |
| bland | web | https://api.bland.ai/v1/mcp | Voice agents |
| gaznil-wordpress | local | my own Python server (private) | gaznil.com posts |

Logins and keys are never stored here; each connector asks to sign in again on a new PC.

## Command-line tools

Node.js, Git, GitHub CLI (`gh`), Python, FFmpeg, WSL (OmniRush runs inside it), Claude Code
(`@anthropic-ai/claude-code`), Codex (`@openai/codex`), Antigravity (`agy`), `firecrawl-cli`, `neon`,
`@gltf-transform/cli`, `typescript-language-server`.

## New PC: restore in order

1. Install Node.js, Git, GitHub CLI, Python, FFmpeg, Blender; sign in with `gh auth login`.
2. `npm i -g @anthropic-ai/claude-code @openai/codex firecrawl-cli neon @gltf-transform/cli typescript typescript-language-server`
3. Clone the private backup: `gh repo clone gaznil/stack-backup`; copy `claude/*` into `~/.claude/` and
   `skills/*` into `~/.claude/skills/`.
4. Re-install skills that have a source (the "Source" column in each group file): `npx skills add <owner/repo>`.
5. Add the plugins and Claude Code connectors above; turn on the claude.ai connectors.
6. Clone project repos (Porotta, taste, minis, motion-king…) as their notes in `~/.claude/context` say.
