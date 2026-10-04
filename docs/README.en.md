<div align="center">

# AUVRA

### Your APIs. Your creative workspace.

From keyframes, Camera Sphere and Blender previs to H3 video, face refinement and the next shot.

**Create in one workspace using your own APIs or GPU.**

**[Start creating](https://auvra.art/)　·　[中文](../README.md)　·　[Full feature guide](features.en.md)**

</div>

---

## Why AUVRA exists

Creating a video often takes several models: design characters, establish a scene, create sound, generate footage, refine details and continue the next shot. Assets end up across platforms and accounts, with repeated setup between steps.

AUVRA brings those steps into one project and one canvas. **Choose your models, API providers and compute, then reuse existing references and results.** Use services for each project's needs without committing all production to one provider's annual plan.

For storyboards, short films, music videos, character and product shots, and creators exploring video production on their own GPU.

## See AUVRA in action

| Meet the workspace | From an image to a video |
| :---: | :---: |
| <a href="https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/auvra-overview-zh.mp4"><img src="../assets/overview-poster.jpg" width="360" alt="AUVRA workspace introduction" /></a> | <a href="https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/creative-example.mp4"><img src="../assets/example-poster.jpg" width="360" alt="Creative video example" /></a> |
| [Introduction · 38 seconds](https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/auvra-overview-zh.mp4) | [Creative example · 5 seconds](https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/creative-example.mp4) |

## One canvas, connected creative work

**References → Camera exploration / previs → Video generation → Face refinement / enhancement → Frames for the next shot**

| Core capability | What you can do |
| :--- | :--- |
| **Creative canvas** | Organize images, video and audio; connect references and reuse results in subsequent shots. |
| **ComfyUI workflows** | Connect your own remote GPU and locally hosted MiniMax H3. Choose quick previews or high quality and view the actual seed. |
| **Face refinement** | Refine faces in generated footage. Keep the original and refined versions for comparison. |
| **Camera Sphere** | Explore side, high and reverse viewpoints from an image, adjust framing and reuse results as references. |
| **3D previs · Experimental** | Express camera movement and blocking with simple Blender geometry, then combine images and audio to explore H3 video. |
| **Frame capture / Next Shot** | Extract first, last or current frames from uploaded or generated videos into connected image nodes. |
| **Video enhancement** | Choose AuvrA · Free or enhancement through your connected AtlasCloud account, with cost confirmation before cloud submission. |

### ComfyUI: use your video workflows from the canvas

Connect your remote ComfyUI to use **locally hosted MiniMax H3 video generation** inside website projects. Combine character images, scene references, video and audio according to the selected mode. Try a direction with quick previews, then choose high quality. Results return to the canvas; view and copy the actual seed to retain the settings trail for a generation.

You use your own compute instance. Once its models and dependencies are configured, operate this production route from AUVRA rather than repeatedly organizing inputs and results across tools.

### Face refinement: keep both versions

The ComfyUI production route includes facial-detail refinement. Enable automatic refinement, disable it or adjust its strength. **Original and refined footage are saved separately.** Compare wider shots, multiple people and moving faces before choosing a version, with the original still available.

### Camera Sphere and Next Shot: continue from an existing image

Adjust angle, elevation and distance around a reference scene to explore side, high and reverse viewpoints and different shot sizes. Spatial orbit exploration provides additional views to select. Use the resulting image as a storyboard frame or video reference.

Combine **Next Shot / single-shot exploration** with frame capture to start the next production step from existing footage. Extract its first, last or current frame into an automatically connected image node, then use it for subsequent generation. Uploaded video assets are supported too.

### Blender previs: express camera ideas through space

Block a scene with simple geometry, position characters and plan the camera. Combine previs video, character designs, scene references and audio for **locally hosted MiniMax H3 generation**. The previs communicates positions, spatial relationships and camera paths; image references, descriptions and the model supply appearance and action. Fully detailed characters and limb animation are not required to begin exploration.

This is an **experimental creative capability** we continue to test. Experiments include walking, pursuit, wuxia fights, following shots, push-and-pan movement and reverse shots, with stacked previs/output comparisons. Use it to explore storyboard and filming ideas; the examples below show the actual degree of guidance.

### Sound, enhancement, assets and AI assistants

| Supporting capability | How it fits |
| :--- | :--- |
| **Sound and audio tracks** | Create sound with the integrated Doubao audio capabilities, use audio references in supported modes, or replace a video soundtrack. |
| **Image and video modes** | Choose supported generation / editing, first-frame, first/last-frame, multiple-reference, continuation and other available modes by model. |
| **Providers and price information** | Select models and channels, view supported dimensions, resolutions and advanced settings, and compare available public prices in the pricing popover. |
| **Video enhancement** | Choose free enhancement or your connected AtlasCloud; keep the original and save the enhanced version separately. |
| **Project asset library** | Organize subjects, references and results by project; view personal storage usage and manage media. |
| **MCP / Plugin** | Authorize AUVRA in compatible AI clients so assistants can use supported project and creative tools. Specify models, quantities and budgets before generation. |

[Read the complete feature guide and practical limits →](features.en.md)

## Experimental comparisons

| Blender previs → H3 video | Face refinement |
| :---: | :---: |
| <a href="https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/previs-comparison.mp4"><img src="../assets/previs-poster.jpg" width="300" alt="Blender previs above H3 output" /></a> | <a href="https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/face-comparison.mp4"><img src="../assets/face-poster.jpg" width="300" alt="Original above refined footage" /></a> |
| Top: previs · Bottom: generated footage | Top: original · Bottom: refined footage |
| [View comparison · 8 seconds](https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/previs-comparison.mp4) | [View comparison · 8 seconds](https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/face-comparison.mp4) |

### Camera Sphere: one reference, different viewpoints

| Original | Side view | Higher view |
| :---: | :---: | :---: |
| <img src="../assets/camera-original.jpg" width="230" alt="Original reference" /> | <img src="../assets/camera-side.jpg" width="230" alt="Side-view result" /> | <img src="../assets/camera-high.jpg" width="230" alt="Higher-view result" /> |

[Read the gallery notes →](examples.en.md)

These are existing experimental outputs. Previs provides guidance; Camera Sphere infers unseen space. Face refinement still requires review for identity, jitter and lip sync. Results vary. Video links lead directly to MP4 files, which your browser may play or download.

## Choose services for each project

Use supported official APIs, APIYI, AtlasCloud and your own ComfyUI in one workspace. We encourage official APIs while offering supported third-party channels as optional choices. You do not need to commit all creative work to one provider's annual plan.

**Models, modes, dimensions and prices vary by provider.** API generation is billed by your selected provider; GPU rental is billed by your compute service.

## Get started

1. **Sign in** at [auvra.art](https://auvra.art/).
2. **Connect** an API account or remote ComfyUI with the required models and dependencies.
3. **Create a project**, add references and generate your first shot.

The website and narrated introduction currently use Chinese. English documentation does not imply an English product interface.

---

**[Product feedback](https://github.com/zakkaart88-debug/auvra-showcase/issues/new/choose)　·　[Website / cooperation](https://auvra.art/)**

This is a product showcase, **not an open-source code release**. No application source, internal workflows, prompt strategies or deployment materials are provided. Never submit keys or private media in public feedback.
