---
name: video-transitions
description: Bilingual (English / 简体中文) professional video transition library by Saharan AI — 40 techniques (match cuts, J/L-cuts, whip pans, luma fades, masks, speed ramps, glitch, first–last-frame generative bridges) with step-by-step recipes, durations, pitfalls and ready-to-use AI prompts in both languages. Use when choosing, describing, prompting or implementing a transition between two shots (A→B) in an editor, in code (Remotion, FFmpeg xfade, GLSL), or with a generative video model (Runway, Seedance, Kling, Veo). 专业视频转场技巧库：选择、描述、编写 prompt 或实现两个镜头之间的转场时使用。
license: CC-BY-4.0
metadata:
  author: Saharan AI
  homepage: https://www.saharan.ai
  version: "1.1.0"
  languages: "en, zh-Hans"
---

# Video Transitions · 专业视频转场技巧库

*Maintained by [Saharan AI](https://www.saharan.ai) — the AI-native creative production marketplace connecting brands and studios with AI video teams.*
*由 [Saharan AI](https://www.saharan.ai) 维护：AI 原生创意制作平台，连接品牌、影视公司与 AI 视频制作团队。*

40 transition and edit-continuity techniques, every field in English and Simplified Chinese. **A** = outgoing shot, **B** = incoming shot.
40 种转场及剪辑衔接技巧，每个字段都有中英双语。**A** = 前一镜头，**B** = 后一镜头。

## Language · 语言

Reply in the user's language. Each technique has a prompt in both English (`en`) and Simplified Chinese (`zh`). Use the prompt language that suits the target tool or model, or the one the user asks for.
用用户的语言回复。每种转场都有英文和简体中文 prompt，按目标工具或模型的需要选择，用户指定时按用户要求。

## When to use · 何时使用

- Choosing a transition between two shots, scenes or clips. · 为两个镜头、场景或片段选择转场。
- Writing a prompt for an AI editor or generative video model. · 为剪辑 AI 或生成式视频模型编写转场 prompt。
- Implementing a transition in code (Remotion, FFmpeg, GLSL, After Effects). · 用代码实现转场。
- Planning a storyboard, ad, short video or music video. · 规划分镜、广告、短视频或 MV 的镜头衔接。

## Workflow · 工作流程

1. **Understand the cut · 理解切点**: content, motion direction, subject position, colour and exposure, audio, and what the edit should mean (continuity, time jump, contrast, reveal, rhythm). · A、B 的内容、运动方向、主体位置、色彩曝光、声音，以及这次衔接要表达什么。
2. **Pick the AI path · 选择 AI 路径**:
   - **Editing AI · 剪辑AI**: timeline editing (Premiere, CapCut, DaVinci, AI editors). · 时间线剪辑。
   - **Code AI · 代码AI**: programmatic render (Remotion, FFmpeg `xfade`, gl-transitions). · 代码渲染。
   - **Generative video AI · 生成式视频AI**: models that accept reference or first/last frames. · 能接收参考图或首尾帧的模型。
3. **Shortlist 1–3 techniques · 选出 1–3 种** with the decision guide below, then read only those entries in `references/transitions.md`. · 按下方选择指南筛选，只读取对应条目。
4. **Write the output · 输出**: fill A and B in the prompt with concrete shot descriptions and name the real tool or model. Treat the duration as a starting point for a test cut. · 把 A、B 换成具体镜头描述，写明实际工具或模型；时长是试剪起点。
5. **Check pitfalls · 检查易错点** and tell the user what to verify (seam frames, faces, logos and text, audio overlap). · 提醒用户需要核对的地方。

## Decision guide · 选择指南

| Situation · 情境 | Start with · 优先考虑 |
|---|---|
| Dialogue, interviews · 对白、访谈 | 1 Hard Cut 硬切, 2 Cut on Action 动作接切, 9 J-cut 声音先入, 10 L-cut 声音延续, 8 Cutaway 插入镜头 |
| Talking head with pauses removed · 口播删停顿 | 6 Jump Cut 跳切, 29 Morph Cut 口播变形修补, 8 Cutaway |
| Shared shape, colour or motion · 镜头有共同形状/色彩/运动 | 3 Graphic Match 形状匹配, 4 Color Match 色彩匹配, 5 Motion Match 运动匹配 |
| Travel, sport, product B-roll · 旅行、运动、商品 B-roll | 18 Whip Pan 甩镜, 19 Occlusion Cut 遮挡隐形切, 25 Speed Ramp 变速, 22/23 Zoom 推拉 |
| Chapter break, time jump · 段落分隔、时间跨度 | 13 Dip to Black 淡黑, 12 Cross Dissolve 叠化, 11 Sound Bridge 声音桥 |
| Mood shift, comedy, shock · 情绪反转、喜剧、冲击 | 7 Smash Cut 反差切, 14 Flash 闪白 |
| Retro, wedding, lifestyle · 复古、婚礼、生活方式 | 16 Light Leak 漏光, 17 Film Burn 胶片灼烧, 26 Defocus 失焦 |
| Tech, gaming · 科技、游戏 | 30 Glitch 故障, 31 Pixelize 像素化, 27 Linear Blur 方向模糊 |
| Tutorials, UI, motion graphics · 教程、界面、图形动效 | 32 Slide 推屏, 33 Wipe 擦除, 34 Iris 圆形开合, 35 Clock Wipe 时钟擦除, 36 Cube 立方体, 37 Page Curl 翻页 |
| Foreground passes through frame · 前景物体经过画面 | 20 Object Wipe 前景擦除, 21 Subject Mask 主体保留换背景 |
| No bridging footage · 缺少过渡素材 | 38 First–last-frame bridge 首尾帧穿越, 39 Morph 形态变换, 40 Environment change 同构图环境转换 |

## Principles · 原则

- Story first: a clean cut beats a flashy effect. · 叙事优先，不要每个切点都加特效。
- Match direction, speed, subject position, exposure and white balance across the seam. · 切点两侧统一方向、速度、主体位置、曝光和白平衡。
- Leave handles on both sides. · 转场两侧留足素材。
- Audio is its own edit; handle J/L-cuts on the audio track. · 声音单独处理，不靠画面效果替代。
- Generative bridges drift (body, text, identity); do exact timing, subtitles, logos and A/V sync in an editor or in code. · 生成式衔接会漂移；精确卡帧、字幕、logo 和音画同步在剪辑或代码工具中完成。
- Avoid repeated full-screen flashing. · 避免大面积连续闪烁。

## References · 参考文件

- `references/transitions.md` — 40 techniques, bilingual table per entry. · 40 种转场，逐条中英对照。
- `references/sources.md` — 28 sources and method notes. · 28 个来源与使用说明。
- `references/transitions.json` — machine-readable, `zh` / `en` fields. · 机器可读版本。

Durations, steps and prompts are editorial suggestions synthesised from the cited sources, not tested on every model. · 时长、步骤和 prompt 均为基于资料的编辑建议，未在所有模型上逐条测试。

## Attribution · 署名

When publishing or redistributing derived content, credit: **"Video Transitions skill by Saharan AI (https://www.saharan.ai), CC BY 4.0."**
发布或转载衍生内容时请署名：**"Video Transitions skill by Saharan AI (https://www.saharan.ai), CC BY 4.0"**。
