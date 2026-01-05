# 翻译技术实战课 (Translation Technology Training)

> Tools amplify the talent. 工具放大才华。

本仓库包含两个翻译技术培训项目：

## 📚 项目概览

### 🎓 北京第二外国语大学 (BISU) - 数智化笔译与语料库建设
**授课时间**: 2026年1月第二周  
**授课对象**: 高级翻译学院学员  
**课程时长**: 单次 90 分钟  
**课程文档**: 
- [`BISU_数智化笔译与语料库建设.md`](./BISU_数智化笔译与语料库建设.md) - 完整课程设计
- [`BISU_互动内容库.md`](./BISU_互动内容库.md) - 互动问题和案例库
- [`BISU_时间把控检查表.md`](./BISU_时间把控检查表.md) - 授课时间监控表

**课程特色**:
- ✅ 高互动设计（15-20 分钟互动环节）
- ✅ 严格时间把控（备用内容方案）
- ✅ 实操导向（搜商、AI、语料库实战）

---

### ✈️ 中国民用航空飞行学院 (CAFUC) - 翻译技术培训
**授课对象**: MTI 研究生一年级（民航专业）  
**课程时长**: 2 次课，每次 90 分钟  
**课程网站**: 见下方详细介绍

🎯 **课程定位**：技术意识启蒙 + 理论实践衔接 + 民航特色深度植入

## ✨ 核心特色

### 1. 三角色框架 (Three-Persona Framework)
基于《人工智能时代译员的转变之路》论文，构建了 AI 时代的译员能力模型：
- **🔍 分析师 (Analyst)**：从知识应用到 Prompt 构建
- **🏗️ 建构师 (Architect)**：人机协作下的结构重组
- **🎨 风格师 (Stylist)**：情感化润色与文化把关

### 2. 民航特色深度植入 (Aviation-Specific)
全站案例均取材于真实民航场景，包括：
- **适航管理**：AD 指令、AMOC、CAD
- **飞行运行**：NOTAM、ATC 通话、METAR/TAF
- **机务维修**：AMM 手册排故逻辑
- **服务营销**：机上广播 (PA)、品牌宣传

### 3. 完全离线可用 (Offline Ready)
所有资源（样式、脚本、字体）均已本地化，无需网络连接即可正常使用。

## 📚 课程结构

本课程共 2 次课，每次 90 分钟：

### 第一次课：认知重塑与搜商构建
- **理论框架**：PEMT vs Prompt Engineering 范式转变
- **术语挖掘**：民航术语快查（ICAO/CAAC/Boeing）
- **AI 辅助**：三角色框架在长难句中的应用

### 第二次课：技术赋能与全栈质检
- **文本清洗**：正则 (Regex) 在航空文档处理中的应用
- **智能质检**：Python 自动化术语哨兵
- **语料库建设**：双语数据资产管理

## 🛠️ 技术栈

- **Frontend**: HTML5, Tailwind CSS (本地)
- **Scripting**: Vanilla JavaScript, Python (Snippets)
- **Visualization**: Prism.js (代码高亮), Mermaid (流程图)
- **Offline**: 所有依赖均已本地化，无需 CDN

## 🚀 快速开始

```bash
# 本地服务器
python3 -m http.server 3000
# 访问 http://localhost:3000
```

## 📂 目录结构

```
.
├── index.html              # 首页
├── course.html             # 课程详情
├── framework.html          # 三角色理论框架
├── glossary.html           # ✨ 民航专业术语表 (45+ 术语)
├── lecturer.html           # 讲师介绍
├── tutorial_search.html    # 搜索与术语挖掘 (含民航案例库)
├── tutorial_qa.html        # 智能质检 (含 Python 脚本)
├── tutorial_ai.html        # AI 辅助与长难句
├── tutorial_aviation.html  # 民航文本清洗 (Regex Lab 7 实例)
├── tutorial_nyt.html       # 纽约时报双语库实战
└── assets/
    ├── css/                # 样式文件
    ├── js/                 # 脚本文件 (Tailwind, Prism, Mermaid)
    └── img/                # 图片资源
```

## 📖 术语表

`glossary.html` 提供 **45+ 民航专业术语** 的完整定义，分为 7 个类别：

| 类别 | 术语示例 |
|------|---------|
| 🏛️ 机构与法规 | ICAO, FAA, CAAC, EASA, CCAR, 14 CFR, ICAO Annex |
| 📋 适航与文档 | Airworthiness, AD, AMOC, AMM, SRM, MEL, MMEL |
| ✈️ 飞行运行 | NOTAM, ATC, Flight Level, RVSM, SID, STAR, ILS, VOR |
| 📻 陆空通话 | Cleared for takeoff, Cleared for approach |
| 🌤️ 航空气象 | METAR, TAF, CAVOK, CB, TS |
| 💻 翻译技术 | PEMT, MTQE, TMX, TBX |

每个术语包含：**英文全称 + 中文译名 + 标准定义 + 通俗解释**

## 🔮 下一步完善方向 (Roadmap)

1.  **交互式实训平台**：开发基于 Web 的简易 CAT/Workbench
2.  **多语种支持**：增加民航英语之外的法语/西班牙语案例
3.  **真实语料库集成**：接入公开的 ICAO/EASA/FAA 语料库 API
4.  **学生作品集**：增加学生作业展示和互评模块

## 👨‍🏫 讲师

**何晓鸿 (Aldo)**
- 语言桥公司高级审校专家
- GitHub: [@aldohemsn](https://github.com/aldohemsn)

---
© 2025 Aldo. Designed for CAFUC MTI Training.
