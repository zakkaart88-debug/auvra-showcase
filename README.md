<div align="center">

# AUVRA

### 你的 API，你的影像创作工作台

从关键帧、相机球与 Blender 白模预演，到 H3 视频、人脸修复和下一镜。

**用自己的 API 或 GPU，在同一个工作台完成影像创作。**

**[开始创作](https://auvra.art/)　·　[English](docs/README.en.md)　·　[快速开始](docs/quick-start.md)　·　[更新记录](docs/updates.md)**

</div>

---

## 为什么做 AUVRA

创作一段影像，往往需要多个模型：画角色、定场景、做声音、生成视频、修复细节，再继续下一镜。素材散落在不同平台，服务账户不互通，每换一步都要重新整理。

AUVRA 把这些步骤放进一个项目、一张画布。**用户自己选择模型、API 渠道和算力，已有素材和结果可以接着用**，按项目需要灵活创作，不必把全部制作固定在一家平台的年卡里。

适合制作分镜、短片、MV、人物与产品镜头，以及探索自有 GPU 视频制作的创作者。

## 看 AUVRA 能做什么

| 38 秒认识工作台 | 从一个画面，到一段影像 |
| :---: | :---: |
| <a href="https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/auvra-overview-zh.mp4"><img src="assets/overview-poster.jpg" width="360" alt="AUVRA 工作台介绍" /></a> | <a href="https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/creative-example.mp4"><img src="assets/example-poster.jpg" width="360" alt="影像创作样例" /></a> |
| [介绍视频 · 38 秒](https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/auvra-overview-zh.mp4) | [创作样例 · 5 秒](https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/creative-example.mp4) |

## 一张画布，串起整个创作过程

**参考素材 → 镜头探索 / 白模预演 → 视频生成 → 修脸与增强 → 截帧接下一镜**

| 核心能力 | 你可以怎样使用 |
| :--- | :--- |
| **创作画布** | 整理图片、视频与声音；连线引用素材，结果继续用于后续镜头。 |
| **ComfyUI 工作流** | 连接自己的远程 GPU，使用 MiniMax H3 本地模型；选择快速预览或高质量，查看实际种子。 |
| **人脸修复** | 对生成视频进行脸部精修，保留原片与修复版，方便比较和选用。 |
| **相机球** | 从一张图探索侧面、俯视与反向机位，调整取景远近，继续作为分镜或视频参考。 |
| **白模预演 · 实验性** | 用 Blender 简单几何体表达运镜和人物位置，结合参考图与声音，探索 H3 视频效果。 |
| **截帧与下一镜** | 截取上传或生成视频的首帧、尾帧、当前帧，自动创建连线图片节点。 |
| **画质提升** | 选择 AuvrA · 免费增强，或绑定 AtlasCloud 做云端增强，确认费用后提交。 |

### ComfyUI：从网站画布调用自己的视频工作流

连接自己的远程 ComfyUI，把 **MiniMax H3 本地视频生成**用在网站项目里。根据模式组合角色图、场景图、参考视频和声音；先用快速模式试方向，再选择高质量出片。生成结果回到画布，实际种子可查看和复制，方便保留这次创作的参数线索。

用户使用自己的算力实例。模型与依赖配置完成后，可在 AUVRA 操作这条生成路线，无需每次回到多个工具中整理输入与结果。

### 人脸修复：原片和精修版都留下

为 ComfyUI 视频制作配套脸部精修，方便处理生成片段的脸部细节。支持自动修脸、关闭或调整增强程度，**原片与修复版分别保存**。远景、多人和运动镜头可以对照检查，再决定使用哪一版，不必担心增强后只剩一个结果。

### 相机球与下一镜：把一张画面继续拍下去

围绕参考画面调整相机角度、俯仰和距离，探索侧面、俯视、反向机位和不同景别；通过空间环绕探索可选视角。选出的画面继续用于分镜或视频参考。

结合**下一镜 / 单镜头推演**与视频截帧，已有画面能成为下一段制作的起点：截取首帧、尾帧或当前帧，自动创建连线图片节点，再接到后续生成。上传的视频素材也能这样使用。

### Blender 白模预演：把镜头想法变成可参考的空间

先用简单几何体搭场景、放人物、安排运镜，再将白模预演、角色设定图、场景图和声音一起用于 **MiniMax H3 本地视频生成**。白模用于表达人物位置、空间关系和镜头路径；外观与动作由图片参考、文字描述和模型共同完成，不必先制作精细人物或完整肢体动画。

这是我们持续实测的**实验性创作能力**：已探索走动、追逐、武侠打斗、跟随、推摇与反打，并保留预演和结果的上下对比。适合验证分镜与拍摄想法，实际约束程度可直接从下面的案例观察。

### 声音、增强、素材管理与 AI 助手

| 配套能力 | 如何接着用 |
| :--- | :--- |
| **声音创作与音轨** | 使用已接入的豆包音频能力创作声音；在支持的模式中加入参考音频，也可替换视频音轨。 |
| **图片与视频多模式** | 根据模型选用图片生成 / 编辑、首帧、首尾帧、多参考、续接或其他已支持模式。 |
| **供应商与价格信息** | 按模型和服务渠道选择，查看可用尺寸、分辨率和高级设置；在价格浮层中比较已公开的报价信息。 |
| **画质提升** | 选择免费增强或自有 AtlasCloud 云端增强，原片保留，增强版另存。 |
| **项目资产库** | 把主体、参考素材和生成结果归入项目，查看个人存储使用量并管理素材。 |
| **MCP / Plugin** | 在兼容的 AI 客户端授权 AUVRA，让助手使用支持的项目与创作工具；生成前明确模型、数量与预算。 |

[查看完整功能说明与适用范围 →](docs/features.md)

## 实验对比：直接看画面

| Blender 白模 → H3 视频 | 人脸修复前后 |
| :---: | :---: |
| <a href="https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/previs-comparison.mp4"><img src="assets/previs-poster.jpg" width="300" alt="上方 Blender 预演，下方 H3 生成视频" /></a> | <a href="https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/face-comparison.mp4"><img src="assets/face-poster.jpg" width="300" alt="上方原片，下方人脸修复版" /></a> |
| 上：白模预演　下：生成结果 | 上：原片　下：修复版 |
| [查看对比 · 8 秒](https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/previs-comparison.mp4) | [查看对比 · 8 秒](https://github.com/zakkaart88-debug/auvra-showcase/raw/refs/heads/main/assets/face-comparison.mp4) |

### 相机球：同一张参考图，不同机位

| 原始画面 | 侧面探索 | 高机位探索 |
| :---: | :---: | :---: |
| <img src="assets/camera-original.jpg" width="230" alt="原始参考图" /> | <img src="assets/camera-side.jpg" width="230" alt="侧面机位结果" /> | <img src="assets/camera-high.jpg" width="230" alt="高机位结果" /> |

[查看案例说明 →](docs/examples.md)

以上为已有实验输出。白模是参考引导，相机球包含未见空间推测；修脸仍需检查身份、抖动和口型，不承诺每次生成达到相同效果。视频入口直达 MP4，浏览器可能打开播放或下载。

## 自己选择服务，按项目创作

支持的官方 API、API易、AtlasCloud 和自有 ComfyUI 汇集到同一工作台。我们鼓励使用官方 API，也让用户自行选择支持的第三方渠道。不必把全部创作固定在一家平台的年卡里。

**模型、模式、尺寸和价格随渠道而异。** API 生成费用由供应商收取，GPU 租用费用由算力服务方收取。

## 三步开始

1. **登录** [auvra.art](https://auvra.art/)。
2. **连接**自己的 API，或具备所需模型与依赖的远程 ComfyUI。
3. **新建项目**，加入参考素材，完成第一镜。

---

**[使用反馈](https://github.com/zakkaart88-debug/auvra-showcase/issues/new/choose)　·　[网站与合作咨询](https://auvra.art/)　·　[功能更新](docs/updates.md)**

这是产品展示仓库，**不是开源代码项目**。不包含应用源码、内部工作流、提示词策略或部署资料。请勿在公开反馈中提交密钥或私人素材。
