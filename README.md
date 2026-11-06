# Panghu 服务用户反馈

集中整理 **2026-10-30～2026-11-06** 同一次使用会话中，对视频、PPT、科研服务的真实体验、产物评价和优化建议。由用户授权整理发布，供各服务维护者直接阅读和跟踪。

**这里同时保留问题和已经验证的改善。历史失败不代表当前仍失败，提案通过也不代表功能已实现。**

## 各服务直接入口

| 服务 | 最近一次实际体验 | 当前结论 | 评价入口 |
|---|---|---|---|
| [视频服务](https://video-service.panghuer.top/) | 2026-11-06（两次） | 白天取得原生完整有声草稿2:41；晚间新题材5镜中4镜成功，第3镜图解过密致整片失败；状态同步与图解预算待改 | [视频评价与15项跟踪](services/video-service/README.md) · [11月6日实测](services/video-service/retest-2026-11-06.md) · [晚间实测](services/video-service/retest-2026-11-06-https.md) |
| [PPT服务](https://ppt-service.panghuer.top/) | 2026-11-03 | 原生PPTX下载及最终渲染预览已可用；新版多页仍有断词、重叠和出框 | [最新评价](services/ppt-service/README.md) · [历史修复](services/ppt-service/history.md) |
| [科研服务](https://scientific-agent.panghuer.top/) | 2026-11-04 | 原生生成、修订、定稿已走通；关键资料获取、需求保留、精炼与导出仍需优化 | [最新评价](services/scientific-agent/README.md) · [历史修复](services/scientific-agent/history.md) |
| [OpenSpec](https://openspec.panghuer.top/) | 2026-10-30 | 已用于保存视频音频提案；没有独立、完整的服务评测 | [反馈渠道使用记录](services/openspec/README.md) |

## 先看这些问题

- **PPT排版：[PPT-UX-001](services/ppt-service/README.md#ppt-ux-001)**。最终PPTX渲染的第5、6、8页出现重叠或出框，第2、9页存在英文断词。验收应看最终PPTX，不能只看源SVG。
- **科研需求保留：[SCI-010](services/scientific-agent/README.md#sci-010)**。确认方案指定的文件和问题在初稿中丢失；本次稿件通过修订补救，但还需验证产品能否自动保留要求。
- **科研资料覆盖：[SCI-008](services/scientific-agent/README.md#sci-008)、[SCI-009](services/scientific-agent/README.md#sci-009)**。给出官方仓库仍未取得正文，首批复杂查询漏掉核心论文，需要使用者主动调整。
- **视频制作恢复：[VID-004](services/video-service/README.md#vid-004)**。11月6日首批15项中13项成功，3/5镜头草稿成功；失败原因已明确为文字超区、关系过密，简化图解后恢复。仍需让自动生成的方案直接满足渲染限制，减少用户返工。
- **视频图解可读性：[VID-012](services/video-service/README.md#vid-012)**。最新草稿的流程折返、标签拥挤、包含关系不直观；来源已提前出现且保留版本日期，但完整URL丢失。跨镜更新冲突亦再次复现，见[VID-002](services/video-service/README.md#vid-002)。
- **视频图解密度：[VID-015](services/video-service/README.md#vid-015)**。11月6日晚间题材的第3镜自动图解8节点9关系，单镜两次、整片一次校验失败，整片未取得；页面只给问题编号，简化请求对生成无效。
- **视频写操作静默失败：[VID-013](services/video-service/README.md#vid-013)**。采用方案、采用候选、制作整片三次请求返回409而页面无提示，只有整页刷新后才出现结果；后台标签页期间进度也不更新，见[VID-014](services/video-service/README.md#vid-014)。

完整列表见 **[反馈总表](FEEDBACK_INDEX.md)**。条目中有观察日期、影响、建议与验收条件；不必回看原始会话才能理解。

## 跟踪 Issue

| 服务 | 跟踪入口 | 范围 |
|---|---|---|
| 视频服务 | [#1 DSH实测、渲染恢复与图解质量](https://github.com/zmhhaha/panghu-service-feedback/issues/1) | VID-001～016，共16项；11月6日两次实测（DSH运行循环、HTTPS请求旅程）、11月4日复测与历史观察 |
| PPT服务 | [#2 最新产物排版、版本辨识与内容改进](https://github.com/zmhhaha/panghu-service-feedback/issues/2) | 共7项；最新体验与历史待复测路径分别记录 |
| 科研服务 | [#3 检索覆盖、需求保留、修订与导出](https://github.com/zmhhaha/panghu-service-feedback/issues/3) | SCI-008～018，共11项；SCI-001～007保留在历史修复记录 |

维护者可在对应 Issue 中关联修复提交、部署版本及复测证据，再同步更新文档状态。

## 已经验证的进展

- PPT：后续实际取得原生10页PPTX；2026-11-03已能查看网站标明的最终PPTX渲染预览。“无下载”和“无最终渲染预览”不再列为当前问题。
- 科研：旧证据可保留和下载；2026-11-04在未导入自写稿的情况下，完整完成原生写作、章节修订、采用、定稿及下载。
- 科研引用：本次7篇实际引用的题名、作者、版本和摘要能对应原始摘要页。此项没有验证论文全文或软件实现。
- 视频：11月4日取得[原生完整有声MP4草稿](evidence/video-2026-11-04/DSH-architecture-native-draft.mp4)，8镜头、2:54、720p，站内播放至结束，全文件解码通过。第7镜局部改稿后只重生成该镜配音。正式导出和人工精确校时未完成；10月30日的外部合成MP4仍只作为历史交付记录。
- 视频：11月6日再次取得[原生完整有声MP4草稿](evidence/video-2026-11-06/DSH-runtime-cycle-native-draft.mp4)，5镜头、2:41、720p，全文件解码通过；第1、4镜仅改画面、保留原配音。空选择校验、720p规格说明、单镜版本标识和阶段进度均有实际改善。正式导出与主观试听、人工精确校时未完成。
- 视频：同日晚间另做《一次HTTPS请求的旅程》，[4段原生单镜草稿](evidence/video-2026-11-06-https/shot-01-strip-address.mp4)合计175秒、720p、解码通过；讲解方案主动纠正了原稿中“200表示有新内容”等表述。**整片未取得**：第3镜图解元素过密，单镜两次、整片一次校验失败，见[晚间实测](services/video-service/retest-2026-11-06-https.md)。

## 如何使用本仓库

1. 服务维护者先打开对应服务页面，按稳定条目ID定位问题。
2. 在 Issues 中记录实现与部署进度，引用条目ID；一个修复PR可关联多个条目，但应逐项给出验收结果。
3. “已部署”先记为修复声明；正常用户路径复测后再更新验证状态。一次成功不自动关闭其他失败场景。
4. 更新对应文档和总表，保留历史日期、旧结论及复测范围。

填写规则和状态含义见 [CONTRIBUTING.md](CONTRIBUTING.md)。仓库提供统一Issue模板；提交反馈时选择服务并说明观察和期望结果。

## 记录范围

日期均按北京时间（Asia/Shanghai）理解，论文原始日期等例外会明确注明。优先级代表本次用户影响建议，不是维护者承诺。

这是使用记录与评价仓库，包含普通页面操作、下载产物检查以及明确标记的用户修复报告；不是服务端审计或全面质量认证。公开归档保留必要事实与复现条件，完整会话、内部任务记录及研究原稿没有作为评价附件发布。

最后整理：**2026-11-06**。服务之后可能继续变化，请以各条目的最新复测日期为准。
