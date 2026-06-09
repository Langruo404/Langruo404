# Hi, I'm Langruo 👋

大连理工大学工科硕士在读，具备道路桥梁与桥隧工程背景，本科阶段有信息管理与信息系统双学位背景。
目前关注工程 AI、RAG / 知识库、本地模型应用、智能检测、边缘终端与系统需求分析方向。

I am interested in Engineering AI, RAG / knowledge base systems, local LLM applications, intelligent inspection, edge devices, and requirement analysis.

## About Me

我关注复杂工程场景中的需求拆解、模块边界、数据流、上下文组织与技术文档表达。
相比单纯的算法或纯开发方向，我更关注如何把工程问题、用户需求、系统约束和技术实现整理成可理解、可协作、可维护的系统方案。

My current focus is on system boundaries, maintainable architecture, context engineering, and turning complex technical ideas into clear documents.

## Current Focus

* 工程 AI 与系统需求分析 / Engineering AI & Requirement Analysis
* 视觉检测与病害量化 / Computer Vision & Defect Quantification
* RAG、知识库与结构化记忆 / RAG, Knowledge Base & Structured Memory
* 本地模型应用与上下文工程 / Local LLM Applications & Context Engineering
* 智能硬件与边缘终端 / Intelligent Hardware & Edge Devices
* 工业软件、车载系统与 B 端解决方案 / Industrial Software, Automotive Systems & B2B Solutions

## Featured Projects

### [桥梁病害检测与量化案例研究](https://github.com/Langruo404/bridge-defect-detection-quantification-case-study)

**Bridge Defect Detection & Quantification Case Study**

围绕桥梁表观病害检测与量化项目，整理 YOLO segmentation、双目深度估计、病害尺寸计算与 Web 系统展示之间的技术链路。该仓库为 non-code case study，不包含原始源码、数据集、模型权重或内部项目资产。

项目关注点包括：

* 桥梁裂缝、混凝土剥落、钢筋外露等病害对象的工程语义理解
* YOLO segmentation 输出中的类别、置信度、mask 与结果图
* 双目视差、深度换算与病害尺寸量化思路
* mask 轮廓、深度信息与几何计算在裂缝长度/宽度、病害面积估算中的作用
* 前端展示、业务服务、算法服务和数据库记录之间的数据流
* 模型评估、量化误差、接口字段与工程规范转换的能力边界

Keywords: Computer Vision, Bridge Inspection, YOLO Segmentation, Stereo Vision, Defect Quantification, Engineering AI.

### [AI 知识工作台与长期记忆系统](https://github.com/Langruo404/ai-workspace-knowledge-base-system)

**AI Workspace & Knowledge Base System**

本地 AI 知识工作台与长期记忆系统 case study，关注 FTS5、Embedding、RRF 混合召回、分层长期记忆与证据回溯。项目重点是探索如何在对话、长期事实、专业资料和原文证据之间建立可检索、可追溯、可维护的上下文层。

项目关注点包括：

* SQLite FTS5 与 Embedding / sqlite-vec 的混合检索
* Reciprocal Rank Fusion 在关键词召回与语义召回之间的排序融合
* M1 / M2 / M3 分层长期记忆与上下文装配
* source_msg_ids 证据回溯与摘要可信度控制
* Provider / Adapter 与工具运行时原型的系统边界
* 检索命中、上下文预算、记忆污染与证据回溯之间的平衡

Keywords: RAG, Knowledge Base, FTS5, Embedding, RRF, Long-term Memory, Evidence Traceability.

### [本地 LLM Telegram 对话记忆系统](https://github.com/Langruo404/local-llm-telegram-memory-system)

**Local LLM Telegram Bot Memory System**

基于 TypeScript、Telegram Bot、SQLite 与本地 LLM API 的对话记忆系统原型。项目重点不是完整 RAG，而是探索小模型长对话场景下的 context 管理、摘要、轻量检索与 prompt assembly。

项目关注点包括：

* Telegram 私聊链路与本地 LLM OpenAI-compatible API 接入
* SQLite 消息、上下文与摘要存储
* context / segment summary / running summary 的边界划分
* prompt assembly 与上下文预算控制
* 轻量关键词检索与后续结构化记忆扩展方向
* 小模型工具调用步数、记忆污染与长期连续性边界

Keywords: TypeScript, Telegram Bot, Local LLM, SQLite, Summary, Prompt Assembly, Memory System.

### [ESP32-P4 触控边缘显示终端](https://github.com/Langruo404/esp32-p4-edge-display-terminal)

**ESP32-P4 Edge Display Terminal**

基于 ESP32-P4、ESP-IDF 与 LVGL 的 7 英寸触控显示终端 bring-up case study。项目记录从板级资料阅读、显示与触摸链路验证，到中文 UI、TF 存储和 Ethernet 网络连通性测试的工程过程。

项目关注点包括：

* ESP32-P4 与 ESP-IDF 项目环境
* 1024×600 MIPI-DSI 显示、JD9165 面板与 GT911 触摸验证
* LVGL 中文状态页、触摸交互、动画、息屏与唤醒
* 中文字体子集与 RGB565 图片资源流程
* SDMMC / TF 卡读写验证与 Ethernet DHCP bring-up
* 后续向本地服务或 Agent 控制显示内容扩展的边缘终端方向

Keywords: ESP32-P4, ESP-IDF, LVGL, MIPI-DSI, GT911, Embedded UI, Edge Device.

## Direction

希望向系统需求分析、工程 AI、工业 AI、智能检测、RAG / 知识库、智能硬件、车载系统、B 端产品 / 解决方案等方向持续发展。
我希望在真实工程场景中，参与复杂需求拆解、系统方案整理、技术文档编写，以及 AI / 硬件 / 软件协同系统的产品化过程。
