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

## 11月6日晚间视频复测（未取得整片）

- 目录：`video-2026-11-06-https/`，生成、下载和评价日期均为2026-11-06（北京时间）。
- `shot-01-strip-address.mp4`、`shot-02-find-address.mp4`、`shot-04-http-exchange.mp4`、`shot-05-render.mp4`：网站原生单镜有声MP4草稿，分别29、49、44、53秒，1280×720、24fps、H.264＋AAC（24kHz单声道），全部全文件解码通过。原样复制，未站外重合成。第3镜单镜草稿未成功，因此没有对应文件，也没有整片文件。
- `batch-14of15-public.png`：批次1页面局部裁图，保留“部分未完成 · 14/15”及第3镜“本步骤未完成”的通用提示；`film-failure-public.png`保留整片草稿在“第 3/5 镜 · 校验镜头产物”失败与问题编号 MR-ec821ed84ba8506c，同时可见该镜两次单镜失败编号。仅裁剪侧栏，未改字或重绘。
- `shots-contact-sheet.png`：四段单镜各取45%与85%时刻的总览，额外标注镜号与时间，画面内容未重绘。
- `shot02-overlap-42s.png`、`shot04-clipping-38s.png`、`shot05-empty-end-52s.png`：分别取第2镜42秒、第4镜38秒、第5镜52.6秒的原始1280×720帧，用于说明标签折行与节点贴合、容器边缘裁切、结尾空帧；帧内内容保持原样。
- 对应[晚间实测报告](../services/video-service/retest-2026-11-06-https.md)与[VID-012～015](../services/video-service/README.md)。四段产物证明本次实际取得的单镜草稿内容与可读性现象，不证明整片连贯性、正式导出或主观听感。

全文件解码通过；音频只做数字电平与元数据检查（平均−27.6～−28.0dB、峰值−10.7～−11.3dB），未作主观试听、语音自然度或人工精确校时声明。

## 2026-11-07 服务更新后重跑（同一项目，取得整片）

- 目录：`video-2026-11-07/`，生成、下载与评价日期均为2026-11-07（北京时间）。
- [https-journey-native-draft-v2.mp4](video-2026-11-07/https-journey-native-draft-v2.mp4)：网站原生整片有声草稿，5镜头、文稿版本46，01:28下载；204秒、3,441,568字节、1280×720、24fps、H.264＋AAC（24kHz单声道），全文件解码通过，SHA256 `d8aa9200a45864f99960dd6ac3904cf8b3ef861de9e94946e41a7f2e0adb6fce`。原样下载，未站外重合成。
- `contact-sheet-v2.png`：六处代表帧（第2镜60/75秒，第3镜88/100秒，第4镜140秒，第5镜200秒），只加时间标注，画面内容未重绘。
- `shot03-clean-handshake-100s.png`：第3镜新版图解的原始1280×720帧，三次握手排成一条水平线并带结论条。
- `shot02-grouped-servers-75s.png`：第2镜新版图解的原始帧，三类服务器已合并为一个节点，但标签仍与卡片重叠、贴右边界。
- `shot05-empty-end-200s.png`：第5镜末帧，仍为接近空白的画面，只剩“关键路径等待”与回顾链。
- 对应[晚间实测的“服务更新后重跑”一节](../services/video-service/retest-2026-11-06-https.md#2026-11-07-服务更新后重跑)与[VID-015](../services/video-service/README.md#vid-015)。

本次只验证“同一项目重跑能出整片”与第3镜画面改善，不代表第2、4、5镜的排版问题已解决，也不代表正式导出或主观听感通过。

全文件解码通过；音频只做元数据检查（AAC 24kHz 单声道），未作主观试听、语音自然度或人工精确校时声明。
