# 北二外课件替换进度

## 已完成 ✅

### 1. 核心页面
- `index_bisu.html` - 北二外专用首页
- `course_bisu.html` - 课程详情页

### 2. 搜索教程
- `tutorial_search_bisu.html` - 术语搜索教程（已完成）
  - ✅ 替换民航案例为通用案例
  - ✅ Flight Level → carbon neutrality
  - ✅ ICAO/FAA/CAAC → UN/WHO/政府网站
  - ✅ 民航术语 → 气候变化、数字经济、国际法律、公共卫生、学术术语

---

## 待创建 🚧

### 3. AI 辅助教程
- `tutorial_ai_bisu.html`
  - **替换内容**:
    - 航空安全法规长难句 → 学术论文/国际公约长难句
    - COMAC/Boeing手册 → 学术写作/商务文书
    - 航空法律专家 → 商务翻译专家/学术翻译专家
    - 民航管理局 → 国际组织/政府部门

### 4. 文本清洗教程  
- `tutorial_regex_bisu.html`（原 tutorial_aviation.html）
  - **替换内容**:
    - 航空维修手册清洗 → 新闻稿/学术论文清洗
    - NOTAM格式 → 新闻日期格式
    - 机型编号 → ISBN/DOI提取
    - 航空代码 → 通用标识符

### 5. 质检教程
- `tutorial_qa_bisu.html`
  - **替换内容**:
    - 航空术语库 → 通用术语库
    - Flight crew/ICAO Annex → 可持续发展/联合国文件
    - Python脚本案例更新

### 6. 共享页面（无需修改）
- `tutorial_nyt.html` - 纽约时报案例（已经是通用案例）
- `framework.html` - 三角色框架（理论通用）
- `lecturer.html` - 讲师介绍（讲师信息通用）

---

## 案例替换对照表

| CAFUC 案例 | BISU 案例 |
|-----------|----------|
| **民航术语** |  |
| Flight Level, NOTAM, ATC | carbon neutrality, SDGs, ESG |
| ICAO, FAA, CAAC | UN, WHO, 世界银行 |
| 适航管理、飞行运行 | 可持续发展、公共卫生 |
| **长难句来源** |  |
| 航空安全法规 | 国际公约、学术论文 |
| COMAC/Boeing 手册 | 企业CSR报告、政府白皮书 |
| **文本类型** |  |
| 航空维修手册 | 新闻稿、学术期刊 |
| METAR/TAF 报文 | 数据报告、统计公报 |
| **验证来源** |  |
| 民航局网站 | 政府官网、国际组织 |
| ICAO Annex | UN文件、WHO指南 |

---

## 下一步计划

1. **创建 tutorial_ai_bisu.html**（AI 辅助翻译）
2. **创建 tutorial_regex_bisu.html**（文本清洗）
3. **创建 tutorial_qa_bisu.html**（质检）
4. **更新 index_bisu.html 和 course_bisu.html** 的所有链接
5. **提交所有更改到 Git**

---

## 注意事项

- ✅ 保持CAFUC原始课件不变
- ✅ 所有BISU文件使用 `_bisu` 后缀
- ✅ 移除对 `glossary.html`（民航术语表）的所有引用
- ✅ 更新footer为BISU项目信息
- ✅ 导航链接指向BISU版本页面

---

**创建时间**: 2026-01-05  
**状态**: 进行中
