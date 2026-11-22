# 智能硬件创意日报 · 小众真实需求补报

- 日期：2026-11-22（星期日）
- 时区：UTC+8
- 数据截至：约 15:40（UTC+8）
- 说明：本轮按第二期标准补遗，刻意避开今早主名单中的 Flipper One、Keychron Orca echo、ARANIX、CyboPal ONE、InfiMech MX。重点看金额不一定高、但需求证据更扎实的项目。Crowd Supply 原站今日 GET 仍被 403，部分金额只能引用检索快照，并标明时点，不把它写成当场实时数。

## 1. LocalDot

- 品类：智能硬件 / 本地语音助手改造板
- 来源：Crowd Supply；需求首先出现在 Home Assistant 社区
- 链接：[Crowd Supply 项目页](https://www.crowdsupply.com/aaelectronics/localdot) · [GitHub](https://github.com/ale1800/LocalDot) · [Home Assistant 论坛原帖](https://community.home-assistant.io/t/drop-in-replacement-for-echo-dot-3rd-with-voice-assistant/1020256)

给第 3 代 Echo Dot 换一块开源主板，外壳、四麦、喇叭、按键和灯环都留着，改成接 Home Assistant 的本地语音卫星。

解决谁的问题：已经买过 Echo Dot、又想摆脱 Alexa 云端的 Home Assistant 用户。社区里有人家里放了 4、6、甚至 8 台 3 代 Dot，不想把还能用的麦克风和喇叭扔掉。

需求证据：

- Home Assistant 论坛帖由作者于 2026-08-07 发布；截至 2026-11-22 查询，120 帖、13,748 次浏览、183 个赞、37 名参与者，最后一帖在 2026-11-21 16:46（UTC+8）。
- 多名用户直接表达购买意向，包括家里有 4 台或 8 台、已经想了两年怎么替换的人；2026-11-21 还有人专门注册论坛，称不想再用官方 Alexa 服务，更看好换板方案。
- GitHub 仓库 `ale1800/LocalDot` 当日核实：234 star、8 fork、44 watcher，最近更新 2026-11-21。
- 同类需求此前已有 Onju Voice（Nest Mini 2）、MiciMike（Home Mini 1）等换板项目。

可行性 / 价格：据 CNX Software（2026-11-11），单板 $50，两件装 $98，三件装 $145；美国运费 $8，国际 $18；活动截止 2026-12-17；预计 2027-04-17 起发货。需自备 3 代 Echo Dot 和原装 12V 电源。完整固件和设计文件仍在补。

热度信号：检索快照（非当场实时）约 $43,593–$44,768 / 目标 $7,500，约 238–250 人支持。另有一条 YouTube 演示当日核到 1,242 次播放，热度不大。

主要风险：固件未完成，2027 年 4 月只是预期交期；Clock 版未验证；完全本地语音管线仍待成熟。

## 2. Firehat

- 品类：桌面 / 创客采集工具（树莓派 FireWire HAT）
- 来源：Crowd Supply；需求来自 MiniDV / FireWire 存档社区
- 链接：[Crowd Supply 项目页](https://www.crowdsupply.com/computer-equipment-group/firehat) · [GitHub](https://github.com/computerequipmentgroup/firehat) · [Jeff Geerling 实测](https://jeffgeerling.com/blog/2026/minidv-with-raspberry-pi-firewire-hat)

给树莓派 5 / Radxa ROCK 2F 等带 PCIe 的单板电脑加原生 IEEE 1394，直接从老 DV/HDV 摄像机或卡座抓数字码流，不必再经一层模拟转换。

解决谁的问题：手里还有 MiniDV、Digital8、DVCAM、HDV 磁带或 FireWire 摄像机，却发现新电脑、尤其是 macOS Tahoe 不再支持 FireWire 的人。二手专业采集盒（如 Sony HVR-MRC1）在 eBay 大约 $300，社区一直有人用「Open MRU」自行拼采集盒。

需求证据：

- Jeff Geerling 在 2026-03 连续写了两篇实测，并出了视频《Apple Abandoned It. I Saved It with a Raspberry Pi.》。2026-11-22 打开该视频页，播放量为 326,265。文中写明 Apple 在 macOS Tahoe 里放弃 FireWire 后，部分用户被卡住；他用 Firehat 原型 + Pi 5 的整套新购大约 $150–200。
- 更早的 DIY 绕路来自 r/tapeless：有人用 Mini PCIe 转接加火线卡做成 Open MRU。
- 仓库当日 API：93 star、5 fork，更新于 2026-11-20。

可行性 / 价格：LinuxGizmos（2026-08-26）写众筹档为 $79。较新的 Crowd Supply 检索快照写已筹 $26,663 / 目标 $7,500 / 355%，状态为可预购，标价 $99。两处价格不一致，应以原页为准，今日未能打开正文。

热度信号：相对百万级众筹很小；独立测评播放 32.6 万，是本轮里较硬的「痛点被看见」信号。

主要风险：FireWire 在 Linux 内核里的长期支持并不确定；卡座控制因机型而异；这是极窄的垂直市场，交期和现价需再核。

## 3. Sprout Pi 主板

- 品类：桌面工具 / 复古播放器改造板
- 来源：Crowd Supply 预热页；需求先被官方演示视频放大
- 链接：[Crowd Supply 预热页](https://www.crowdsupply.com/certain-things/sprout-pi-mainboard) · [演示视频](https://www.youtube.com/watch?v=xwB0ohq2xYk)

英国工作室 certain things 做的 RP2350 替换主板，装进经典 iPod 外壳，加 USB-C、蓝牙、microSD，高配还可流媒体。

解决谁的问题：还在用或重新捡起 3/4 代 iPod、1/2 代 iPod mini 的人。原机 30 针接口和电池已经过时，但外壳、转盘和 3.5 mm 口仍有人喜欢。

需求证据：

- 官方短片《A modern motherboard for iPods》（2026-10-06 发布）在 2026-11-22 打开视频页，播放量为 1,121,234。这是「还没开卖、先被看到」的强信号；评论正文今日未能稳定抓取，不编造评论内容。
- heise（2026-10-16）和 Notebookcheck（2026-10-14）都跟了报道。
- 项目页当日仍是 Coming Soon，众筹尚未开始，因此还没有支持者或金额。

可行性 / 价格：价格尚未公布。计划兼容 iPod 3/4 和 iPod mini 1/2，分本地音乐版和可流媒体的高配。宣称免焊接、可还原；硬件和固件计划开源。

热度信号：无筹款数。视频破百万播放，但不能等价于付费订单。

主要风险：尚未开卖，价格、交期、流媒体授权和系统完成度都未验证；这是该工作室的第一个硬件项目，众筹失败或跳票都有可能。

## 4. KeyBridge 2.0

- 品类：智能家居桌面控制器（USB 键盘桥）
- 来源：独立小店 Local Devices，不是头部众筹
- 链接：[产品页](https://localdevices.net/products/keybridge-2-0) · [固件仓库](https://github.com/abdalrahimnaser/keybridge-esphome)

一块带 USB Host 的 ESP32-S2 小板，把旧 USB 键盘、数字键盘或 2.4 GHz 宏垫变成 Home Assistant 的实体按键墙，不经过电脑，也不走云。

解决谁的问题：觉得智能按钮贵、数量少，又希望床头、书桌或媒体柜上有真实按键的 Home Assistant 用户。用闲置键盘就能映射灯、窗帘、场景和媒体键。

需求证据：

- 产品页 2026-11-22 打开时写明：Batch #1 限 150 台，状态为已售罄，预计 2026 年 12 月 / 2027 年 1 月发货；Batch #2 限 500 台，状态为在售，预计 2027 年 3 月发货。第一批售罄是可核验的小规模真实预购。
- 2025 年已有第一版并开源；2.0 按用户反馈缩小板型，并改成原生 ESPHome。How-To Geek 2026-10-20 报道后，评论区有人提到床头实体键盘的吸引力。
- GitHub 当日：现行仓库 51 star；已归档旧仓库 30 star、3 fork。星标不多，但和 150 台首批售罄是匹配的小众规模。

可行性 / 价格：现价 $34.99。约 45×39 mm 裸板，USB-C 供电，预刷固件，通过 ESPHome Native API 被 Home Assistant 发现。开源硬件和软件。

热度信号：刻意做小。150 台首批售罄，第二批 500 台仍在预售，没有百万级曝光。

主要风险：第二批发货要到 2027 年 3 月；兼容性取决于 USB 键盘或接收器；作坊式小批量，后续是否持续供货未知。

## 5. OpenDrone

- 品类：无人机 / 开源 FPV 飞控、电调、接收机与机架
- 来源：比利时 OpenDrone 自营站，不是 Kickstarter 爆款榜
- 链接：[产品列表](https://opendrone.be/products) · [飞控页](https://opendrone.be/products/openfc-lite) · [预购说明](https://opendrone.be/preorder) · [GitHub 组织](https://github.com/OpenDrone-hw)

把 FPV 飞控、电调、ExpressLRS 接收机等做成可公开原理图和 PCB 的量产件，补上「飞控软件开源、板子却几乎全闭源」的缺口。

解决谁的问题：用 Betaflight、ExpressLRS、AM32 的 FPV 玩家和维修者。软件栈是开源的，但商业飞控和电调通常不给原理图，坏了难修，也难审计。

需求证据：

- 官方启动文（2026-10-02）把痛点写得很直接：FPV 飞的是开源软件，跑在几乎全闭源的硬件上。
- GitHub 组织当日：29 个公开仓库，848 名关注者。星标较高的有 OpenRX（498 star / 78 fork）、OpenESC-20x20（283 / 85）、OpenFC-Lite-Mini（149 / 40）等。这是开源跟做意义上的需求，不是众筹榜金额。
- 预购页在 2026-11-22 打开时称：Batch 1 已完成测试，已向欧盟客户发货，余货在库；2027 年 3 月批次无论订单多少都会做；早鸟价到 2026-12-15。

可行性 / 价格：当日产品页为早鸟预购，发货截止 2027-03-31，欧元价约为：OpenFC Lite 20x20 €21.50；OpenESC 20x20 €36.50；OpenRX Lite €13.90 起。飞控为 RP2354 + Betaflight，电调跑 AM32，设计宣称开源并有 OSHWA 认证。路线图显示多数产品仍在 Alpha/Beta。注意：`/products/openfc-lite-mini`、`/products/openesc-20x20`、`/shop` 今日为 404，不要用这三条。

热度信号：没有单一众筹总额。仓星标和组织关注者是主要热度；Batch 1 已对欧盟发货，但未公布累计销量。

主要风险：多数 SKU 仍是预购；Alpha/Beta 设计可能在批次间改版；新飞控目标存在固件成熟度风险。

## 采集说明

本轮需求证据最硬的是 LocalDot（论坛跟帖 + 换板传统）和 Firehat（系统砍功能 + DIY 绕路 + 独立测评）。KeyBridge 是「首批 150 台售罄」的典型小众预购。Sprout 热度在视频，订单还没开始。OpenDrone 补上了今早缺席的无人机 / FPV 开源硬件，但要分清 Batch 1 已发货和 2027 年 3 月预购的差别。

国内众筹和社区仍然是最大缺口：摩点当日几乎没有符合品类的硬件；有品多为常规消费电子迭代；京东众筹、恩山、知乎、RCGroups，以及 Reddit 多个垂直版块，本轮没能稳定打开可引用的热帖。下次会再补这些渠道，不能只靠 Crowd Supply。
