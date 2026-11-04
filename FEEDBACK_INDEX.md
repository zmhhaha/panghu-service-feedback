# 反馈总表

整理日期：2026-11-04。状态按最近一次有依据的记录填写；“历史待复测”不能解释为当前必现故障。维护者可引用稳定ID登记修复，再按验收场景补充复测结果。

跟踪入口：[视频 #1](https://github.com/zmhhaha/panghu-service-feedback/issues/1) · [PPT #2](https://github.com/zmhhaha/panghu-service-feedback/issues/2) · [科研 #3](https://github.com/zmhhaha/panghu-service-feedback/issues/3)。共28项待优化、建议或历史待复测条目，另保留已修复历史记录。

## 视频服务

最近体验2026-10-30；本会话无后续实现验收。下列优先级沿用当时用户建议，MP4和TTS属于原首版之后的能力规划。

2026-11-04 09:00 计划复测因本地浏览器工具启动故障未进入服务，见[执行阻塞记录](services/video-service/retest-2026-11-04.md)。VID-001～VID-010 状态未变，本次不新增产品缺陷。

| ID | 条目 | 优先级 | 状态 |
|---|---|---|---|
| [VID-001](services/video-service/README.md#vid-001) | 已采用镜头直接导出MP4 | P0 | 历史能力缺口，待复测 |
| [VID-002](services/video-service/README.md#vid-002) | 多镜头连续操作版本冲突 | P0 | 历史观察，待复测 |
| [VID-003](services/video-service/README.md#vid-003) | 批量生成、重试与采用 | P1 | 历史观察，待复测 |
| [VID-004](services/video-service/README.md#vid-004) | 长任务进度和失败信息 | P1 | 历史观察，待复测 |
| [VID-005](services/video-service/README.md#vid-005) | 输出尺寸等规格约束 | P1 | 历史观察，待复测 |
| [VID-006](services/video-service/README.md#vid-006) | 预览与采用版本辨识 | P1 | 历史观察，待复测 |
| [VID-007](services/video-service/README.md#vid-007) | 随讲解推进的架构动画 | P2 | 产品建议 |
| [VID-008](services/video-service/README.md#vid-008) | 逐镜头配音、同步、预览、有声导出 | P1 | OpenSpec已提案，未验证实现 |
| [VID-009](services/video-service/README.md#vid-009) | 音频版本与局部更新 | P1 | OpenSpec已提案，未验证实现 |
| [VID-010](services/video-service/README.md#vid-010) | 背景音乐和基础混音 | P2 | 提案第二阶段 |

## PPT服务

最近产物评价2026-11-03。原生下载和最终PPTX预览已可用，历史修复见[历史记录](services/ppt-service/history.md)。

| ID | 条目 | 优先级 | 状态 |
|---|---|---|---|
| [PPT-UX-001](services/ppt-service/README.md#ppt-ux-001) | 最终渲染断词、重叠、出框 | 高 | 11月3日实际观察，待优化 |
| [PPT-UX-002](services/ppt-service/README.md#ppt-ux-002) | 新旧版本及下载入口不易辨识 | 中 | 11月3日实际观察，待优化 |
| [PPT-CONTENT-001](services/ppt-service/README.md#ppt-content-001) | 术语解释和贯穿实例不足 | 中 | 内容改善建议 |
| [PPT-RECOVERY-001](services/ppt-service/history.md#ppt-recovery-001) | 质量失败诊断与局部恢复 | 待排期 | 历史故障路径待复测 |
| [PPT-UI-001](services/ppt-service/history.md#ppt-ui-001) | 下一步按钮与阶段不同步 | 待排期 | 历史异常待复测 |
| [PPT-EXPORT-001](services/ppt-service/history.md#ppt-export-001) | 审核转正式流程 | 待确认 | 最新路径未复核 |
| [PPT-EDIT-001](services/ppt-service/history.md#ppt-edit-001) | 图形连线跟随模块移动 | 可选 | 旧稿结构观察，新版未复核 |

## 科研服务

2026-11-04完成原生工作流后的新条目；旧SCI-001～007见下方历史区。

| ID | 条目 | 优先级 | 状态 |
|---|---|---|---|
| [SCI-008](services/scientific-agent/README.md#sci-008) | 官方资料与仓库正文获取 | 高 | 功能建议 |
| [SCI-009](services/scientific-agent/README.md#sci-009) | 低命中后自动调整检索 | 高 | 实际观察，待优化 |
| [SCI-010](services/scientific-agent/README.md#sci-010) | 生成时保留确认的固定案例 | 高 | 单次稿件已补救，产品级待验证 |
| [SCI-011](services/scientific-agent/README.md#sci-011) | 局部修订兼顾全篇长度 | 中 | 实际观察，待优化 |
| [SCI-012](services/scientific-agent/README.md#sci-012) | 减少重复限制说明 | 中 | 内容改善建议 |
| [SCI-013](services/scientific-agent/README.md#sci-013) | 等待和完成后的下一步提示 | 中 | 实际观察，待优化 |
| [SCI-014](services/scientific-agent/README.md#sci-014) | Word/PDF与可直接分享的导出 | 中 | 功能建议 |
| [SCI-015](services/scientific-agent/README.md#sci-015) | 检索批次预算与当前覆盖表达 | 低 | 实际观察，待优化 |
| [SCI-016](services/scientific-agent/README.md#sci-016) | 报告与页面时区口径一致 | 低 | 实际观察，待优化 |
| [SCI-017](services/scientific-agent/history.md#sci-017) | 导入稿结构化引用映射 | 待复测 | 10月31日历史观察 |
| [SCI-018](services/scientific-agent/history.md#sci-018) | 历史失败与当前定稿状态区分 | 待复测 | 10月31日历史观察 |

## 历史修复，避免重复报障

| 服务 | 历史问题 | 目前有依据的结论 |
|---|---|---|
| PPT | 大方案输入上限及错误提示 | 用户报告修复；随后主流程实际生成、下载成功，未独立审计服务器配置 |
| PPT | 相邻URL分隔导致阻塞 | 后续产物的两个来源链接独立完整；其他分隔符组合未复测 |
| PPT | 无原生下载、无最终PPTX预览 | 后续分别实际验证可用；新版渲染质量另见PPT-UX-001 |
| 科研SCI-001 | 证据整理失败 | 修复后本次路径通过，后续原生成文也完成 |
| 科研SCI-002 | 失败诊断不足 | 修复声明后部分界面复测通过，未逐类制造失败 |
| 科研SCI-003 | 旧证据不可见 | 实际复测可保留、查看和下载 |
| 科研SCI-004 | 缺少人工接管 | 导入稿路径实际通过；与原生写作分别记录 |
| 科研SCI-005 | 筛选相关性与日期 | 已改善、部分复测；新检索问题另列SCI-009 |
| 科研SCI-006 | 作者与日期信息 | 新7篇样本核对通过，原历史边界样本未全重验 |
| 科研SCI-007 | 文件与内部来源混淆 | 界面区分已改善，去重计数边界未全部覆盖 |

细节及验证边界分别见[PPT历史](services/ppt-service/history.md)和[科研历史](services/scientific-agent/history.md)。
