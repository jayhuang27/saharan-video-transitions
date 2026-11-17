# 来源与 AI 实现资源 / Sources & Implementation Resources

> Retrieved 2026-11-15. 空白互动数 = 未核实，不是 0。Compiled by [Saharan AI](https://www.saharan.ai).

| ID | 类型 | 名称 | 能学到什么 | 热度 | 使用建议 |
|---|---|---|---|---|---|
| S04 | YouTube 原创教程 | [Peter McKinnon：MAKE YOUR OWN CAMERA TRANSITIONS!!](https://www.youtube.com/watch?v=_bwfAPXlFu8) | 实拍镜头转场灵感 | 👍71,000 / ▶1,303,826 | 高互动学习入口；本次未取得视频逐帧或完整字幕。 |
| S05 | YouTube 原创教程 | [Peter McKinnon：Fast & Easy LUMA FADE TRANSITION!](https://www.youtube.com/watch?v=1Qm1EGxdZ6E) | 亮度溶解 | 👍36,000 / ▶783,022 | 高互动教程；具体技术同时参照 Adobe 官方说明。 |
| S28 | YouTube 原创教程 | [Premiere Gal：SEAMLESS TRANSITIONS with Generative Fill](https://www.youtube.com/watch?v=fxRbUrYp9Bw) | 生成式填充辅助场景衔接 | 👍1,200 / ▶38,218 | 用于学习AI补画面思路；本次未获取完整字幕。 |
| S01 | 专业文章 | [StudioBinder：Types of Editing Transitions in Film](https://www.studiobinder.com/blog/types-of-editing-transitions-in-film/) | 基础剪辑、淡化、隐形切、叙事用途 | — | 用于理解剪辑语言，避免每个切点都加特效。 |
| S02 | 专业文章 | [StudioBinder：Match Cuts & Creative Transitions](https://www.studiobinder.com/blog/match-cuts-creative-transitions-examples/) | 形状、色彩、动作、声音匹配 | — | 先设计两个镜头的共同元素，再做匹配。 |
| S03 | 官方文档 | [Adobe：Create J and L cuts](https://helpx.adobe.com/premiere/desktop/edit-projects/trim-clips/perform-j-cuts-and-l-cuts.html) | 声音先入、声音延续 | — | 需要独立调整音频和画面的剪辑点。 |
| S06 | 官方文档 | [Adobe：Luma fade transition effect](https://www.adobe.com/creativecloud/video/hub/features/why-use-a-luma-fade.html) | 按亮度顺序显露下一画面 | — | 高反差素材更易看出亮度分层。 |
| S07 | 官方文档 | [Adobe：Modern transitions in Premiere](https://helpx.adobe.com/premiere/desktop/add-video-effects/types-of-effects/transitions.html) | 叠化、闪白、旋转、故障等效果 | — | 核对所在软件版本是否包含该效果。 |
| S08 | 官方文档 | [Adobe：Create action speed ramps](https://www.adobe.com/creativecloud/video/hub/guides/premiere-pro-speed-ramp.html) | 时间重映射与变速 | — | 慢动作需要足够源帧率；具体速度曲线按素材调整。 |
| S09 | 官方文档 | [Adobe：Morph Cut overview](https://helpx.adobe.com/uk/premiere/desktop/add-video-effects/apply-video-transitions/morph-cut-overview.html) | 采访口播的跳切修补 | — | 最适合静态背景中的单人近似构图。 |
| S10 | 官方教程 | [Adobe：Build custom transitions](https://www.adobe.com/learn/after-effects/web/create-custom-transitions) | 用蒙版和关键帧制作自定义擦除 | — | 适合品牌色块和图形转场。 |
| S11 | 原创教程 | [tutvid：Create a Light Leak Transition](https://tutvid.com/premiere-pro/create-light-leak-transition-premiere-pro/) | 漏光素材叠加 | — | 素材需覆盖切点，混合方式按素材黑底与亮度调整。 |
| S12 | 专业文章 | [StudioBinder：Swish Pan / Whip Pan](https://www.studiobinder.com/blog/swish-pan-whip-pan-definition-film/) | 甩镜的拍摄与用途 | — | 两端镜头方向与模糊程度应相近。 |
| S13 | 官方文档 | [Remotion：@remotion/transitions](https://www.remotion.dev/docs/transitions/) | 代码实现 fade、wipe、slide、cube 等 | — | 用 TransitionSeries 管理场景重叠；各包版本保持一致。 |
| S14 | GitHub AI skills | [remotion-dev/skills](https://github.com/remotion-dev/skills) | 官方视频代码生成与渲染 skills | ⭐7,223 | 参考安装：npx skills add remotion-dev/skills。提示词：用 Remotion 将 A、B 做0.4秒擦除，输出可编辑代码与预览。 |
| S15 | GitHub 库及 AI skill | [gl-transitions/gl-transitions](https://github.com/gl-transitions/gl-transitions) | 100+ GLSL 转场及 Agent Skill | ⭐2,252 | skill 位于 skills/gl-transitions/SKILL.md。提示词：用 gl-transitions 实现 A→B 的 Cube，0.5秒，检查首中末帧。 |
| S16 | GitHub 渲染工具 | [transitive-bullshit/ffmpeg-gl-transition](https://github.com/transitive-bullshit/ffmpeg-gl-transition) | 用 FFmpeg 调用 GLSL 转场 | ⭐722 | 不是独立AI skill；通常需要定制FFmpeg构建。提示词：检查滤镜可用性后，为A、B生成0.5秒GLSL转场命令。 |
| S17 | 官方文档 | [FFmpeg：xfade](https://ffmpeg.org/ffmpeg-filters.html#xfade) | 批量视频转场滤镜 | — | 输入需统一尺寸、帧率、时间基等。提示词：统一A、B参数，使用xfade做0.5秒淡化，另处理音频衔接。 |
| S18 | YouTube 原创教程 | [StudioBinder：Ultimate Guide to Scene Transitions](https://www.youtube.com/watch?v=TKXBAaQB03U) | 电影场景转场示例 | — | 配套S01阅读；不把频道粉丝数当成视频点赞。 |
| S19 | YouTube 原创教程 | [Daniel Schiffer：FILMING SMOOTH TRANSITIONS](https://www.youtube.com/watch?v=1dr_qpnommw) | 商品B-roll实拍衔接 | — | 作为观摩入口，不据此声称已看完教程或确认具体动作。 |
| S20 | Bilibili 教程 | [保姆级无缝转场教学：10分钟教会你3种转场](https://www.bilibili.com/video/BV1eK4y1R7tC/) | 中文无缝转场入门 | — | 中文学习入口，不以搜索排序代表专业质量排名。 |
| S21 | YouTube 原创教程 | [Cinecom.net：5 INSANE TRANSITIONS!](https://www.youtube.com/watch?v=8TCjk94XBCI) | 创意转场观摩 | — | 用于拓展风格；本次未核对完整教学内容。 |
| S22 | 原创教程 | [Kyler Holland：Object Mask Transitions](https://www.kylerholland.com/blog/object-mask-transitions-premiere-pro/) | 跟踪主体蒙版后分层转场 | — | 需要对象蒙版工具；背景和主体分层，防止效果溢出。 |
| S23 | 研究论文 | [MatchDiffusion：Training-free Generation of Match-cuts](https://arxiv.org/abs/2411.18677) | 生成式匹配剪辑研究 | — | 是研究方法，不代表任意视频模型仅靠一句提示词就能复现。 |
| S24 | 官方指南 | [Runway：Image to Video Prompting Guide](https://help.runwayml.com/hc/en-us/articles/48324313115155-Image-to-Video-Prompting-Guide) | 描述运动、由上一段末帧继续生成 | — | 本表生成式prompt为改写建议；首尾帧支持取决于具体模型。 |
| S25 | 官方代码 | [Runway SDK：image_to_video](https://github.com/runwayml/sdk-python/blob/main/src/runwayml/resources/image_to_video.py) | 首帧与可选尾帧输入能力 | — | 给模型提供A末帧与B首帧；先确认所选模型与接口参数支持。 |
| S26 | 社交讨论 | [Reddit：How do I do this dissolving transition](https://www.reddit.com/r/premiere/comments/1hoap6w) | 社区对亮度蒙版的辨认 | — | 仅作为术语与需求线索，操作依据使用S06、S10。 |
| S27 | YouTube 官方教程 | [Adobe Live：Light Leak Transitions](https://www.youtube.com/watch?v=vF64-jXd1Ek) | 漏光转场示范 | — | 与S11结合学习；不把频道粉丝数作为作品热度。 |

## 使用说明 / Method notes

- **项目:** 说明
- **检索范围:** 跨平台检索中英文专业文章、官方文档、YouTube、Bilibili、Reddit及GitHub。共整理40种技巧和28个资源入口。这是精选库，不是全网穷尽清单或点赞总排名。
- **如何选择:** 叙事与对白先看硬切、动作接切、J/L cut。实拍旅行或商品片看匹配剪辑、甩镜、遮挡、变速。图形视频看擦除、推屏。缺少过渡镜头时再考虑生成式衔接。
- **Prompt使用:** 将A、B替换为素材名或镜头描述，再复制对应Prompt。指定实际使用的软件或模型。剪辑AI需能编辑时间线；代码AI需渲染代码；生成式视频AI需能接收相应参考图。
- **参数口径:** 所有建议时长、步骤细化和Prompt均为基于资料的编辑建议，不是原作者逐字指令，也未在具体AI模型上逐条测试。秒数是试剪起点，应按节奏与帧率调整。
- **来源对应:** 主表的来源编号对应资源表。主要来源提供技术概念或实现依据，附加来源可能是教程观摩入口。仅有搜索摘要或打不开的视频已在资源表注明。
- **热度口径:** 优先收录能核实的高互动原创教程。YouTube数值来自检索时可见的搜索索引，可能滞后约2个月；GitHub stars来自当日API。点赞、播放、stars不合并评分。
- **空白数值:** 未公开、未取得或不能可靠核实的互动数留空。频道粉丝数、账号累计获赞、第三方估算不替代单条作品点赞。
- **检索日期:** 2026-11-15。日期是本次查阅时间，不代表所有网页和统计数据都在当天更新。
- **来源质量:** 技术做法优先参照官方文档、创作者教程及专业文章。社区帖子用于发现术语和问题。高点赞说明传播热度，不能单独证明方法适合当前素材。
- **AI资源区别:** Remotion skills和GL Transitions内的SKILL.md是代理指导资源。GLSL库、FFmpeg滤镜和研究论文分别属于代码资源、渲染工具和研究方法，不能一概当作可安装skill。
- **素材准备:** 转场两侧留足额外素材。需要匹配的镜头尽量统一运动方向、主体落点、曝光与白平衡。声音转场必须检查音轨，不靠画面效果替代。
- **生成式边界:** 生成式Prompt需要筛选和修剪成片，可能出现形体、文字与身份漂移。精确卡帧、字幕、logo及音画同步优先在剪辑或代码工具中完成。
