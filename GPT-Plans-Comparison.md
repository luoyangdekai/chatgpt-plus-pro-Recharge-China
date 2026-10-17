# ChatGPT 套餐权益对比 | Codex 模型权益与额度

> 最后更新：2026-10-17
> 本文根据 OpenAI 官方公开信息整理，适合快速比较 ChatGPT 各套餐的定位、模型、工具与适用人群；额度折算另附社区实测来源。
> 说明：模型名称、功能开放范围与使用限额可能随 OpenAI 调整，请以账号内实际显示及官方页面为准。
> 本次已复核价格、Work / Codex 模型与使用规则、桌面 Live。带 **†** 的 Chat 权益保留自 2026-9-9 原文，尚未核实当前情况，仅供历史参考。

---

## 国内充值入口：

👉 [便捷国内 ChatGPT Plus / Pro 充值入口](https://wzyp.cn/shop/3F5YOW2H)

## 🚀 一张表看懂各套餐

| 套餐 | 官方参考价格* | 模型能力（Work / Codex） | 高级推理 | 综合用量（Work / Codex） | 更适合 |
| --- | --- | --- | --- | --- | --- |
| Free | $0 | GPT-6 Luna（桌面端，逐步开放） | 以可选档位为准 | 基础 | 偶尔使用、轻度问答 |
| Go | $8/月 | GPT-6 Luna（桌面端，逐步开放） | 以可选档位为准 | 以账号显示为准 | 日常高频聊天、低成本升级 |
| Plus | $20/月 | GPT-6 Astra、GPT-6.1 Sol、GPT-6 Sol、GPT-6 Luna | ✅ 按模型选择推理档位 | 有 5 小时窗口，另可能有周限额 | 学习、办公、科研、编程、内容创作 |
| Pro $100 | $100/月 | 同 Plus | ✅ 按模型选择推理档位 | 当前无 5 小时限额；仍受套餐额度限制 | 重度个人用户、专业工作流 |
| Pro $200 | $200/月 | 同 Plus | ✅ 按模型选择推理档位 | 当前无 5 小时限额；新旧订阅需区分 | 极高频专业使用、更高额度需求 |
| Pro $500 | $500/月 | 同 Plus；Astra / 6.1 Sol 支持 Ultrafast | ✅ 按模型选择推理档位 | 当前无 5 小时限额；仍受套餐额度限制 | 极高频专业使用、追求更快响应 |

*价格为 OpenAI 官方公开参考价格，实际结算可能因国家/地区、税费、币种、订阅渠道或促销而不同。Go 的 $8/月为美元参考价。Business 通常至少需要 2 个付费席位。*

> 原文的“Pro 5× / Pro 20×”改为按月费区分。当前官方价格页不再给出统一的 Plus 倍数，不能把旧称直接当作今天的额度承诺。价格及使用规则见 [OpenAI 官方资料](https://learn.chatgpt.com/docs/pricing)，Ultrafast 见 [速度说明](https://learn.chatgpt.com/docs/agent-configuration/speed)。

---

## 💰 套餐额度折算（社区实测）

> 以下为 Codex 用户根据实际 Token 与 Usage 百分比反推的 API 等价价值，并非 OpenAI 官方承诺的美元余额。不同模型、缓存比例、速度模式和任务会影响结果，不能统一换算成套餐内固定的 Credits。

| 套餐 | 订阅价格 | 实测依据 | API 等价价值 / 周 | API 等价价值 / 月* |
| --- | --- | --- | --- | --- |
| Plus | $20/月 | Wokey：10 个账号，10 月 1–8 日，网关流量样本 | 中位数 ≈ $92；中间一半账号 $77–107 | 中位数 ≈ $399；对应 $334–464 |
| Pro $100 | $100/月 | InventiveHQ：同一用户 2 个窗口，三台机器日志合并，Sol 为主 | ≈ $330–380 | ≈ $1,430–1,650 |
| Pro $100（另一组样本） | $100/月 | FinOps LLM：9 月 27 日–10 月 8 日，6 个用满的窗口，模型混用 | 中位数 ≈ $175；窗口范围 $100–234 | 中位数 ≈ $758；对应 $433–1,014 |
| Pro $200（新额度） | $200/月 | InventiveHQ：2 个窗口，包含未用满窗口的外推，Sol 为主 | ≈ $640–670 | ≈ $2,770–2,900 |
| Pro $200（旧额度过渡期） | $200/月 | 与新订阅分开，过渡状态以账号通知为准 | 本次不列统一数值 | 本次不列统一数值 |
| Pro $500 | $500/月 | 本次未取得足够可核对的一手周额度数据 | 暂不填写固定数值 | 暂不填写固定数值 |

*月价值按周价值 × 52 ÷ 12（约 4.33）作平均月折算，取近似数；不等于每个自然月或账单周期实际发放的额度。假设每周充分使用，不含额外赠送、购买或重置。表中各组任务条件不同，不能直接相除得出套餐倍率。*

> ⚠️ 注意：这里的“$”是如果把同等 Token 用量改用 API 支付时的大致成本。由于测试结果受多种因素影响，存在一定波动范围。Pro $100 的两组结果差别较大，不能只取较高的一组当作所有账号的周限额，也不能仅凭 API 等价价值下降断定实际 Token 额度减少。

实测来源与适用范围：

- [InventiveHQ 原始测量](https://inventivehq.com/blog/codex-subscription-usage-measured)：公布逐窗口数据和统计方法，覆盖同一用户三台机器；适合参考 Sol 为主的工作流，但样本少。文中的 Plus、旧 Pro $200 和 Pro $500 数字是推算，本表没有把它们当成实测。
- [FinOps LLM 原始测量](https://finopsllm.com/research/chatgpt-pro-100-real-codex-multiplier)：6 个用满的 Pro $100 窗口；Luna 占 Token 的比例较高，任务与上一组不同，且使用过额外重置。这里比较每个完整窗口，不把重置收益算作正常每周权益。
- [Wokey 原始测量](https://wokey.ai/codex-usage-limits?lang=zh)：Plus 样本有日期、账号数和中间一半账号的范围；来源是商业网关运营方，不能视为独立审计或所有普通账号的代表。
- [SemiAnalysis 控制实验](https://newsletter.semianalysis.com/p/anthropic-subscriptions-offer-5x)（10 月 5 日）：分别测输入、缓存、输出的额度消耗，方法更适合解释模型间差异；其 Astra 工作流下，新 Pro $200 约为 $2,897/月 API 等价价值。报告指出，调整前购买的 $200 档可保留旧额度至 10 月 29 日；这是第三方报告，个人过渡状态仍以账号通知为准。

> 官方说明，API 价格和订阅内用量并不是同一套规则；Work 与 Codex 共享额度。本节只作实测参考，不能据此保证可用消息数、任务数或美元余额。[官方用量说明](https://learn.chatgpt.com/docs/pricing)

## 🧠 可用模型对比

ChatGPT 在 网页端聊天（Chat）、ChatGPT Work 和 Codex 中提供的模型并不完全相同。

| 套餐 | 💬 网页端聊天 Chat† | 🧰 ChatGPT Work | 💻 Codex |
| --- | --- | --- | --- |
| Free | 原文：GPT-5.6 Luna† | 桌面端 GPT-6 Luna，逐步开放；其他入口以账号为准 | 桌面端 GPT-6 Luna，逐步开放 |
| Go | 原文：GPT-5.6 Luna† | 桌面端 GPT-6 Luna，逐步开放；其他入口以账号为准 | 桌面端 GPT-6 Luna，逐步开放 |
| Plus | 原文：GPT-5.6 Sol† | GPT-6 Astra<br>GPT-6.1 Sol<br>GPT-6 Sol<br>GPT-6 Luna | GPT-6 Astra<br>GPT-6.1 Sol<br>GPT-6 Sol<br>GPT-6 Luna |
| Pro $100 | 原文：GPT-6 Pro<br>GPT-5.6 Sol Pro<br>GPT-5.6 Sol† | 同 Plus | 同 Plus |
| Pro $200 | 原文：GPT-6 Pro<br>GPT-5.6 Sol Pro<br>GPT-5.6 Sol† | 同 Plus | 同 Plus |
| Pro $500 | 当前 Chat 模型未核实 | 同 Plus；支持 Ultrafast* | 同 Plus；支持 Ultrafast* |

> GPT-6.1 Sol 正在逐步开放中，具体是否已经出现以账号实际显示为准。GPT-6.1 Sol、GPT-6 Sol、GPT-6 Luna 在 ChatGPT 中用于 Work / Codex，不用于 Chat。GPT-5.6 Sol、Terra、Luna 在过渡期间仍保留。[官方模型说明](https://learn.chatgpt.com/docs/models)
>
> † Chat 一列是 2026-9-9 原文记录，不是本次核实后的当前模型清单。
>
> *Ultrafast 是速度模式，支持 Astra 和 GPT-6.1 Sol；可用推理档位还取决于模型、套餐、客户端及工作区设置。*

---

## 🛠️ 常用功能对比

| 功能 | Free | Go | Plus | Pro $100 | Pro $200 | Pro $500 |
| --- | --- | --- | --- | --- | --- | --- |
| 日常文字聊天 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| GPT-5.6 Luna / Think（Chat，原文记录）† | ✅† | ✅† | —† | —† | —† | 未核实 |
| GPT-6.1 Sol（Work / Codex） | ❌ 首发未包含 | ❌ 首发未包含 | ✅ 逐步开放 | ✅ 逐步开放 | ✅ 逐步开放 | ✅ 逐步开放 |
| Medium / High 推理 | 按模型与账号 | 按模型与账号 | 按模型与账号 | 按模型与账号 | 按模型与账号 | 按模型与账号 |
| Extra High / Max / Ultra 推理 | 按模型与账号 | 按模型与账号 | 按模型与账号 | 按模型与账号 | 按模型与账号 | 按模型与账号 |
| GPT-5.6 Sol Pro（Chat，原文记录）† | ❌† | ❌† | ❌† | ✅† | ✅† | 未核实 |
| GPT-6 Astra（Work / Codex） | 未列入支持套餐 | 未列入支持套餐 | ✅ | ✅ | ✅ | ✅ |
| Ultrafast（Astra / 6.1 Sol） | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| 文件上传与分析（Chat，原文记录）† | 有限† | 扩展† | 更高† | 高† | 最高† | 未核实 |
| 数据分析（Chat，原文记录）† | 有限† | 扩展† | 更高† | 高† | 最高† | 未核实 |
| 图像生成（Chat，原文记录）† | 有限† | 扩展† | 更高† | 高† | 最高† | 未核实 |
| 桌面语音 / GPT-Live | 未列入支持套餐 | 未列入支持套餐 | ✅ 逐步开放 | ✅ 逐步开放 | ✅ 逐步开放 | ✅ 逐步开放 |
| Deep Research（Chat，原文记录）† | 有限† | 扩展† | ✅† | ✅ 更高额度† | ✅ 更高额度† | 未核实 |
| Codex | 基础，桌面端 | 基础，桌面端 | ✅ | ✅ | ✅ | ✅ |
| Projects（原文记录）† | ✅† | ✅† | ✅† | ✅† | ✅† | 未核实 |
| 每个 Project 文件上限 | 以账号显示为准 | 以账号显示为准 | 以账号显示为准 | 以账号显示为准 | 以账号显示为准 | 以账号显示为准 |
| Memory（Chat，原文记录）† | 基础† | 更长† | 增强† | 增强† | 增强† | 未核实 |
| Work / Codex 的 5 小时限额 | 以账号显示为准 | 以账号显示为准 | 有 | 当前无 | 当前无 | 当前无 |

> † 标注项保留原文说法，只作为历史参考；原来的 Project 文件数 5 / 25 / 25 / 40 / 40 未取得当前依据，已改为以账号显示为准。当前 [Projects 说明](https://learn.chatgpt.com/docs/projects)没有列出这些分档数字。
>
> 推理档位不是单纯按 Plus / Pro 一刀切，具体看 [模型说明](https://learn.chatgpt.com/docs/models)。Pro 当前没有 5 小时限额，不代表无限用量。

整体可以简单理解为：

- Plus 的官方估计：每 5 小时约可发送 Astra 5–45 条、GPT-6.1 Sol 15–160 条、GPT-6 Sol 15–150 条或 GPT-6 Luna 350–3,000 条本地消息。这是不同模型的估计，不是可叠加领取的额度，也不是固定消息上限。[官方估计](https://learn.chatgpt.com/docs/pricing)
- Fast 会按 Standard 的约 2.5 倍消耗订阅内额度；Ultrafast 为约 8 倍。使用额外购买的 Credits 时，对应倍率是 2 倍和 6 倍。[速度与计费](https://learn.chatgpt.com/docs/agent-configuration/speed)

---

## 🎨 ChatGPT 图像生成套餐对比

> 以下 Chat 生图表保留原文结构与说法，**标注 † 的内容为 2026-9-9 历史记录，未核实为当前权益**。不要据此承诺当前型号、倍数或无限生图。

| 套餐 | Images 2.5† | 图像生成额度† | 生成速度† | Images with Thinking† | 更适合 |
| --- | --- | --- | --- | --- | --- |
| Free | ✅† | 有限† | 基础† | ❌† | 偶尔生图、简单改图 |
| Go | ✅† | 约 Free 10×† | 更快† | ❌† | 日常较高频生图 |
| Plus | ✅† | 更高额度† | 更快† | ✅† | 高频创作、复杂生图、专业改图 |
| Pro $100 | ✅† | 原文：无限生图*† | 更快† | ✅† | 大量生图、连续改图、专业视觉创作 |
| Pro $200 | ✅† | 原文：无限生图*† | 更快† | ✅† | 极高频生图、大规模视觉内容生产 |
| Pro $500 | 未核实 | 未核实 | 未核实 | 未核实 | 以当前 Chat 生图权益为准 |

> *原文的“无限生图”附有正常使用政策及滥用防护限制；本次未取得当前依据，不作为现行承诺。*

Work / Codex 的内置生图使用 `gpt-image-2`，消耗一般用量；相似任务中，生图平均约以不生图时的 3–5 倍速度消耗订阅内额度，具体受图片质量和尺寸影响。Free 不支持该生图入口。这个规则不能直接套到上表的 Chat 生图。[图像生成说明](https://learn.chatgpt.com/docs/image-generation)、[用量说明](https://learn.chatgpt.com/docs/pricing)

---

## 🎙️ 语音 / Live

ChatGPT 各套餐均有不同程度的语音功能，但额度与可使用模型不同。

整体可以简单理解为：

桌面 GPT-Live：Plus / Pro 支持，具体是否已经出现以账号实际显示为准。

桌面 Live 使用现有 Codex 用量，官方列出的语音费率为 $0.05/分钟；使用额外 Credits 时为 1.25 Credits/分钟，执行任务的模型另按其用量计算。语音和任务共享套餐额度，这不是每月另送的语音余额，也不能套用于普通 Chat 语音。[语音功能](https://learn.chatgpt.com/docs/features/voice)、[语音用量](https://learn.chatgpt.com/docs/pricing)

其中高阶 Pro 档位更适合长时间语音交互或高频使用，仍需留意剩余额度。

---

## 🎯 怎么选？

### 只偶尔用

选 Free

适合简单问答、翻译、轻度写作和体验 ChatGPT。

### 大多数学习 / 科研 / 办公 / 编程用户

优先选 Plus

Plus 是个人套餐中比较均衡的一档：价格远低于 Pro，同时已经可以在 Work / Codex 使用 GPT-6.1 Sol、较强推理等高级能力。具体模型与开放情况以账号显示为准。

### Plus 经常不够用

选 Pro $100

拥有 Pro 核心能力，同时 Work / Codex 当前没有 5 小时限额。但若是重度用户，仍应按实际周用量判断是否需要升级；不能继续沿用“性价比远不如20x”的旧结论。

### AI 是核心生产力工具

选 Pro $200；更高用量或 Ultrafast 需求可看 Pro $500

更适合每天高强度使用 AI、Coding、研究、文件分析、Agent 或复杂工作流的人。Pro $500 的 Ultrafast 会更快消耗额度，并不等于每项功能都比 $200 档多 2.5 倍。[Ultrafast 说明](https://learn.chatgpt.com/docs/agent-configuration/speed)

---

## 📌 最简版结论

```text
Free
↓
免费体验，基础使用

Go
↓
便宜的轻量级套餐

Plus
↓
主流专业版，适合绝大多数个人用户

Pro $100
↓
Pro 能力，Work / Codex 当前无 5 小时限额

Pro $200
↓
Pro 能力，更高用量需求；注意新旧订阅额度区别

Pro $500
↓
Pro 高阶档，支持 Astra / 6.1 Sol Ultrafast
```

---

## 🔗 官方资料

- [OpenAI：套餐价格与使用额度](https://learn.chatgpt.com/docs/pricing)
- [OpenAI：Work / Codex 可用模型](https://learn.chatgpt.com/docs/models)
- [OpenAI：Fast / Ultrafast 速度模式](https://learn.chatgpt.com/docs/agent-configuration/speed)
- [OpenAI：图像生成](https://learn.chatgpt.com/docs/image-generation)
- [OpenAI：语音 / GPT-Live](https://learn.chatgpt.com/docs/features/voice)
- [OpenAI：Projects 与聊天](https://learn.chatgpt.com/docs/projects)

社区数据的来源、日期和条件见上方“套餐额度折算（社区实测）”。

---

## 📄 免责声明

本文为基于 OpenAI 官方公开信息及已注明来源的社区实测整理的非官方中文对比资料，不代表 OpenAI 官方立场。套餐价格、模型、额度、地区可用性及功能可能随时调整，请以 OpenAI 官方页面和你的 ChatGPT 账户实际显示为准。标注 † 的历史记录不代表当前权益，社区实测不代表官方保证。

---

如果这份对比对你有帮助，欢迎 ⭐ Star / 收藏本仓库。

