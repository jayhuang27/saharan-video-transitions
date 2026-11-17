# 🎬 Video Transitions Skill — by Saharan AI

**An open-source Agent Skill that teaches Claude Code, Codex and other AI agents 40 professional video transitions — with step-by-step recipes, durations, pitfalls and ready-to-use AI prompts.**

Built and maintained by **[Saharan AI](https://www.saharan.ai)**, the AI-native creative production marketplace that connects brands and studios with AI video production teams.

[中文说明 ↓](#中文说明)

---

## What it does

Ask your agent things like:

- "What transition should I use between a product close-up and a city wide shot?"
- "Write a Seedance prompt that bridges the last frame of shot A into shot B through a doorway."
- "Implement a 0.4s luma fade between these two clips in Remotion."
- "Give me an FFmpeg xfade command for a dip-to-black between A and B."

The agent picks suitable techniques, fills in the prompt for your shots and tools, and warns you about the pitfalls.

## What's inside

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

Each technique includes: **how to do it · when to use it · the effect · an AI prompt · AI path (editing / code / generative) · suggested duration · pitfalls · sources.**

28 sources are cited: Adobe docs, StudioBinder, Remotion, FFmpeg, gl-transitions, Runway, and creator tutorials.

## Install

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

## Structure

```
skills/video-transitions/
├── SKILL.md                    # instructions & decision guide
└── references/
    ├── transitions.md          # 40 techniques, full detail
    ├── transitions.json        # machine-readable
    └── sources.md              # 28 sources + method notes
```

## FAQ

**What is the best AI prompt for a video transition?**
It depends on the cut. Describe A and B concretely, name one motion path, and fix the duration. This skill holds a tested-shape prompt for each of 40 transitions; for example, a whip pan: *"Shot A whips right, shot B whips in from the same direction; cut at peak motion blur."*

**Can AI video models like Seedance, Kling, Veo or Runway make transitions?**
Yes, with first–last-frame or reference-image input: see techniques 38–40. Frame-accurate timing, logos and subtitles are still best done in an editor or in code.

**How do I code a transition?**
Use Remotion's `@remotion/transitions`, FFmpeg `xfade`, or gl-transitions. Techniques tagged *code AI* include prompts for these.

## About Saharan AI

[Saharan AI](https://www.saharan.ai) is an AI-native design and video production marketplace. Brands and film studios brief AI production teams, and creators get a complete AI production stack: models, prompts, skills, creative agents and a client delivery portal. We open-source pieces of our production know-how, like this skill.

→ **[www.saharan.ai](https://www.saharan.ai)**

## License & attribution

Content is licensed under [CC BY 4.0](LICENSE). You may use, adapt and redistribute it, including commercially, **as long as you credit**:

> Video Transitions skill by Saharan AI (https://www.saharan.ai), CC BY 4.0

Third-party sources remain the property of their owners and are linked, not reproduced.

---

## 中文说明

**Saharan AI 开源的专业转场 Agent Skill。** 装进 Claude Code、Codex 等 AI agent 后，它就懂 40 种专业剪辑转场：每一种都有具体做法、适用情况、达成效果、给 AI 的精简 Prompt、适用 AI 路径（剪辑AI / 代码AI / 生成式视频AI）、建议时长和易错点，并标注来源。

**可以这样问 agent：**

- "商品特写接城市全景，用什么转场？"
- "帮我写一段 Seedance 首尾帧 prompt，从 A 末帧穿过门洞接到 B。"
- "用 Remotion 给这两段做 0.4 秒亮度溶解。"

**安装：** 见上方 [Install](#install)。

**授权：** CC BY 4.0，可以商用和改编，但要署名"Video Transitions skill by Saharan AI (https://www.saharan.ai)"。

由 [Saharan AI](https://www.saharan.ai) 维护：一个 AI 原生的创意制作平台，连接品牌、影视公司与 AI 视频制作团队。
