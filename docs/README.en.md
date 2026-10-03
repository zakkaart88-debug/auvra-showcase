# AUVRA

<img src="../assets/auvra-avatar-white.png" alt="AUVRA" width="104" />

### Your APIs. Your creative workspace.

Take a reference image through camera exploration, 3D previs, video generation and face refinement in one creative canvas. Connect your own API accounts or remote ComfyUI, choose the model for each shot, and reuse results across supported services.

**[Visit AUVRA](https://auvra.art/) · [中文介绍](../README.md) · [Experimental gallery](examples.en.md)**

## Watch the introduction

[![AUVRA introduction — Chinese narration](../assets/overview-poster.jpg)](../assets/auvra-overview-zh.mp4)

[Watch / download the 38-second introduction](https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/auvra-overview-zh.mp4)

## Inside the workspace

### A creative canvas that connects assets and shots

Keep character references, scenes, videos, audio and generation nodes in one project. Connect assets as references, mention them in creative descriptions, and hover over reference images to check your selection. Generated results stay on the canvas and can feed subsequent shots, reducing repeated downloads, uploads and asset organization across platforms.

### ComfyUI workflows on your own GPU

AUVRA provides ComfyUI video workflows based on the **locally hosted MiniMax H3 model**. Connect your own remote ComfyUI instance and submit jobs and view results from the website. Depending on the selected mode, images, video and audio can serve as references. Quick preview and high-quality options are available, and you can view and copy the actual generation seed.

This gives creators a route using their own compute rather than a cloud video API for every shot. The instance needs the required models and dependencies. Speed and supported resolution depend on the GPU, model and workflow. A seed requires matching inputs and settings to be useful; it does not guarantee an identical composition at a different resolution.

### Face restoration and refinement

The ComfyUI video route includes **AUVRA face refinement** to improve facial details in generated footage, with comparison particularly useful for moving subjects, multiple people and wider shots. You can disable refinement or adjust its strength. **The original and refined versions are saved separately.**

This is an enhancement tool, not a guarantee against facial artifacts. Very small faces, occlusion, identity consistency, temporal stability and dialogue lip sync still need shot-by-shot review.

### Camera Sphere: explore viewpoints from an image

Adjust viewing angle, elevation and distance to explore side views, high angles, reverse views and different shot sizes. Use results as storyboard frames or image references for video. Spatial orbit exploration helps explore views around a scene and select useful frames.

Useful for characters, products and scene planning. A single image does not contain a complete 3D scene; the model infers unseen space. This is **AI camera exploration**, not precise 3D reconstruction, and large viewpoint changes may introduce spatial or appearance errors.

### 3D previs: plan space and camera movement first

An **experimental feature based on locally hosted MiniMax H3**. Build simple geometry in Blender, place stand-in characters and arrange camera movement. Use the previs video with character images, scene references and audio to explore a rendered video in AUVRA.

The previs communicates camera movement, subject positions and spatial relationships. Images supply appearance and visual style, while descriptions and the model supply action. You do not need fully animated character limbs before exploring a shot. Our experiments include walking, pursuit, wuxia fights, following shots, push-and-pan movement and reverse shots, with stacked previs/output comparisons.

It currently supports storyboard exploration and rough previs guidance. It **does not guarantee frame-accurate blocking, geometry or camera paths**. Complex shots need comparison, adjustment and selection. Providing audio does not by itself guarantee accurate dialogue lip sync.

### Frame capture, subsequent shots and enhancement

- **Video frame capture:** extract the first, last or current frame from generated or uploaded videos and create a connected image node for continued work.
- **Next Shot / single-shot exploration:** use an existing frame to explore the next camera or narrative choice without rebuilding assets from scratch.
- **Video enhancement:** choose AuvrA · Free or AtlasCloud cloud enhancement. The cloud option uses your connected AtlasCloud account and requires cost confirmation before submission; the original is retained. Increasing resolution does not guarantee recovery of missing detail.

## See existing experiments

**Blender previs → H3 video:** previs on top, generated footage below.

[![Previs and generated footage](../assets/previs-poster.jpg)](../assets/previs-comparison.mp4)

[Watch the 8-second comparison](../assets/previs-comparison.mp4)

**Face refinement comparison:** original on top, refined footage below. Compare facial details during movement.

[![Original and refined video](../assets/face-poster.jpg)](../assets/face-comparison.mp4)

[Watch the 8-second face comparison](../assets/face-comparison.mp4)

**Camera Sphere viewpoints:** original image, side view and higher view.

| Original | Side view | Higher view |
| --- | --- | --- |
| ![Original](../assets/camera-original.jpg) | ![Side view](../assets/camera-side.jpg) | ![Higher view](../assets/camera-high.jpg) |

[Read the full experimental gallery](examples.en.md)

These are existing experimental outputs, not promises of identical results on every run. Only output media and public descriptions are shared; internal workflows, prompt strategies and implementation code are not included.

## Choose your services

Use supported official APIs, APIYI, AtlasCloud and your own ComfyUI in one workspace. Select available modes, aspect ratios, resolutions and advanced options by model and provider, and view pricing information. Coverage, capabilities, billing and data-handling policies differ between providers.

We support and encourage official APIs while offering selected third-party providers as optional choices. Choose services for each project rather than committing all creative work to one platform's annual plan. Generation charges come from the selected provider; GPU rental is billed by your compute service. Connecting an account does not make generation free.

## Get started

1. Visit [auvra.art](https://auvra.art/) and create an account or sign in.
2. Connect a supported API account or a remote ComfyUI instance with the required models and dependencies.
3. Create a project, add references and generate your first shot.

For AI video enthusiasts, storyboard artists and short-film or music-video teams. Features depend on the currently available website options. The website and introduction video currently use Chinese; this English documentation does not imply an English product interface.

## Feedback and cooperation

Use [Issues](https://github.com/zakkaart88-debug/auvra-showcase/issues) for product feedback, or the website's feedback form for cooperation inquiries. Never post keys, passwords, private media or account details. Star or Watch this repository to follow updates.

This is a **product showcase and documentation repository**, not an open-source release. No application source, internal workflows, prompt recipes, API implementations or deployment materials are provided. Use the product on the website; product and brand use is subject to its terms.
