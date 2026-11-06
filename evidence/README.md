# 公开评价证据

这里只保存理解评价所需的产物和页面证据，不是完整研究原稿或全部服务导出。

## PPT最终渲染预览

- 目录：`ppt-2026-11-03/`。
- 产物生成：2026-11-02 22:28:12，北京时间。
- 下载和评价：2026-11-03。
- 来源：PPT服务页面明确标为“最终PPTX渲染预览”的图片。
- 文件：`05.png`、`06.png`、`08.png`，对应实际页码，未经重绘、文字修改或排版修正。
- 对应反馈：[PPT-UX-001](../services/ppt-service/README.md#ppt-ux-001)。

这些图片可以证明本次预览中观察到的排版现象，不能证明后续线上版本仍然有问题，也不代替桌面PowerPoint编辑与放映验证。

## 视频原生完整草稿、截帧与页面局部

- 目录：`video-2026-11-04/`，生成、下载及评价日期均为2026-11-04。
- [DSH-architecture-native-draft.mp4](video-2026-11-04/DSH-architecture-native-draft.mp4)：网站原生完整有声草稿，文稿版本59，11:02下载；174秒、2,819,035字节、1280×720、24fps、H.264＋AAC（24kHz单声道），全文件解码通过。原样复制，未站外重合成；正式导出及人工精确校时未完成。
- `shot01-finalframe.png`、`shot02-finalframe.png`、`shot06-finalframe.png`：分别从网站原生单镜MP4草稿第17、21、21秒提取，保持1280×720原始画面；未重绘、修改文字或修正排版。
- `batch-failure-public.png`：网站批次1进度页面的局部裁图，保留19/24项完成和前五镜的结果及提示；已排除无关项目侧栏，不是完整页面。
- `cross-shot-conflict-public.png`、`empty-selection-public.png`：分别保留跨镜头编辑版本冲突、空选择操作后连接中断的页面提示，只含当前项目和相关区域，未修改文字。裁图不单独证明操作前提或故障根因，需结合报告中的复现记录。
- `full-video-contact-sheet.png`：完整原生MP4的8镜抽帧总览，额外标注镜号和时间，画面内容未重绘；`full-video-playback-complete.png`为站内播放器174秒结束时的页面裁图，已去除外围无关区域。
- `full-shot08-173s.png`、`full-tail-173.75s.png`：原生完整MP4在173秒与173.75秒的画面，展示来源尾卡的清晰程度及结束前阅读时间，未修改文字或排版。
- 对应反馈：[VID-002](../services/video-service/README.md#vid-002)、[VID-004](../services/video-service/README.md#vid-004)、[VID-011](../services/video-service/README.md#vid-011)、[VID-012](../services/video-service/README.md#vid-012)，详情见[11月4日实测](../services/video-service/retest-2026-11-04.md)。

图片证明本次草稿的可读性现象和页面反馈；完整MP4证明本次实际取得的站内草稿内容。它们不代表正式成片或后续修订质量。截帧是原生产物的检查证据，不是网站额外导出格式，也不是站外重新合成的视频。

## 11月6日视频复测

- 目录：`video-2026-11-06/`，生成、下载和评价日期均为2026-11-06（北京时间）。
- [DSH-runtime-cycle-native-draft.mp4](video-2026-11-06/DSH-runtime-cycle-native-draft.mp4)：网站原生完整有声草稿，5镜头、文稿版本37，18:36下载；161秒、2,880,071字节、1280×720、24fps、H.264＋AAC（24kHz单声道）。原样复制，未站外重合成；SHA256为`d21f45d6fd4fe3261c9f45143a2404918b4877a4fc8693122935cc2ce94f873e`。
- `batch-result-public.png`：页面局部裁图，保留13/15及第1、4镜具体失败原因；`cross-shot-conflict-public.png`保留项目更新冲突提示；`output-specifications-public.png`保留720p/24fps说明和单镜版本信息。仅裁剪，未改字、重绘或修正页面；已排除无关项目侧栏。图片不能单独证明操作前提或后台根因。
- `full-video-contact-sheet.png`：5镜代表帧总览，增加镜号和时间标注；`final-5s-contact-sheet.png`为末5秒8个样本的总览。帧内内容保持原样，未重绘或修正排版。
- `full-video-playback-complete.png`：站内播放器2:41结束状态的局部裁图，保留草稿名称和版本37说明，去除外围无关区域，未修改页面文字。
- 对应[11月6日实测报告](../services/video-service/retest-2026-11-06.md)和[VID-001～012](../services/video-service/README.md)。历史附件继续保留，不将旧现象当作最新状态。

全文件解码、站内从0播放至结束和镜头边界抽样通过。音频测量与主体波形对应仅支持音轨存在、主体顺序和名义起点一致，逐段两端各0.15秒未纳入比较；未作主观试听、末字完整或人工精确同步通过声明。正式导出仍需人工试听确认，本次交付为草稿。
