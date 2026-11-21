# Video styles index: code-made video repos, by type

Snapshot: 21 Nov 2026 (stars and licences checked that day). Purpose: when I need a new KIND of video, look here first.
If a row fits, use it (install the skill, or read its STYLE/rules) instead of researching again. Research again only when
nothing here fits, or the row is older than ~3 months (this space moves fast).

Licence key: ✅ MIT / Apache = may learn from and reuse with credit, also in paid work. 👀 = read-only (non-commercial,
own licence, or no licence = all rights reserved): learn ideas only, never copy code or wording.

## Find by what you want to make

| I want… | Look at first |
|---|---|
| Any look from a big menu (99 styles) | lemo-opuscar 👀, huashu-art-motion ✅, animate ✅ |
| Topic in -> narrated explainer out | anything2explainer 👀, kurzgesagt-motion ✅, animated-explainer-skills ✅, vox-explainer-skill ✅ |
| Kurzgesagt-style flat-vector explainer | opus-5.5-kurzgesagt-motion ✅, animated-explainer-skills ✅, claude-animation-skills ✅ |
| Vox-style paper-collage explainer | vox-director ✅, vox-explainer-skill ✅ |
| Hand-drawn / whiteboard / "pen draws while voice talks" | khan-explainer ✅, weilanx-claude-videos ✅, animate (sketchbook, crosshatch) ✅ |
| Stickman faceless YouTube | stickman-video-director ✅ |
| Math / science / theorem explainer | manim ✅, ManimML ✅, TheoremExplainAgent ✅, Code2Video ✅ |
| Charts, diagrams, data boards synced to voice | YouTube-AI-Motion-Graphics ✅, animate (math) ✅ |
| Launch film / product promo / ad | huashu-motion ✅, motionmaxxing ✅, bang-motion ✅, opuscar glass-product 👀 |
| Make an "AI-looking" video look pro | motionmaxxing ✅ (laws + render gates) |
| Edit my own short-form footage, clone a ref reel's style | mrpaidsocial-video-editor-agent 👀, motion-video-skill ✅ |
| Quick faceless shorts from stock / AI images (not drawn in code) | YumCut 👀, purffle-shorts ✅, content-factory ✅ |
| Glass, refraction, smooth vector shading, SVG tools | see "Drawing and look tools" below |

## 1. Style libraries (many looks in one place)

| Repo | Stars | Type / look | Good for | Licence |
|---|---|---|---|---|
| [lemomo-ai/lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar) | 19.4k | 99 film styles in code (watercolor, neon tubes, glass product, teardown, blueprint, ukiyo-e, LiDAR, newsreel…), each a STYLE.md + demo | Picking a look; TECHNIQUE.md = full code-video pipeline; STYLE.md files show how to describe a look | 👀 own licence |
| [alchaincyf/huashu-art-motion](https://github.com/alchaincyf/huashu-art-motion) | 7.4k | 35 art-history styles drawn in canvas code (Chinese docs) | Drawing tricks: style renderers, cel shadow band, light maps, plastic shading, "draw characters properly or show only hands" | ✅ MIT |
| [cth9191/animate](https://github.com/cth9191/animate) | 2.2k | 7 styles (cut paper, crosshatch, riso, sketchbook, math, pixel, isometric) + "new look from your references" | Story grammar, look check before build, measured review, matching a reference look | ✅ MIT |
| [artemnovitckii/claude-animation-skills](https://github.com/artemnovitckii/claude-animation-skills) | 1.0k | 11 reel styles: low-poly, voxel, 3D cartoon explainer, Kurzgesagt-style… | Short reels, no footage | ✅ MIT |
| [iart-ai/motion-skills](https://github.com/iart-ai/motion-skills) | 2.0k | 56 skills: kinetic type, data-viz, explainers, TikTok/Reels, WebGL, Manim | Broad motion-graphics menu | 👀 no licence |

## 2. Topic -> explainer skills (full pipeline)

| Repo | Stars | Type / look | Good for | Licence |
|---|---|---|---|---|
| [Vincentwei1021/anything2explainer](https://github.com/Vincentwei1021/anything2explainer) | 3.5k | Black-canvas line-art motion graphics, Remotion, 2-8 min, parallel build agents | Composition + light rules with numbers, QC metric scripts | 👀 non-commercial |
| [Vincentwei1021/video-talkcraft](https://github.com/Vincentwei1021/video-talkcraft) | 2.5k | Voiceover-driven explainer, word-level sync, 109 motion rules | Motion rules | 👀 non-commercial |
| [dawoodabdullah010/opus-5.5-kurzgesagt-motion](https://github.com/dawoodabdullah010/opus-5.5-kurzgesagt-motion) | small | Kurzgesagt-style, 60 fps canvas, ElevenLabs | Measured style reference (palette, camera), mistakes log K1-K49, camera checks | ✅ MIT |
| [BusyBee3333/animated-explainer-skills](https://github.com/BusyBee3333/animated-explainer-skills) | 33 | Kurzgesagt-quality explainer as one HTML file, GSAP | Prop shading recipes (two-tone, gloss, contact shadow, inner ellipse) | ✅ MIT |
| [CK42BB/vox-explainer-skill](https://github.com/CK42BB/vox-explainer-skill) | 290 | Vox-style explainer: script, keyframes, voice, music | Vox look | ✅ MIT |
| [Alisa0808/vox-director](https://github.com/Alisa0808/vox-director) | 3.0k | Vox paper-collage explainer/ad (uses Atlas Cloud + ffmpeg) | Collage look | ✅ MIT |
| [Anil-matcha/vox-ai-motion-graphics-generator](https://github.com/Anil-matcha/vox-ai-motion-graphics-generator) | 365 | Vox collage explainer | Collage look | 👀 no licence |
| [MegaTroll222/VOX-COLLAGE-BROLL](https://github.com/MegaTroll222/VOX-COLLAGE-BROLL) | 323 | One spoken line -> collage b-roll | Collage b-roll | 👀 other |
| [haiderfarooq3/khan-explainer](https://github.com/haiderfarooq3/khan-explainer) | 166 | Khan Academy style: a pen draws while a voice explains; free, local | Whiteboard lessons | ✅ MIT |
| [Azure12355/weilanx-claude-videos](https://github.com/Azure12355/weilanx-claude-videos) | 272 | Hand-drawn + pixel-art explainers, Remotion + SVG, code music/SFX | Hand-drawn look in SVG | ✅ MIT |
| [kaomei/stickman-video-director](https://github.com/kaomei/stickman-video-director) | 7.3k | Script -> stickman faceless video, 14+ styles | Faceless YouTube stickman | ✅ MIT |
| [iart-ai/explainer-video-skills](https://github.com/iart-ai/explainer-video-skills) | 133 | Script, storyboard, narrated explainers, recaps, animated diagrams | Recaps, diagrams | ✅ MIT |
| [sirioberati/YouTube-AI-Motion-Graphics](https://github.com/sirioberati/YouTube-AI-Motion-Graphics) | 241 | 74 animated HTML explainer boards (charts, Venn, timeline, heatmap) synced to voice | Data / diagram inserts | ✅ MIT |
| [promptmetrics/video-skill](https://github.com/promptmetrics/video-skill) | 8 | Plans Kurzgesagt-style videos (script, storyboard, design spec), no render | Planning only | ✅ MIT |

## 3. Math, science, code-to-video research

| Repo | Stars | Type / look | Good for | Licence |
|---|---|---|---|---|
| [ManimCommunity/manim](https://github.com/ManimCommunity/manim) | 42.8k | 3Blue1Brown-style math animation (Python) | Math, graphs, equations | ✅ MIT |
| [helblazer811/ManimML](https://github.com/helblazer811/ManimML) | 3.5k | Machine-learning concept animations on Manim | Neural nets, ML | ✅ MIT |
| [marcelo-earth/generative-manim](https://github.com/marcelo-earth/generative-manim) | 942 | Prompt -> Manim video | Quick math clips | ✅ Apache-2.0 |
| [TIGER-AI-Lab/TheoremExplainAgent](https://github.com/TIGER-AI-Lab/TheoremExplainAgent) | 1.5k | Agent makes narrated Manim theorem videos (ACL 2025) | Planning + visual self-repair loop | ✅ MIT |
| [showlab/Code2Video](https://github.com/showlab/Code2Video) | 2.4k | Planner / coder / critic agents for educational code videos (ICML 2026) | Critic-with-anchors idea for layout | ✅ MIT |
| [OpenSenseNova/SenseNova-6.8-Code2Video](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video) | 751 | Open model for code-driven video | Research | 👀 no licence |
| [FrontierVideo/FrontierVideo](https://github.com/FrontierVideo/FrontierVideo) | 16 | Benchmark of coding agents doing pro video production | Knowing what agents fail at | not checked |

## 4. Launch films, promos, motion graphics

| Repo | Stars | Type / look | Good for | Licence |
|---|---|---|---|---|
| [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | 2.9k | Commercial launch films by an agent, composes music, "point at the frame to change it" | Product launches | ✅ MIT |
| [Tejashmakwana/motionmaxxing](https://github.com/Tejashmakwana/motionmaxxing) | 1.7k | Turns AI-slop videos into motion-designer films | World/light/texture laws, slop table, motion blur + grain, render gates | ✅ Apache-2.0 |
| [bangtutorial/bang-motion](https://github.com/bangtutorial/bang-motion) | 2.9k | Openers, promos, bumpers, kinetic type, 5 explainer styles | Short motion pieces | ✅ MIT |
| [unclejobs-ai/motion-video-skill](https://github.com/unclejobs-ai/motion-video-skill) | 143 | 15-90 s promo/character videos, reference analysis, 7 gates, Remotion + HyperFrames | Ref-matched promos | ✅ MIT |
| [siyuanfeng636-cpu/agentic-motion-graphics](https://github.com/siyuanfeng636-cpu/agentic-motion-graphics) | 15 | Code-to-video motion graphics on HyperFrames + GSAP + Whisper + TTS | HyperFrames examples | ✅ MIT |
| [haidrrrry/claude-remotion-skill](https://github.com/haidrrrry/claude-remotion-skill) | 1.2k | Claude makes/edits motion graphics with Remotion | Remotion users | ✅ MIT |
| [mrpaidsocial/mrpaidsocial-video-editor-agent](https://github.com/mrpaidsocial/mrpaidsocial-video-editor-agent) | 188 | Edit short-form end to end, style-clone a ref reel, ElevenLabs sound | Editing own footage | 👀 no licence |

## 5. Engines (alternatives to HyperFrames)

| Repo | Stars | What | Licence |
|---|---|---|---|
| HyperFrames (my engine) | - | HTML -> video; has built-in motion blur (`data-motion-blur="on"`) | see stack README |
| [motion-canvas/motion-canvas](https://github.com/motion-canvas/motion-canvas) | 20.1k | TypeScript animation engine with an editor | ✅ MIT |
| [VideoZero/skills](https://github.com/VideoZero/skills) | 79 | Agent skills for Motion Canvas structured visuals | ✅ Apache-2.0 |
| [vawe-hq/vawe](https://github.com/vawe-hq/vawe) | 23 | One HTML page -> mp4, for coding agents | ✅ Apache-2.0 |
| [codedbytahir/motionforge](https://github.com/codedbytahir/motionforge) | 115 | Free Remotion alternative (React) | ✅ MIT |
| [ZLHad/OpenVideoHarness](https://github.com/ZLHad/OpenVideoHarness) | 40 | One sentence -> agent writes code and renders | ✅ MIT |

## 6. Faceless shorts from stock footage / AI images (not drawn in code)

| Repo | Stars | What | Licence |
|---|---|---|---|
| [IgorShadurin/app.yumcut.com](https://github.com/IgorShadurin/app.yumcut.com) | 915 | Prompt -> vertical video: script, scenes, voice, subtitles; self-hosted | 👀 other |
| [Chamanrajragu/purffle-shorts](https://github.com/Chamanrajragu/purffle-shorts) | 101 | Any-LLM script, TTS, stock/AI images, word captions, Reddit/chat stories, auto-upload, MCP | ✅ MIT |
| [SamurAIGPT/AI-Faceless-Video-Generator](https://github.com/SamurAIGPT/AI-Faceless-Video-Generator) | 544 | Script + voice + AI talking face | ✅ MIT |
| [jutsuhq/content-factory](https://github.com/jutsuhq/content-factory) | 7 | Script -> vertical video from AI images, Apple-silicon Macs only | ✅ MIT |

## 7. Drawing and look tools

| Repo / source | What | Good for | Licence |
|---|---|---|---|
| [VII-Cae/hyalite--liquid-glass](https://github.com/VII-Cae/hyalite--liquid-glass) | Real refraction glass with SVG displacement + lens map, no WebGL | Glass / clear plastic | ✅ MIT |
| [kubai087/glasswork](https://github.com/kubai087/glasswork) | Liquid-glass material as CSS, refracting thick rim | Glass UI | ✅ MIT |
| [Lichtso/FreeFormGradients](https://github.com/Lichtso/FreeFormGradients) | Diffusion curves + distance transform (WebGL2) | Smooth painterly vector shading | ✅ MIT |
| [BachiLi/diffvg](https://github.com/BachiLi/diffvg) | Differentiable SVG rasteriser (Python/PyTorch) | Auto-tuning an SVG to match a picture | ✅ Apache-2.0 |
| [joanrod/star-vector](https://github.com/joanrod/star-vector) | Image/text -> SVG code model | SVG generation research | ✅ Apache-2.0 |
| [css-doodle/css-doodle](https://github.com/css-doodle/css-doodle) | Web component for pattern art | Generative backgrounds | ✅ MIT |
| [GraphiteEditor/Graphite](https://github.com/GraphiteEditor/Graphite) | Open 2D design + motion graphics app | Node-based vector work | ✅ Apache-2.0 |
| [Oklab (Björn Ottosson)](https://bottosson.github.io/posts/oklab/) | Perceptual colour space, small code | Gradients without muddy middles | free code |
| [Inigo Quilez articles](https://iquilezles.org/articles/) | 2D distance functions, cosine palettes | Placing bands and rings, colour variety | learn from |
| [Diffusion Curves paper (Orzan 2008)](https://inria.hal.science/hal-00840848/document) | Vector primitive for smooth shading | Theory behind FreeFormGradients | paper |

## 8. Prompt collections and curated lists

| Repo | What |
|---|---|
| [yihui-dev/awesome-opus5-5-videos](https://github.com/yihui-dev/awesome-opus5-5-videos) (16.1k, ✅ MIT) | 703 prompts behind viral Claude Opus 5.5 code videos (motion graphics, explainers, 3D, games) |
| [terkelg/awesome-creative-coding](https://github.com/terkelg/awesome-creative-coding) | Creative coding, generative art, shaders |
| [willianjusten/awesome-svg](https://github.com/willianjusten/awesome-svg) | SVG tools and libraries |
| [raphamorim/awesome-canvas](https://github.com/raphamorim/awesome-canvas) | Canvas libraries |
| [sergey-pimenov/awesome-web-animation](https://github.com/sergey-pimenov/awesome-web-animation) | Web animation (JS, CSS, SVG) |

## How it was found (to refresh later)
`gh search repos --topic explainer-video --sort stars`, plus searches for "explainer video claude", "motion graphics skills agent",
`--topic motion-canvas`, `--topic creative-coding`, "kurzgesagt", "code2video", "diffusion curves", `--topic svg-filters`;
licences via `gh repo view <repo> --json licenseInfo`. Free, no credits.
