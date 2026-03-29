# ⌨️ My RIME (rime-ice) Personal Configuration

[English Version](#-english) | [中文说明](#-中文)

---

## 🇺🇸 English

> **Disclaimer:** This is a personal configuration repository tailored for my specific workflow. It is provided "as-is" for reference and synchronization purposes.

This repository contains my highly customized configuration for **RIME (Weasel/rime-ice)**, focusing on the synergy between traditional local engines and modern AI-assisted input.

### ✨ Key Features & Enhancements
* **AI-Powered Error Correction:** Integrated the **[AI-Rime (v3)](https://github.com/BaiZhiXin/AI-Rime)** engine to provide real-time intelligent correction and suggestion.
* **Wanxiang Large Language Model:** Enabled **[wanxiang-lts-zh-hans](https://github.com/mizuka-wu/rime-wanxiang)** grammar support for superior contextual awareness and sentence completion.
* **Advanced Association Engine:** Implemented `lianxiang_translator` via Lua for seamless word and sentence associations.
* **Custom Spelling Algebra:** * Intelligent fuzzy mapping: e.g., `wi` → `wo`.
* **Optimized Filtering:** Custom candidate filters (e.g., iPhone keyword mapping).
* **Balanced Performance:** Fine-tuned `melt_eng` user dictionary and translator constraints for low latency.

---

## 🇨🇳 中文

> **声明：** 本仓库仅包含我个人的 RIME 自用配置文件。主要用于多端同步与备份，欢迎参考，但不保证完全兼容所有环境。

本仓库基于 **[雾凇拼音 (rime-ice)](https://github.com/iD76/rime-ice)**，旨在探索传统输入引擎与现代 AI 技术的深度结合。

### 🚀 核心功能与特性
* **AI 智能纠错：** 集成了来自 **[AI-Rime](https://github.com/BaiZhiXin/AI-Rime)** 的 v3 版核心，实现基于大模型的实时智能纠错与补全。
* **万象大模型注入：** 开启了 **[万象 (Wanxiang-LTS)](https://github.com/mizuka-wu/rime-wanxiang)** 语法支持，大幅提升长句输入的准确度与语境理解力。
* **Lua 联想引擎：** 引入 `lianxiang_translator` 插件，支持更自然的词组与句子联想。
* **自定拼写算法：** * 包含针对性模糊音处理（如 `wi` → `wo`），适配个人输入习惯。
* **精细化过滤：** 自定义候选过滤规则（如 iPhone 专属关键词映射）。
* **性能优化：** 开启了 `melt_eng` 用户词典支持，并对重码显示与上下文建议进行了精细调优。

---

### 🛠️ Environment
* **OS:** Windows 11 (Weasel 0.17.4+)
* **Base Schema:** rime-ice (雾凇拼音)
* **Plugins:** AI-Rime (v3), Wanxiang-LTS (Mizuka-Wu)

*Stay curious. Keep tinkering. 🚀*
