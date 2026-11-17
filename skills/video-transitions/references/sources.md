# 来源与 AI 实现资源 · Sources & Implementation Resources

> 检索日期 Retrieved: 2026-11-15 · 由 [Saharan AI](https://www.saharan.ai) 整理 · Compiled by Saharan AI
> 互动数空白 = 未核实，不是 0 · A blank figure means unverified, not zero.

| ID | 类型 · Type | 名称 · Title | 能学到什么 · What you learn | 热度 · Popularity | 使用建议 · Notes |
|---|---|---|---|---|---|
| S04 | YouTube 原创教程<br>YouTube tutorial | [Peter McKinnon：MAKE YOUR OWN CAMERA TRANSITIONS!!](https://www.youtube.com/watch?v=_bwfAPXlFu8) | 实拍镜头转场灵感<br>Ideas for in-camera transitions | 👍 71,000 / ▶ 1,303,826 | 高互动学习入口；本次未取得视频逐帧或完整字幕。<br>High-engagement entry point; frame-by-frame video or full transcript not obtained. |
| S05 | YouTube 原创教程<br>YouTube tutorial | [Peter McKinnon：Fast & Easy LUMA FADE TRANSITION!](https://www.youtube.com/watch?v=1Qm1EGxdZ6E) | 亮度溶解<br>Luma fade | 👍 36,000 / ▶ 783,022 | 高互动教程；具体技术同时参照 Adobe 官方说明。<br>High-engagement tutorial; cross-check technique against Adobe's official docs. |
| S28 | YouTube 原创教程<br>YouTube tutorial | [Premiere Gal：SEAMLESS TRANSITIONS with Generative Fill](https://www.youtube.com/watch?v=fxRbUrYp9Bw) | 生成式填充辅助场景衔接<br>Generative fill to help bridge scenes | 👍 1,200 / ▶ 38,218 | 用于学习AI补画面思路；本次未获取完整字幕。<br>For learning the AI frame-extension idea; full transcript not obtained. |
| S01 | 专业文章<br>Professional article | [StudioBinder：Types of Editing Transitions in Film](https://www.studiobinder.com/blog/types-of-editing-transitions-in-film/) | 基础剪辑、淡化、隐形切、叙事用途<br>Basic cuts, fades, invisible cuts, narrative purpose | — | 用于理解剪辑语言，避免每个切点都加特效。<br>For understanding editing language; avoid adding an effect to every cut. |
| S02 | 专业文章<br>Professional article | [StudioBinder：Match Cuts & Creative Transitions](https://www.studiobinder.com/blog/match-cuts-creative-transitions-examples/) | 形状、色彩、动作、声音匹配<br>Shape, colour, action and sound matching | — | 先设计两个镜头的共同元素，再做匹配。<br>Design the shared element between the two shots first, then match. |
| S03 | 官方文档<br>Official docs | [Adobe：Create J and L cuts](https://helpx.adobe.com/premiere/desktop/edit-projects/trim-clips/perform-j-cuts-and-l-cuts.html) | 声音先入、声音延续<br>Audio leading and audio trailing | — | 需要独立调整音频和画面的剪辑点。<br>Requires independently adjustable audio and video edit points. |
| S06 | 官方文档<br>Official docs | [Adobe：Luma fade transition effect](https://www.adobe.com/creativecloud/video/hub/features/why-use-a-luma-fade.html) | 按亮度顺序显露下一画面<br>Revealing the next shot in luminance order | — | 高反差素材更易看出亮度分层。<br>Brightness layering is easier to see on high-contrast footage. |
| S07 | 官方文档<br>Official docs | [Adobe：Modern transitions in Premiere](https://helpx.adobe.com/premiere/desktop/add-video-effects/types-of-effects/transitions.html) | 叠化、闪白、旋转、故障等效果<br>Dissolve, flash, spin, glitch and other effects | — | 核对所在软件版本是否包含该效果。<br>Check whether your software version includes the effect. |
| S08 | 官方文档<br>Official docs | [Adobe：Create action speed ramps](https://www.adobe.com/creativecloud/video/hub/guides/premiere-pro-speed-ramp.html) | 时间重映射与变速<br>Time remapping and speed changes | — | 慢动作需要足够源帧率；具体速度曲线按素材调整。<br>Slow motion needs enough source frame rate; adjust the speed curve to the footage. |
| S09 | 官方文档<br>Official docs | [Adobe：Morph Cut overview](https://helpx.adobe.com/uk/premiere/desktop/add-video-effects/apply-video-transitions/morph-cut-overview.html) | 采访口播的跳切修补<br>Fixing jump cuts in talking-head interviews | — | 最适合静态背景中的单人近似构图。<br>Works best for a single person in similar framing against a static background. |
| S10 | 官方教程<br>Official tutorial | [Adobe：Build custom transitions](https://www.adobe.com/learn/after-effects/web/create-custom-transitions) | 用蒙版和关键帧制作自定义擦除<br>Custom wipes with masks and keyframes | — | 适合品牌色块和图形转场。<br>Good for brand colour blocks and graphic transitions. |
| S11 | 原创教程<br>Creator tutorial | [tutvid：Create a Light Leak Transition](https://tutvid.com/premiere-pro/create-light-leak-transition-premiere-pro/) | 漏光素材叠加<br>Overlaying light-leak footage | — | 素材需覆盖切点，混合方式按素材黑底与亮度调整。<br>The footage must cover the cut; adjust blend mode for black background and brightness. |
| S12 | 专业文章<br>Professional article | [StudioBinder：Swish Pan / Whip Pan](https://www.studiobinder.com/blog/swish-pan-whip-pan-definition-film/) | 甩镜的拍摄与用途<br>Shooting and using whip pans | — | 两端镜头方向与模糊程度应相近。<br>Direction and blur amount should be similar on both shots. |
| S13 | 官方文档<br>Official docs | [Remotion：@remotion/transitions](https://www.remotion.dev/docs/transitions/) | 代码实现 fade、wipe、slide、cube 等<br>Code implementations of fade, wipe, slide, cube, etc. | — | 用 TransitionSeries 管理场景重叠；各包版本保持一致。<br>Manage scene overlap with TransitionSeries; keep package versions aligned. |
| S14 | GitHub AI skills<br>GitHub AI skills | [remotion-dev/skills](https://github.com/remotion-dev/skills) | 官方视频代码生成与渲染 skills<br>Official skills for video code generation and rendering | ⭐ 7,223 | 参考安装：npx skills add remotion-dev/skills。提示词：用 Remotion 将 A、B 做0.4秒擦除，输出可编辑代码与预览。<br>Install: npx skills add remotion-dev/skills. Prompt: use Remotion to do a 0.4 s wipe from A to B, output editable code and a preview. |
| S15 | GitHub 库及 AI skill<br>GitHub library & AI skill | [gl-transitions/gl-transitions](https://github.com/gl-transitions/gl-transitions) | 100+ GLSL 转场及 Agent Skill<br>100+ GLSL transitions and an Agent Skill | ⭐ 2,252 | skill 位于 skills/gl-transitions/SKILL.md。提示词：用 gl-transitions 实现 A→B 的 Cube，0.5秒，检查首中末帧。<br>Skill at skills/gl-transitions/SKILL.md. Prompt: use gl-transitions to implement a Cube from A to B, 0.5 s, check first, middle and last frames. |
| S16 | GitHub 渲染工具<br>GitHub render tool | [transitive-bullshit/ffmpeg-gl-transition](https://github.com/transitive-bullshit/ffmpeg-gl-transition) | 用 FFmpeg 调用 GLSL 转场<br>Calling GLSL transitions from FFmpeg | ⭐ 722 | 不是独立AI skill；通常需要定制FFmpeg构建。提示词：检查滤镜可用性后，为A、B生成0.5秒GLSL转场命令。<br>Not a standalone AI skill; usually needs a custom FFmpeg build. Prompt: check filter availability, then generate a 0.5 s GLSL transition command for A and B. |
| S17 | 官方文档<br>Official docs | [FFmpeg：xfade](https://ffmpeg.org/ffmpeg-filters.html#xfade) | 批量视频转场滤镜<br>Batch video transition filter | — | 输入需统一尺寸、帧率、时间基等。提示词：统一A、B参数，使用xfade做0.5秒淡化，另处理音频衔接。<br>Inputs need matching size, frame rate, timebase, etc. Prompt: unify A and B parameters, use xfade for a 0.5 s fade, handle the audio join separately. |
| S18 | YouTube 原创教程<br>YouTube tutorial | [StudioBinder：Ultimate Guide to Scene Transitions](https://www.youtube.com/watch?v=TKXBAaQB03U) | 电影场景转场示例<br>Film scene transition examples | — | 配套S01阅读；不把频道粉丝数当成视频点赞。<br>Read alongside S01; don't treat channel subscribers as video likes. |
| S19 | YouTube 原创教程<br>YouTube tutorial | [Daniel Schiffer：FILMING SMOOTH TRANSITIONS](https://www.youtube.com/watch?v=1dr_qpnommw) | 商品B-roll实拍衔接<br>In-camera transitions for product B-roll | — | 作为观摩入口，不据此声称已看完教程或确认具体动作。<br>For viewing only; we don't claim to have watched the whole tutorial or confirmed specific moves. |
| S20 | Bilibili 教程<br>Bilibili tutorial | [保姆级无缝转场教学：10分钟教会你3种转场](https://www.bilibili.com/video/BV1eK4y1R7tC/) | 中文无缝转场入门<br>Intro to seamless transitions (Chinese) | — | 中文学习入口，不以搜索排序代表专业质量排名。<br>Chinese-language entry point; search ranking doesn't represent professional quality. |
| S21 | YouTube 原创教程<br>YouTube tutorial | [Cinecom.net：5 INSANE TRANSITIONS!](https://www.youtube.com/watch?v=8TCjk94XBCI) | 创意转场观摩<br>Creative transition showcase | — | 用于拓展风格；本次未核对完整教学内容。<br>For broadening style; full tutorial content not verified. |
| S22 | 原创教程<br>Creator tutorial | [Kyler Holland：Object Mask Transitions](https://www.kylerholland.com/blog/object-mask-transitions-premiere-pro/) | 跟踪主体蒙版后分层转场<br>Layered transitions with a tracked subject mask | — | 需要对象蒙版工具；背景和主体分层，防止效果溢出。<br>Needs an object-mask tool; separate background and subject so the effect doesn't spill. |
| S23 | 研究论文<br>Research paper | [MatchDiffusion：Training-free Generation of Match-cuts](https://arxiv.org/abs/2411.18677) | 生成式匹配剪辑研究<br>Research on generative match cuts | — | 是研究方法，不代表任意视频模型仅靠一句提示词就能复现。<br>A research method; doesn't mean any video model can reproduce it with one prompt. |
| S24 | 官方指南<br>Official guide | [Runway：Image to Video Prompting Guide](https://help.runwayml.com/hc/en-us/articles/48324313115155-Image-to-Video-Prompting-Guide) | 描述运动、由上一段末帧继续生成<br>Describing motion; continuing generation from the previous clip's last frame | — | 本表生成式prompt为改写建议；首尾帧支持取决于具体模型。<br>Generative prompts here are adapted suggestions; first/last-frame support depends on the model. |
| S25 | 官方代码<br>Official code | [Runway SDK：image_to_video](https://github.com/runwayml/sdk-python/blob/main/src/runwayml/resources/image_to_video.py) | 首帧与可选尾帧输入能力<br>First-frame and optional last-frame input | — | 给模型提供A末帧与B首帧；先确认所选模型与接口参数支持。<br>Give the model A's last frame and B's first frame; confirm the model and API support it. |
| S26 | 社交讨论<br>Community discussion | [Reddit：How do I do this dissolving transition](https://www.reddit.com/r/premiere/comments/1hoap6w) | 社区对亮度蒙版的辨认<br>Community identification of luma mattes | — | 仅作为术语与需求线索，操作依据使用S06、S10。<br>Only a lead on terms and needs; use S06 and S10 for the actual technique. |
| S27 | YouTube 官方教程<br>YouTube official tutorial | [Adobe Live：Light Leak Transitions](https://www.youtube.com/watch?v=vF64-jXd1Ek) | 漏光转场示范<br>Light-leak transition demo | — | 与S11结合学习；不把频道粉丝数作为作品热度。<br>Learn together with S11; don't treat channel subscribers as content popularity. |

## 使用说明 · Method notes

**检索范围 · Scope**

- 跨平台检索中英文专业文章、官方文档、YouTube、Bilibili、Reddit及GitHub。共整理40种技巧和28个资源入口。这是精选库，不是全网穷尽清单或点赞总排名。
- Cross-platform search of Chinese and English professional articles, official docs, YouTube, Bilibili, Reddit and GitHub. 40 techniques and 28 resource entries. This is a curated library, not an exhaustive list or a ranking by likes.

**如何选择 · How to choose**

- 叙事与对白先看硬切、动作接切、J/L cut。实拍旅行或商品片看匹配剪辑、甩镜、遮挡、变速。图形视频看擦除、推屏。缺少过渡镜头时再考虑生成式衔接。
- For narrative and dialogue, start with hard cut, cut on action and J/L-cuts. For travel or product footage, look at match cuts, whip pans, occlusion and speed ramps. For motion graphics, look at wipes and pushes. Consider generative bridges only when bridging footage is missing.

**Prompt使用 · Using the prompts**

- 将A、B替换为素材名或镜头描述，再复制对应Prompt。指定实际使用的软件或模型。剪辑AI需能编辑时间线；代码AI需渲染代码；生成式视频AI需能接收相应参考图。
- Replace A and B with clip names or shot descriptions, then copy the prompt. Name the actual software or model. Editing AI must be able to edit a timeline; code AI must render code; generative video AI must accept the relevant reference images.

**参数口径 · About the parameters**

- 所有建议时长、步骤细化和Prompt均为基于资料的编辑建议，不是原作者逐字指令，也未在具体AI模型上逐条测试。秒数是试剪起点，应按节奏与帧率调整。
- All suggested durations, detailed steps and prompts are editorial suggestions based on the sources, not verbatim instructions from the original authors, and have not been tested one by one on specific AI models. Seconds are a starting point for a test cut; adjust for pace and frame rate.

**来源对应 · Source mapping**

- 主表的来源编号对应资源表。主要来源提供技术概念或实现依据，附加来源可能是教程观摩入口。仅有搜索摘要或打不开的视频已在资源表注明。
- Source IDs in the main table map to the sources table. The main source provides the technical concept or implementation basis; additional sources may be viewing entry points. Entries with only search snippets or unavailable videos are noted.

**热度口径 · About popularity figures**

- 优先收录能核实的高互动原创教程。YouTube数值来自检索时可见的搜索索引，可能滞后约2个月；GitHub stars来自当日API。点赞、播放、stars不合并评分。
- High-engagement original tutorials that could be verified are prioritised. YouTube figures come from search-index snapshots and may lag by about two months; GitHub stars come from the API on the retrieval date. Likes, views and stars are not combined into a score.

**空白数值 · Blank values**

- 未公开、未取得或不能可靠核实的互动数留空。频道粉丝数、账号累计获赞、第三方估算不替代单条作品点赞。
- Engagement figures that are not public, not obtained or not reliably verifiable are left blank. Channel subscribers, total account likes and third-party estimates are not used as single-video likes.

**检索日期 · Retrieval date**

- 2026-11-15。日期是本次查阅时间，不代表所有网页和统计数据都在当天更新。
- 2026-11-15. This is when sources were consulted; it doesn't mean every page or figure was updated that day.

**来源质量 · Source quality**

- 技术做法优先参照官方文档、创作者教程及专业文章。社区帖子用于发现术语和问题。高点赞说明传播热度，不能单独证明方法适合当前素材。
- Techniques follow official docs, creator tutorials and professional articles first. Community posts are used to discover terms and problems. High likes show reach but don't by themselves prove a method suits your footage.

**AI资源区别 · AI resource types**

- Remotion skills和GL Transitions内的SKILL.md是代理指导资源。GLSL库、FFmpeg滤镜和研究论文分别属于代码资源、渲染工具和研究方法，不能一概当作可安装skill。
- Remotion skills and the SKILL.md in GL Transitions are agent guidance resources. The GLSL library, FFmpeg filters and research papers are code resources, render tools and research methods respectively, and should not all be treated as installable skills.

**素材准备 · Footage prep**

- 转场两侧留足额外素材。需要匹配的镜头尽量统一运动方向、主体落点、曝光与白平衡。声音转场必须检查音轨，不靠画面效果替代。
- Leave enough handles on both sides of a transition. Shots to be matched should share motion direction, subject position, exposure and white balance where possible. Sound transitions need the audio tracks checked; picture effects don't replace them.

**生成式边界 · Limits of generative video**

- 生成式Prompt需要筛选和修剪成片，可能出现形体、文字与身份漂移。精确卡帧、字幕、logo及音画同步优先在剪辑或代码工具中完成。
- Generative prompts require selecting and trimming results; body, text and identity may drift. Do frame-accurate timing, subtitles, logos and A/V sync in an editing or code tool first.
