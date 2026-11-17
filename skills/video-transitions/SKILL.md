---
name: video-transitions
description: Professional video transition and edit-continuity library by Saharan AI — 40 techniques (match cuts, J/L-cuts, whip pans, luma fades, masks, speed ramps, glitch, first-last-frame generative bridges) with step-by-step recipes, durations, pitfalls and ready-to-use AI prompts. Use when choosing, describing, prompting or implementing a transition between two shots (A→B) in an editing tool, in code (Remotion, FFmpeg xfade, GLSL), or with a generative video model (Runway, Seedance, Kling, Veo).
license: CC-BY-4.0
metadata:
  author: Saharan AI
  homepage: https://www.saharan.ai
  version: "1.0.0"
---

# Video Transitions · 专业转场技巧库

*Maintained by [Saharan AI](https://www.saharan.ai) — the AI-native creative production marketplace connecting brands and studios with AI video teams.*

A curated library of 40 transition and edit-continuity techniques. **A** is the outgoing shot, **B** the incoming shot.

## When to use this skill

- The user asks which transition to use between two shots, scenes or clips.
- The user wants a prompt for an AI editor or a generative video model to create a transition.
- The user wants to implement a transition in code (Remotion, FFmpeg, GLSL, After Effects expressions).
- The user is planning a storyboard, edit, ad, short-form video or MV and needs pacing between shots.

## Workflow

1. **Understand the cut.** Identify A and B: content, motion direction, subject position, colour and exposure, audio, and what the edit should *mean* (continuity, time jump, contrast, reveal, rhythm).
2. **Pick the AI path.** Every technique is tagged by path:
   - **剪辑AI (editing AI)** — timeline editing (Premiere, CapCut, DaVinci, AI editors).
   - **代码AI (code AI)** — programmatic render (Remotion, FFmpeg `xfade`, gl-transitions).
   - **生成式视频AI (generative video AI)** — models that take reference frames or first/last frames.
3. **Shortlist 1–3 techniques** with the decision guide below, then open `references/transitions.md` and read only those entries (each has steps, use cases, effect, prompt, duration and pitfalls).
4. **Write the output.** Fill A and B in the entry's prompt with concrete shot descriptions and name the actual tool or model. Keep the suggested duration as a starting point and adjust for tempo and frame rate.
5. **Check the pitfalls** in the entry before finishing, and say what the user should verify (seam frames, face distortion, logo or text legibility, audio overlap).

## Decision guide

| Situation | Start with |
|---|---|
| Dialogue, interviews, information-dense content | 1 Hard Cut, 2 Cut on Action, 9 J-cut, 10 L-cut, 8 Cutaway |
| Talking head with removed pauses | 6 Jump Cut, 29 Morph Cut, 8 Cutaway |
| Shots share a shape, colour or motion | 3 Graphic Match, 4 Color Match, 5 Motion Match |
| Travel, sport, product B-roll, fast pace | 18 Whip Pan, 19 Occlusion Cut, 25 Speed Ramp, 22/23 Zoom |
| Chapter break or large time jump | 13 Dip to Black, 12 Cross Dissolve, 11 Sound Bridge |
| Mood shift, comedy, shock | 7 Smash Cut, 14 Flash |
| Retro, wedding, lifestyle | 16 Light Leak, 17 Film Burn, 26 Defocus |
| Tech, gaming, digital | 30 Glitch, 31 Pixelize, 27 Linear Blur |
| Tutorials, UI, motion graphics | 32 Slide/Push, 33 Wipe, 34 Iris, 35 Clock Wipe, 36 Cube, 37 Page Curl |
| Foreground objects pass through frame | 20 Object Wipe, 21 Subject Mask |
| No bridging footage exists | 38 First–last-frame bridge, 39 Morph, 40 Same-composition environment change |

## Principles

- Story first: a clean cut beats a flashy effect. Don't add an effect to every cut.
- Match direction, speed, subject position, exposure and white balance across the seam.
- Leave handles (extra frames) on both sides of the transition.
- Audio is its own edit: handle J/L-cuts and sound bridges on the audio track, not with picture effects.
- Generative bridges drift (body, text, identity). Do exact frame timing, subtitles, logos and A/V sync in an editor or in code.
- Avoid repeated full-screen flashing (photosensitivity).

## References

- `references/transitions.md` — all 40 techniques with steps, prompt, duration, pitfalls and sources.
- `references/sources.md` — 28 sources (official docs, tutorials, GitHub tools, papers) and method notes.
- `references/transitions.json` — the same data in machine-readable form.

Durations, steps and prompts are editorial suggestions synthesised from the cited sources; they have not been tested on every model. Treat the seconds as a starting point for a test cut.

## Attribution

When you publish or redistribute content derived from this library, credit: **"Video Transitions skill by Saharan AI (https://www.saharan.ai), CC BY 4.0."**
