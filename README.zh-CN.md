<p align="right"><a href="README.md">English</a> · <b>简体中文</b></p>

<img src="assets/banner-zh.svg" width="100%" alt="李子圣 · 嵌入式系统架构与工程负责人 · 从技术构想到可运行的硬件" />

<table>
<tr>
<td width="72%" valign="top">

### 把架构设计，落到真实硬件上。

我是**李子圣（Zisheng Li）**，嵌入式系统工程师、智能硬件创业者，现任 **[Anvol](https://anvol.dev) 工程负责人**，也是 **FreakStudio 创始人**。持续围绕智能感知、模块化硬件、开发者工具与产品原型推进研发和交付。

我的工作贯穿需求、电路、实时固件、算法、设备界面与验证，也把这些经验沉淀为可复用的驱动、AI开发工作流与教学系统，让更多人能够在其上继续构建。

**关注方向：**嵌入式系统架构 · AI与硬件 · 开发者生态 · 工程交付

[邮件联系](mailto:1069653183@qq.com) · [FreakStudio知识库](https://freakstudio.cn) · [组织仓库](https://github.com/FreakStudioCN)

</td>
<td width="28%" align="center" valign="middle"><img src="assets/zisheng-li.png" width="235" alt="李子圣商务照片" /><br /><sub>李子圣 · Zisheng Li</sub></td>
</tr>
</table>

| **8** 项授权专利 | **4** 篇学术论文 | **7** 项软件著作权 | **282** 个uPyPI包 |
| :---: | :---: | :---: | :---: |
| 本人列名；5项发明、3项外观 | 感知、物联网与视觉方向 | 本人列名登记 | 社区平台；2026年11月1日快照 |

## 平台与开发者生态

我围绕FreakStudio生态的硬件、软件与工程工作流开展工作，与团队成员及上游开源社区共同推进。

| 平台 | 连接的能力 | 公开入口 |
| --- | --- | --- |
| **Blockless** | 从硬件想法到器件选择、接线、MicroPython固件与引导部署的AI辅助工作流。 | [VS Code扩展与后端](https://github.com/FreakStudioCN/mpy-hardware-extension) |
| **Blockless Make APP** | 在浏览器中生成、预览MicroPythonOS应用，完成MPK打包与设备部署。 | [应用构建平台](https://github.com/FreakStudioCN/micropythonos-ai-app-builder) |
| **GraftSense与uPyPI** | 将模块化硬件、可复用驱动、示例和包发现、分发连接起来。 | [驱动库](https://github.com/FreakStudioCN/GraftSense-Drivers-MicroPython) · [包管理平台](https://upypi.net) |
| **MicroPython Skills** | 把工程知识整理成可复用的项目、驱动、验证和应用开发工作流。 | [技能库](https://github.com/FreakStudioCN/MicroPython_Skills) · [英文版](https://github.com/FreakStudioCN/MicroPython_Skills_EN) |
| **Blockless PCB Studio** | 模块化底板规划、2D/3D审阅、BOM与导出，以及可选KiCad流程；当前为工程原型，制造前需要审阅。 | [规划器](https://github.com/FreakStudioCN/blockless-csp-assembler) · [Studio](https://github.com/FreakStudioCN/blockless-pcb-studio) |

**上游与分发：**MicroPythonOS、LVGL和BIPES由上游社区开发，我们的分支用于集成与实验。uPyStore属于应用分发生态工作的一部分；其域名在2026年11月1日核对时返回HTTP 404，因此暂不作为在线入口推荐。

## 代表性工作

<table>
<tr>
<td width="50%" valign="top"><a href="https://github.com/FreakStudioCN/GraftSense-Drivers-MicroPython"><img src="assets/module-kit.jpeg" width="100%" alt="GraftSense模块化硬件与传感器模块" /></a><br /><b>01 / 把模块组织成系统</b><p>GraftSense与GraftPort把传感器、接口、驱动、例程与课程资料连接起来。我重点推进单个模块与完整应用之间可复用的工程层。</p><a href="https://github.com/FreakStudioCN/GraftSense-Drivers-MicroPython">查看驱动生态 →</a></td>
<td width="50%" valign="top"><a href="https://github.com/FreakStudioCN/MicroPython_Claude_Assistant_Public"><img src="assets/claude-companion.jpeg" width="100%" alt="Claude Code实体桌面助手原型" /></a><br /><b>02 / 让AI工作流进入物理空间</b><p>通过嵌入式固件、BLE、屏幕、灯光与语音，把编程代理的状态转化为设备反馈。我参与设备端与整体集成工作。</p><a href="https://github.com/FreakStudioCN/MicroPython_Claude_Assistant_Public">查看公开助手项目 →</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://github.com/leezisheng/pig_healthy_pytorch"><img src="assets/edge-vision.png" width="100%" alt="动物追踪、运动统计与异常分析研究原型" /></a><br /><b>03 / 从视频中获得有用的感知信息</b><p>动物健康与行为分析研究原型，连接YOLO、DeepSORT、运动特征、异常分析与上位机可视化。我的工作包括模型链路、界面与边缘端集成。</p><a href="https://github.com/leezisheng/pig_healthy_pytorch">健康监测代码 →</a> · <a href="https://github.com/leezisheng/Animal_behavior_analysis">行为分析 →</a></td>
<td width="50%" valign="top"><a href="https://github.com/leezisheng/SEMG_Assistant"><img src="assets/emg-robot-arm.png" width="100%" alt="表面肌电采集与机械臂实验" /></a><br /><b>04 / 从人体信号到机械运动</b><p>肌电采集、滤波、神经网络回归、MCU控制与上位机可视化构成完整研究原型。我把Keras模型与STM32固件、系统测试连接起来。</p><a href="https://github.com/leezisheng/SEMG_Assistant">信号分析软件 →</a> · <a href="https://github.com/leezisheng/MCU_Project">MCU实验 →</a></td>
</tr>
</table>

**更多团队产品：**[盆栽宝宝](https://github.com/FreakStudioCN/PottedBaby) · [PixelSky](https://github.com/FreakStudioCN/PixelSky) · [语音陪伴终端](https://github.com/FreakStudioCN/danke_ai) · [BOM工具](https://github.com/FreakStudioCN/BOM-SelfPurch_Parts_List_Proc-Toolkit)

## 我怎样组织一个系统

<img src="assets/architecture-zh.svg" width="100%" alt="工程路径：需求与验收、硬件与感知、固件与控制、应用与AI、验证与交接；驱动、包管理、工作流和文档支撑复用。" />

| 层次 | 实践内容 |
| --- | --- |
| **硬件与感知** | 传感器接口、PCB调试、模拟采集、电机驱动、电源与通信。 |
| **嵌入式与控制** | STM32、ESP32、RP2040/RP2350、MicroPython、FreeRTOS、HAL适配、PID与外设协议。 |
| **AI与应用** | OpenCV、Keras、检测追踪、信号处理、PyQt、LVGL及设备与上位机集成。 |
| **工程与团队** | 需求拆解、可验证的里程碑、样机集成、文档、技术教学与跨专业协作。 |

## 私有项目中的工程工作

部分当前工作保存在私有仓库中。以下从能力与职责层面介绍相关实践。

| 工作方向 | 我的工作与工程背景 |
| --- | --- |
| AI乐器硬件 | 嵌入式音频样机迭代、设备控制与显示、上位机辅助测试，以及从实验走向工程样机的联调工作。 |
| 实体AI助手 | 设备固件、BLE/Wi-Fi通信、界面与语音反馈、配置和集成；上文提供可公开的助手版本。 |
| 客户到工程的工作流 | 需求澄清、双语工程需求书、范围与验收场景、合同/SOW准备及可审阅的交接文档。 |
| 商业运营工具 | 基于证据的硬件研究、客户沟通流程、技术内容整理与销售支持资料；相关贡献属于更大的团队系统。 |
| 开发效率工具 | IDE包管理集成、MicroPython中间件测试实验，以及文档采集与整理工具。 |
| Web与平台集成 | 围绕硬件工作流，参与团队浏览器产品与后端服务的集成工作。 |

## 近期工程重点

| 时间 | 工作 |
| --- | --- |
| **2026年10月** | 驱动审阅与实验性异步版本集成，明确验证标签，补充安装与运行检查。[公开提交](https://github.com/FreakStudioCN/GraftSense-Drivers-MicroPython/commit/a34bed7a4426a64841e5a7019bc9c8919938837b) |
| **2026年8—10月** | 完善MicroPython项目与应用工作流、发布准备和可复用工程技能。[技能库本人提交](https://github.com/FreakStudioCN/MicroPython_Skills/commits/main/?author=leezisheng) |
| **2026年9—10月** | 私有硬件样机迭代，以及连接客户需求、工程评估与交付文档的工具链。 |

[**查看全部66个公开仓库与提交快照 →**](docs/REPOSITORIES.zh-CN.md) · [English catalog](docs/REPOSITORIES.md)

目录覆盖个人账户与FreakStudioCN，包含派生分支与参考仓库。提交数按各仓库默认分支历史统计，包含合并提交，不相加作为个人贡献总分。

## 代码之外的现场

<table>
<tr>
<td width="50%"><img src="assets/hicool-demo.jpeg" width="100%" alt="FreakStudio团队在HICOOL 2026展示产品" /><br /><b>从原型走向产品演示</b><br /><sub>团队产品展示 · HICOOL 2026</sub></td>
<td width="50%"><img src="assets/teacher-workshop.jpeg" width="100%" alt="教师使用硬件套件开展培训" /><br /><b>从工程经验走向教学系统</b><br /><sub>团队师资培训 · 80余名教师、30余所学校 · 2026年1月</sub></td>
</tr>
</table>

**我的路径：**深圳红茶移动嵌入式软件实践 → 青禾之道 / FreakStudio创始人 → 智能感知研究、产品工程与开发者生态。2024年至今在中北大学攻读电子信息工程硕士研究生。

## 一起把技术做成能运行的产品。

欢迎就嵌入式架构、智能硬件、传感系统、机器人原型和开发者工具交流合作。

**[1069653183@qq.com](mailto:1069653183@qq.com)** · [Anvol工程服务](https://anvol.dev) · [FreakStudio知识库](https://freakstudio.cn) · [GitHub组织](https://github.com/FreakStudioCN)

<sub>更新于2026年11月1日。个人工作、团队协作与上游项目按实际背景表述；配图展示真实硬件、研究原型及团队活动。</sub>
