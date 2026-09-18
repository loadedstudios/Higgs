# Higgsfield API / Pipelines Overview

Pulled live on 18 September 2026 from the Higgsfield MCP connector (the same "API" Alex Mashrabov, CEO of Higgsfield, referred to in his tweet about the company's $5.4B valuation).

## Verified facts

- CEO/co-founder: Alex Mashrabov (@alexmashrabov), previously co-founder of AI Factory (Snapchat Cameos, acquired by Snap in 2020).
- Valuation: $5.4B, following a $400M raise from Goldman Sachs, Intel, DST Global and Liberty Global.
- The API genuinely exposes Higgsfield's product pipelines, skills, and models, confirmed by direct tool access below.

## Image models (partial list, 30+ available)

| Model ID | Provider | Description |
|---|---|---|
| soul_2 / soul_v2 | Higgsfield | Realistic UGC, fashion editorial, character generation |
| soul_cinematic | Higgsfield | Cinema-grade stills and concept art |
| gpt_image_2 | OpenAI | 1k/2k/4k, low/medium/high quality tiers |
| cinematic_studio_2_5 | Higgsfield | Cinematic stills, up to 4K |
| marketing_studio_image | Higgsfield | One-click product image ads for social campaigns |
| ms_image (DTC Ads) | Higgsfield | Brand-kit-aware ad image generation, avatars, products |
| nano_banana / nano_banana_pro / nano_banana_2 | Google | Budget to ultimate quality, text-to-image and image-to-image |
| seedream_v4_5 | Bytedance | 4K to ~6K output, precise transformations |
| z_image | Tongyi-MAI | Super fast, stylized text-to-image |

## Video models (partial list)

| Model ID | Provider | Description |
|---|---|---|
| cinematic_studio_3_0 | Higgsfield | Most advanced cinema-grade model, up to 4K, 4-15s |
| cinematic_studio_video_v2 | Higgsfield | Refined cinematic camera and colour, genre control, 3-12s |
| marketing_studio_video | Higgsfield | One-click product ads, TikTok/Reels ready, 12-15s |
| higgsfield_preset | Higgsfield | Preset-routed image-to-video generation |

## 3D models

| Model ID | Provider | Description |
|---|---|---|
| sam_3_3d | Meta | Single image to textured 3D GLB mesh |
| image_to_3d / meshy_image_to_3d | Meshy | Single image to 3D GLB with texturing, PBR, rigging, animation |
| multi_image_to_3d | Meshy | 1-4 images of the same subject to 3D GLB, better accuracy |
| 3d_rigging | Meshy | Rig an existing 3D model URL, apply pre-canned animation |

## Workflow pipelines (16 available)

These are Higgsfield's packaged, multi-step production skills, callable via API:

- ad-multiplier
- brand-asset-creation
- character-sheet
- faceless-video
- narrator
- product-photoshoot
- subtitles
- thumbnail-generation
- ugc-product-video
- ugc-review-video
- ugc-try-on-video
- ugc-tutorial-video
- ugc-unboxing-video
- ugc-website-video
- video-editing
- website-builder-flow (builds and deploys full websites, web apps, and browser games)

## Source

- Compiled directly from the Higgsfield MCP connector's `models_explore` and `get_workflow_instructions` tools, live.
- Company/valuation facts checked against public reporting (Goldman Sachs, Intel, DST Global, Liberty Global funding round).
