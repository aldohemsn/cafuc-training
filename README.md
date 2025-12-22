# 翻译技术实战课 (CAFUC Translation Technology Training)

> Tools amplify the talent. 工具放大才华。

这是一个专为**中国民用航空飞行学院 (CAFUC)** MTI 研究生定制的翻译技术培训课程网站。

🎯 **课程定位**：技术意识启蒙 + 理论实践衔接

## ✨ 核心特色

### 1. 三角色框架 (Three-Persona Framework)
基于《人工智能时代译员的转变之路》论文，构建了 AI 时代的译员能力模型：
- **🔍 分析师 (Analyst)**：从知识应用到 Prompt 构建
- **🏗️ 建构师 (Architect)**：人机协作下的结构重组
- **🎨 风格师 (Stylist)**：情感化润色与文化把关

### 2. 民航特色深度植入 (Aviation-Specific)
全站案例均取材于真实民航场景，包括：
- **适航管理**：AD指令、AMOC、CAD
- **飞行运行**：NOTAM、ATC 通话、METAR/TAF
- **机务维修**：AMM 手册排故逻辑
- **服务营销**：机上广播 (PA)、品牌宣传

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

- **Frontend**: HTML5, Tailwind CSS
- **Scripting**: Vanilla JavaScript, Python (Snippets)
- **Visualization**: Prism.js (代码高亮), Mermaid (流程图)

## 🚀 快速开始

```bash
# 本地服务器
python3 -m http.server 8001
# 访问 http://localhost:8001
```

## 📂 目录结构

```
.
├── framework.html          # [NEW] 三角色理论框架
├── tutorial_search.html    # 搜索与术语挖掘 (含民航案例库)
├── tutorial_qa.html        # 智能质检 (含 Python 脚本)
├── tutorial_ai.html        # AI 辅助与长难句
├── tutorial_aviation.html  # 民航文本清洗 (Regex)
├── index.html              # 首页
└── ...
```

## 🔮 下一步完善方向 (Roadmap)

1.  **交互式实训平台**：开发基于 Web 的简易 CAT/Workbench，让学生能在网页上直接练习修改 Prompt 和译文。
2.  **多语种支持**：增加民航英语之外的法语/西班牙语案例（针对 CAFUC 泛语种需求）。
3.  **真实语料库集成**：接入公开的 ICAO/EASA/FAA 语料库 API，实现实时术语查询功能。
4.  **学生作品集**：增加学生作业展示和互评模块。

## 👨‍🏫 讲师

**何晓鸿 (Aldo)**
- 语言桥公司高级审校专家
- GitHub: [@aldohemsn](https://github.com/aldohemsn)

---
© 2025 Aldo. Designed for CAFUC MTI Training.
