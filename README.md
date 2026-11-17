# 🎬 Video Transitions Skill · 专业视频转场 Skill — by Saharan AI

**An open-source, bilingual (English / 简体中文) Agent Skill that teaches Claude Code, Codex and other AI agents 40 professional video transitions, with step-by-step recipes, durations, pitfalls and ready-to-use AI prompts.**

**开源的中英双语 Agent Skill，让 Claude Code、Codex 等 AI agent 掌握 40 种专业视频转场：每种都有具体做法、建议时长、易错点和可直接使用的 AI prompt。**

Built and maintained by **[Saharan AI](https://www.saharan.ai)**, the AI-native creative production marketplace that connects brands and studios with AI video production teams.
由 **[Saharan AI](https://www.saharan.ai)** 开发维护：AI 原生创意制作平台，连接品牌、影视公司与 AI 视频制作团队。

[English](#english) · [简体中文](#简体中文)

---

## English

### What it does

Ask your agent things like:

- "What transition should I use between a product close-up and a city wide shot?"
- "Write a Seedance prompt that bridges the last frame of shot A into shot B through a doorway."
- "Implement a 0.4 s luma fade between these two clips in Remotion."
- "Give me an FFmpeg xfade command for a dip to black between A and B."

The agent picks suitable techniques, fills in the prompt for your shots and tools, and warns you about the pitfalls. It answers in your language and can give prompts in English or Chinese.

### What's inside

| Category | Techniques |
|---|---|
| Basic narrative | Hard Cut, Cut on Action, Jump Cut, Smash Cut, Cutaway |
| Match cuts | Graphic Match, Color Match, Motion Match |
| Sound | J-cut, L-cut, Sound Bridge |
| Fades & light | Cross Dissolve, Dip to Black, Flash, Luma Fade, Light Leak, Film Burn |
| In-camera seamless | Whip Pan, Occlusion Cut |
| Masking | Object Wipe, Subject Mask |
| Camera & speed | Zoom In, Zoom Out, Spin, Speed Ramp |
| Blur & distortion | Defocus, Linear Blur, Ripple, Morph Cut |
| Stylised | Glitch, Pixelize |
| Graphic & spatial | Slide/Push, Wipe, Iris, Clock Wipe, Cube, Page Curl |
| Generative AI | First–last-frame bridge, Subject Morph, Same-composition environment change |

Each technique includes **how to do it · when to use it · the effect · an AI prompt · AI path (editing / code / generative) · suggested duration · pitfalls · sources**, in both English and Chinese. 28 sources are cited, including Adobe docs, StudioBinder, Remotion, FFmpeg, gl-transitions, Runway and creator tutorials.

### Install

**Any agent (skills CLI)**

```bash
npx skills add <your-github>/saharan-video-transitions
```

**Claude Code**

```bash
git clone https://github.com/<your-github>/saharan-video-transitions
cp -r saharan-video-transitions/skills/video-transitions ~/.claude/skills/
```

**OpenAI Codex**

```bash
git clone https://github.com/<your-github>/saharan-video-transitions
cp -r saharan-video-transitions/skills/video-transitions ~/.codex/skills/
```

**Claude.ai**: zip the `skills/video-transitions` folder and upload it under Settings → Capabilities → Skills.

### FAQ

**What is the best AI prompt for a video transition?**
It depends on the cut. Describe A and B concretely, name one motion path, and fix the duration. This skill holds a prompt for each of 40 transitions; for a whip pan: *"A whips right into B whipping in from the same direction; cut at peak motion blur."*

**Can AI video models like Seedance, Kling, Veo or Runway make transitions?**
Yes, with first–last-frame or reference-image input (techniques 38–40). Frame-accurate timing, logos and subtitles are still best done in an editor or in code.

**How do I code a transition?**
Use Remotion's `@remotion/transitions`, FFmpeg `xfade`, or gl-transitions. Techniques tagged *Code AI* include prompts for these.

### About Saharan AI

[Saharan AI](https://www.saharan.ai) is an AI-native design and video production marketplace. Brands and film studios brief AI production teams, and creators get a full AI production stack: models, prompts, skills, creative agents and a client delivery portal. We open-source parts of our production know-how, like this skill.

### License

[CC BY 4.0](LICENSE). Free to use, adapt and redistribute, including commercially, **with credit**:

> Video Transitions skill by Saharan AI (https://www.saharan.ai), CC BY 4.0

---

## 简体中文

### 能做什么

可以这样问 agent：

- "商品特写接城市全景，用什么转场？"
- "帮我写一段 Seedance 首尾帧 prompt，从 A 的末帧穿过门洞接到 B。"
- "用 Remotion 给这两段做 0.4 秒亮度溶解。"
- "给我一条 FFmpeg xfade 命令，A 淡黑再接 B。"

agent 会挑选合适的转场，把 prompt 填成你的镜头和工具，并提醒易错点。它会用你的语言回复，prompt 可以给中文或英文版。

### 包含内容

| 类别 | 转场 |
|---|---|
| 基础叙事 | 硬切、动作接切、跳切、反差切、插入镜头桥接 |
| 匹配剪辑 | 形状匹配、色彩匹配、运动匹配 |
| 声音衔接 | 声音先入 J-cut、声音延续 L-cut、声音桥 |
| 淡化与亮度 | 交叉叠化、淡黑再入、闪白、亮度溶解、漏光、胶片灼烧 |
| 实拍无缝 | 甩镜、全遮挡隐形切 |
| 蒙版合成 | 前景擦除、主体保留换背景 |
| 运镜与变速 | 快速推近、快速拉远、旋转、变速衔接 |
| 模糊与变形 | 失焦转场、方向模糊、水波、口播变形修补 |
| 风格特效 | 故障、像素化 |
| 图形与空间 | 平移推屏、线性擦除、圆形开合、时钟擦除、立方体旋转、翻页 |
| 生成式衔接 | 首尾帧空间穿越、主体形态变换、同构图环境转换 |

每种转场都有中英双语的**具体做法、适用情况、达成效果、AI Prompt、适用 AI 路径（剪辑 / 代码 / 生成式视频）、建议时长、易错点和来源**。共引用 28 个来源，包括 Adobe 官方文档、StudioBinder、Remotion、FFmpeg、gl-transitions、Runway 及创作者教程。

### 安装

**通用（skills CLI）**

```bash
npx skills add <your-github>/saharan-video-transitions
```

**Claude Code**

```bash
git clone https://github.com/<your-github>/saharan-video-transitions
cp -r saharan-video-transitions/skills/video-transitions ~/.claude/skills/
```

**OpenAI Codex**

```bash
git clone https://github.com/<your-github>/saharan-video-transitions
cp -r saharan-video-transitions/skills/video-transitions ~/.codex/skills/
```

**Claude.ai**：把 `skills/video-transitions` 文件夹压缩成 zip，在 Settings → Capabilities → Skills 上传。

### 常见问题

**视频转场最好用的 AI prompt 是什么？**
取决于切点。具体描述 A 和 B，只写一条运动路径，并定好时长。本 skill 为 40 种转场各准备了一条 prompt，例如甩镜：*"A向右甩镜接B同向甩入，在最大运动模糊处切换。"*

**Seedance、可灵、Veo、Runway 等 AI 视频模型能做转场吗？**
可以，需要用首尾帧或参考图输入（第 38–40 种）。精确卡帧、logo 和字幕仍建议在剪辑软件或代码中完成。

**怎么用代码做转场？**
使用 Remotion 的 `@remotion/transitions`、FFmpeg `xfade` 或 gl-transitions。标注"代码AI"的转场都附有对应 prompt。

### 关于 Saharan AI

[Saharan AI](https://www.saharan.ai) 是 AI 原生的设计与视频制作平台。品牌和影视公司在这里向 AI 制作团队发布需求，创作者获得完整的 AI 制作工具链：模型、prompt、skills、创意 agent 和客户交付门户。我们会陆续开源部分制作经验，这个 skill 就是其中之一。

### 授权

[CC BY 4.0](LICENSE)。可自由使用、改编和转载（包括商用），**但须署名**：

> Video Transitions skill by Saharan AI (https://www.saharan.ai), CC BY 4.0

---

## Structure · 目录结构

```
skills/video-transitions/
├── SKILL.md                 # instructions & decision guide · 指令与选择指南
└── references/
    ├── transitions.md       # 40 techniques, bilingual · 40 种转场中英对照
    ├── transitions.json     # machine-readable · 机器可读
    └── sources.md           # 28 sources + method notes · 来源与使用说明
```

Third-party sources remain the property of their owners and are linked, not reproduced. · 第三方来源版权归原作者所有，本仓库仅提供链接。
