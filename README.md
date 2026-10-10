# 陶弘景 Skill（tao-hongjing）

**v1.0.0** · 南朝本草学开山、《本草经集注》作者、道教茅山宗宗师陶弘景（456-536，"山中宰相"）的人物 skill。

[![版本](https://img.shields.io/badge/版本-v1.0.0-blue)](CHANGELOG.md)
[![原文库](https://img.shields.io/badge/原文库-2部14万字-orange)](modules/)
[![文献双轨](https://img.shields.io/badge/特色-真作/托名双轨声明-red)]()
[![License](https://img.shields.io/badge/协议-MIT-green)](LICENSE)

> 「凡學道輩，欲求永年，先須祛疾。」—— 《辅行诀脏腑用药法要》

> ⚠️ 仅供学习研究，不构成医疗建议。矿物药剧毒，炼丹服食严禁模仿。

## 一句话介绍

隐居茅山 45 年的"山中宰相"：整理《神农本草经》成 730 种《本草经集注》，首创自然属性分类、朱墨分书、诸病通用药——本草学承先启后的里程碑；托名文献《辅行诀》保存《汤液经法》五脏补泻体系，是仲景经方源流之钥。兼为化学先驱（钾盐火焰鉴定世界最早记录）。

**直接激活词**：`陶弘景` / `陶隐居` / `本草考据` / `辅行诀` / `五味补泻`

## 功能矩阵

| 能力 | 说明 |
|:---|:---|
| 谨案体考据 | 药物性味/名实辨误/异文标注（"一本作X當從"） |
| 五味补泻体系 | 五脏德苦口诀 + 20方阵 + 救误五方 + 五行互含25味药精 |
| 二旦六神汤 | 阳旦/阴旦/青龙/白虎/朱鸟/玄武——仲景经方源流 |
| 制剂炮制 | 丸散膏丹汤酒通则（麻黄先煎/半夏汤洗等） |
| 修道-医疗一体 | 欲求永年先须祛疾——祛疾/脏平/内视/守真一次第 |
| 文献双轨 | 真作（本草集注）/托名（辅行诀）严格分标 |

## 快速安装

```bash
git clone https://github.com/gsyguo1995/tao-hongjing-skill.git ~/.claude/skills/tao-hongjing
```

## 数据来源

| 文献 | 性质 | 字数 |
|---|---|---|
| 本草经集注 | 陶弘景真作（敦煌残卷+辑复） | 13.2万 |
| 辅行诀脏腑用药法要 | **托名**陶弘景（敦煌卷子，作者存争议） | 0.85万 |

学术来源（已验证 HTTP 200）：[中国医药信息查询平台](https://www.dayi.org.cn/ancient_physicians/500019.html)、[中国医药大学](https://www2.cmu.edu.tw/~cmcshow/doctorscont.php?i=9)、[维基文库·本草经集注](https://zh.wikisource.org/zh-hans/%E6%9C%AC%E8%8D%89%E7%B6%93%E9%9B%86%E8%A8%BB)

## 目录结构

```
tao-hongjing/
├── SKILL.md              # 主技能文件（自包含）
├── modules/
│   ├── 00_index.md
│   ├── 01-bencao-jizhu.md      # 本草经集注（真作）
│   └── 02-fuxing-jue.md        # 辅行诀（托名）
├── references/
│   ├── 00-keyword-index.md
│   ├── 07-wuwei-buxie.md       # 五味补泻总纲
│   ├── 08-faq.md               # 10题直答
│   └── 23-yangsheng-neishi.md  # 养生内视（简档，素材薄标注）
├── knowledge/research/
└── CHANGELOG.md
```

## 相关项目

| 项目 | 坐标系 | 说明 |
|:---|:---|:---|
| [陈士铎](https://github.com/gsyguo1995/chen-shiduo-skill) | 真假之辨+五行生克 | 清初辨证大师 |
| [唐容川](https://github.com/gsyguo1995/tang-rongchuan-skill) | 气血水火+中西汇通 | 清末汇通学派 |
| **陶弘景**（本库） | 本草考据+五味补泻 | 中古本草开山+道教科学家 |

## 免责声明

本项目内容仅供中医学习与历史研究。矿物药（丹砂/雄黄等）有剧毒，古代炼丹服食为历史现象，严禁模仿。诊疗请咨询执业中医师。

---

*Generated with Distilly + tcm-distiller 方法论 · 2026-10-09*
