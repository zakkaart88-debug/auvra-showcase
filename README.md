<div align="center">

# AUVRA

### 你的 API，你的影像创作工作台

连接自己的 API 与 ComfyUI，把素材、镜头和生成结果留在同一张画布。

**[开始创作](https://auvra.art/)　·　[English](docs/README.en.md)　·　[快速开始](docs/quick-start.md)　·　[更新记录](docs/updates.md)**

</div>

---

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
