<div align="center">

# 🎬 medical-report

## 体检单拍一张，异常指标逐项讲明白
## Snap one lab report, get every abnormal marker explained

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

用于解读体检报告、检验报告、检查单、化验单，以及影像、超声、CT、MRI、内镜和病理报告。用户上传图片、照片、截图、PDF、文档或表格即可，甚至只发附件没有文字说明也会触发。输出包含异常总览、分组表、逐项详细解读和单次指标可视化；若同一指标有两个及以上可靠时间点，则生成趋势折线图、异常分布条形图、风险分层图和复查计划时间轴等飞书图表卡片。健康问题会先分成建议限期就医、建议复查随访、建议长期管理三类，识别到紧急风险时单独给出醒目的「情况紧急」提示。流程设有多道数值确认硬门槛，看不清或对不上的数值绝不猜测；定位始终是健康信息整理与管理建议，不给诊断、不开口服药剂量或治疗方案。

### ✨ 能做什么

- 上传报告图片/PDF/表格 → 梳理报告内容，输出异常总览 + 分组表 + 逐项详细解读 + 单次指标可视化
- 两个及以上时间点 → 自动生成趋势、异常分布、风险分层与复查时间轴图表
- 把健康问题分成限期就医/复查随访/长期管理三类 → 一句话说清再列医学证据
- 识别到急症风险 → 单独生成视觉更强的「情况紧急」提示
- 数值不清或对不上 → 暂停生成，列出待确认项请用户补充原件
- 顺带给出就医沟通、复查随访、观察监测与生活方式管理建议

### 📦 包含的技能

- `medical-report` —— 见 [`medical-report/SKILL.md`](medical-report/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/medical-report.git
cp -r medical-report/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Interprets health-checkup, lab, imaging, ultrasound, CT, MRI, endoscopy and pathology reports. Users can upload a photo, screenshot, PDF, document or spreadsheet — even a bare attachment with no text will trigger it. Output includes an abnormal-findings overview, grouped tables, item-by-item explanations and single-point visualizations; when an indicator has two or more reliable time points, it builds Feishu chart cards for trend lines, abnormal distribution, risk stratification and a follow-up timeline. Findings are sorted into urgent consultation, recheck and follow-up, and long-term management, with a distinct urgent alert when risk signals appear. Hard numeric gates stop it from guessing unreadable values, and it stays scoped to health information organization: no diagnosis, no drug dosages, no treatment plans.

### ✨ What it does

- Upload a report photo, PDF or spreadsheet → content organized into an abnormal overview, grouped tables, per-item explanations and single-point charts
- Two or more time points → trend, distribution, risk-stratification and follow-up timeline charts
- Sorts issues into urgent care, recheck, and long-term management → plain-language summary first, medical evidence after
- Acute risk detected → a visually stronger urgent alert is raised on its own
- Unreadable or mismatched numbers → generation pauses and the user is asked for a clearer original
- Adds advice for doctor conversations, follow-up, monitoring and lifestyle management

### 📦 Skills included

- `medical-report` — [`medical-report/SKILL.md`](medical-report/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/medical-report.git
cp -r medical-report/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
