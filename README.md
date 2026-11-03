# Panghu 服务用户反馈

集中整理 **2026-10-30～2026-11-04** 同一次使用会话中，对视频、PPT、科研服务的真实体验、产物评价和优化建议。由用户授权整理发布，供各服务维护者直接阅读和跟踪。

**这里同时保留问题和已经验证的改善。历史失败不代表当前仍失败，提案通过也不代表功能已实现。**

## 各服务直接入口

| 服务 | 最近一次实际体验 | 当前结论 | 评价入口 |
|---|---|---|---|
| [视频服务](https://video-service.panghuer.top/) | 2026-10-30 | 分镜、画面和素材导出可用；成片与音频为后续需求，未取得后续复测记录 | [视频评价与10项建议](services/video-service/README.md) |
| [PPT服务](https://ppt-service.panghuer.top/) | 2026-11-03 | 原生PPTX下载及最终渲染预览已可用；新版多页仍有断词、重叠和出框 | [最新评价](services/ppt-service/README.md) · [历史修复](services/ppt-service/history.md) |
| [科研服务](https://scientific-agent.panghuer.top/) | 2026-11-04 | 原生生成、修订、定稿已走通；关键资料获取、需求保留、精炼与导出仍需优化 | [最新评价](services/scientific-agent/README.md) · [历史修复](services/scientific-agent/history.md) |
| [OpenSpec](https://openspec.panghuer.top/) | 2026-10-30 | 已用于保存视频音频提案；没有独立、完整的服务评测 | [反馈渠道使用记录](services/openspec/README.md) |

## 先看这些问题

- **PPT排版：[PPT-UX-001](services/ppt-service/README.md#ppt-ux-001)**。最终PPTX渲染的第5、6、8页出现重叠或出框，第2、9页存在英文断词。验收应看最终PPTX，不能只看源SVG。
- **科研需求保留：[SCI-010](services/scientific-agent/README.md#sci-010)**。确认方案指定的文件和问题在初稿中丢失；本次稿件通过修订补救，但还需验证产品能否自动保留要求。
- **科研资料覆盖：[SCI-008](services/scientific-agent/README.md#sci-008)、[SCI-009](services/scientific-agent/README.md#sci-009)**。给出官方仓库仍未取得正文，首批复杂查询漏掉核心论文，需要使用者主动调整。
- **视频音频闭环：[VID-008](services/video-service/README.md#vid-008)、[VID-009](services/video-service/README.md#vid-009)**。逐镜头配音、试听采用、音画字幕同步及有声MP4已记入OpenSpec，尚无实现验收记录。

完整列表见 **[反馈总表](FEEDBACK_INDEX.md)**。条目中有观察日期、影响、建议与验收条件；不必回看原始会话才能理解。

## 跟踪 Issue

| 服务 | 跟踪入口 | 范围 |
|---|---|---|
| 视频服务 | [#1 历史体验与音频提案复测](https://github.com/zmhhaha/panghu-service-feedback/issues/1) | VID-001～010，共10项；历史观察、产品建议与提案验收 |
| PPT服务 | [#2 最新产物排版、版本辨识与内容改进](https://github.com/zmhhaha/panghu-service-feedback/issues/2) | 共7项；最新体验与历史待复测路径分别记录 |
| 科研服务 | [#3 检索覆盖、需求保留、修订与导出](https://github.com/zmhhaha/panghu-service-feedback/issues/3) | SCI-008～018，共11项；SCI-001～007保留在历史修复记录 |

维护者可在对应 Issue 中关联修复提交、部署版本及复测证据，再同步更新文档状态。

## 已经验证的进展

- PPT：后续实际取得原生10页PPTX；2026-11-03已能查看网站标明的最终PPTX渲染预览。“无下载”和“无最终渲染预览”不再列为当前问题。
- 科研：旧证据可保留和下载；2026-11-04在未导入自写稿的情况下，完整完成原生写作、章节修订、采用、定稿及下载。
- 科研引用：本次7篇实际引用的题名、作者、版本和摘要能对应原始摘要页。此项没有验证论文全文或软件实现。
- 视频：站内画面生成、明确采用、素材导出已经完成。会话交付的MP4是外部合成，不能作为站内MP4导出成功的证据。

## 如何使用本仓库

1. 服务维护者先打开对应服务页面，按稳定条目ID定位问题。
2. 在 Issues 中记录实现与部署进度，引用条目ID；一个修复PR可关联多个条目，但应逐项给出验收结果。
3. “已部署”先记为修复声明；正常用户路径复测后再更新验证状态。一次成功不自动关闭其他失败场景。
4. 更新对应文档和总表，保留历史日期、旧结论及复测范围。

填写规则和状态含义见 [CONTRIBUTING.md](CONTRIBUTING.md)。仓库提供统一Issue模板；提交反馈时选择服务并说明观察和期望结果。

## 记录范围

日期均按北京时间（Asia/Shanghai）理解，论文原始日期等例外会明确注明。优先级代表本次用户影响建议，不是维护者承诺。

这是使用记录与评价仓库，包含普通页面操作、下载产物检查以及明确标记的用户修复报告；不是服务端审计或全面质量认证。公开归档保留必要事实与复现条件，完整会话、内部任务记录及研究原稿没有作为评价附件发布。

最后整理：**2026-11-04**。服务之后可能继续变化，请以各条目的最新复测日期为准。
