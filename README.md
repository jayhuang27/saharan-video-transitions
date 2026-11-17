# 🎬 Video Transitions Skill — by Saharan AI

**An open-source Agent Skill that teaches Claude Code, Codex and other AI agents 40 professional video transitions, with step-by-step recipes, durations, pitfalls and ready-to-use AI prompts.**

Built and maintained by **[Saharan AI](https://www.saharan.ai)**, the AI-native, end-to-end creative tool: one AI agent for the whole creative workflow, with expert agents on call and memory of your brand.

---

## What it does

Ask your agent things like:

- "What transition should I use between a product close-up and a city wide shot?"
- "Write a Seedance prompt that bridges the last frame of shot A into shot B through a doorway."
- "Implement a 0.4 s luma fade between these two clips in Remotion."
- "Give me an FFmpeg xfade command for a dip to black between A and B."

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

28 sources are cited, including Adobe docs, StudioBinder, Remotion, FFmpeg, gl-transitions, Runway and creator tutorials.

## Install

**Any agent (skills CLI)**

```bash
npx skills add jayhuang27/saharan-video-transitions
```

**Claude Code**

```bash
git clone https://github.com/jayhuang27/saharan-video-transitions
cp -r saharan-video-transitions/skills/video-transitions ~/.claude/skills/
```

**OpenAI Codex**

```bash
git clone https://github.com/jayhuang27/saharan-video-transitions
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
It depends on the cut. Describe A and B concretely, name one motion path, and fix the duration. This skill holds a prompt for each of 40 transitions; for a whip pan: *"A whips right into B whipping in from the same direction; cut at peak motion blur."*

**Can AI video models like Seedance, Kling, Veo or Runway make transitions?**
Yes, with first–last-frame or reference-image input (techniques 38–40). Frame-accurate timing, logos and subtitles are still best done in an editor or in code.

**How do I code a transition?**
Use Remotion's `@remotion/transitions`, FFmpeg `xfade`, or gl-transitions. Techniques tagged *Code AI* include prompts for these.

**Does it work in other languages?**
Yes. The agent replies in your language and can translate the prompt for the tool or model you use.

## About Saharan AI

[Saharan AI](https://www.saharan.ai) is an AI-native, end-to-end creative tool. One AI agent runs the whole creative workflow on one shared canvas: brainstorm, storyboard, produce, edit, deliver, approve and distribute. Expert agents, built on the skills of top creative directors, can join any stage with the full project context, and creative memory learns your brand's taste from every project. We open-source parts of the creative know-how behind it, like this skill.

→ **[www.saharan.ai](https://www.saharan.ai)**

## License & attribution

Content is licensed under [CC BY 4.0](LICENSE). You may use, adapt and redistribute it, including commercially, **as long as you credit**:

> Video Transitions skill by Saharan AI (https://www.saharan.ai), CC BY 4.0

Third-party sources remain the property of their owners and are linked, not reproduced.
