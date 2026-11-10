<div align="center">

# 你好，我是 lplalbert 👋

**李沛霖**｜华中科技大学 计算机与人工智能学院 计算机科学与技术 博士一年级

**数字水印/隐写 · Agent 系统 · 量化数据工程**

[![Blog](https://img.shields.io/badge/Blog-lplalbert.github.io-blue)](https://lplalbert.github.io)

</div>

---

## 🧭 关注方向

- **数字水印与隐写**：频域/空间域嵌入、鲁棒性攻击评测、水印定位与提取
- **Agent 系统工程**：多 Agent 协作编排、GUI Agent、安全闸门与全链路审计
- **数据工程质量体系**：大规模数据入库、覆盖率/完整性审计、事件级验证与可复现评测

## 🔭 重点项目

<table>
<tr><td><b>🤖 life-agent</b> — Android GUI Agent + 恢复证据研究</td></tr>
<tr><td>截图 + 控件树感知 → LLM 决策 → 安全闸门 → 执行的真机 Agent 循环；消费类操作强制确认、每步留痕可回溯。研究侧：Provenance Gate（动作时刻证据出处闸门）、受控 A/B、配对符号检验 + 聚类 bootstrap 统计工具、故障归因四分类。Python / ADB / Android</td></tr>
<tr><td><b>💧 dx_overlay_code / fftmask / inrsteg</b> — 水印与隐写研究系列</td></tr>
<tr><td>RS(15,5) 编码 ID 水印叠加与截图检测（C++/Python）；FFT 频域 60bit 水印嵌入/解码（YCrCb）；高分辨率鲁棒水印框架，抵抗极端裁剪与缩放</td></tr>
<tr><td><b>✍️ MizigeFontGen / font_score</b> — 字体生成与评分</td></tr>
<tr><td>米字格手写风格字体生成（2/3 类变体，MIT）；字帖图片预处理 → OCR → 字符评分完整流水线</td></tr>
<tr><td><b>🀄 maj / maj_server</b> — 麻将拍照识别与点数结算</td></tr>
<tr><td>多区拍照识别、番符自动分析、日麻点数查表；Flutter 前端 + Python 识别后端</td></tr>
</table>

## 🤝 开源贡献（进行中）

<table>
<tr><td><b>🔗 apache/hugegraph-ai</b> — HugeGraph 与 AI/LLM & GraphRAG 的集成</td></tr>
<tr><td>8 个 PR（#412–#419）：向量检索阈值契约、流式生成契约、Graph 装载数据保真、prompt 配置运行时解析与 .env 往返、InfoExtract 长度配置化、Web UI 配置刷新</td></tr>
<tr><td><b>⚙️ inclusionAI/AReno</b> — 单机 RL post-training 训练工具箱</td></tr>
<tr><td>2 个 PR（#666/#667）：off-policy 校正的异步 GRPO/GSPO 损失、有界样本队列的异步策略训练器</td></tr>
</table>

## 🛠 技术栈

`Python` `C/C++` `TypeScript` `Dart/Flutter` `Node.js` `SQLite` `PyTorch` `FastAPI` `Django` `Android/ADB`

## 📦 其他

- **ai-video-pipeline** — AI 视频生产流水线（选题→文案→配音→素材→成片→投稿），含评测基建：故障注入、盲评一致性、四臂对照闭环、种子冻结
- **regular-script** — 柳公权楷书 64×64 汉字数据集与笔画标准
- **tools_label** — YOLO 标注工具集（类别重映射、分布统计、YAML 生成）
- **Zotero_plugin** — Zotero 7 插件开发
- **auto_sign** — 校园健康打卡自动化 + 截图推送
- **my_blog** — Django + MySQL 博客系统
- **代码复现工作** — 借助 multi-coding-agent（他人开发的多 Agent Coding 系统）完成多个代码复现项目

---

<div align="center">

*结论必须带证据引用，失败必须可定位、可复现。*

</div>
