# 🎼 Metrical Dissonance Simulator

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

这是一个基于纯前端技术栈构建的交互式视听工具，旨在直观地模拟和演示音乐理论中的**节拍不协和 (Metrical Dissonance)**。

本项目深度结合了音乐理论家哈拉尔德·克雷布斯 (Harald Krebs) 的学术理论，将抽象的节奏冲突转化为可视化的网格与可听见的序列，非常适合用于音乐理论教学、节奏编排测试以及学术演示。

## ✨ 核心特性 (Features)

- 🎵 **双重不协和模型**：
  - **分组不协和 (Grouping Dissonance)**：模拟多重节拍的交叉重叠，并动态生成严谨的学术公式（如 `G 4/3`）。
  - **位移不协和 (Displacement Dissonance)**：模拟同一节拍在时间轴上的平移错位（如 `D 3+2`）。
- 📊 **自适应视觉网格**：直观展示“基础层 (Base Layer)”与“冲突层 (Conflict Layer)”的运行轨迹。内置最小公倍数 (LCM) 算法寻找协和交汇点，并设有 32 步长上限保护机制，防止大周期运算导致界面溢出。
- 🎹 **硬核音频引擎**：采用原生 `Web Audio API` 生成正弦波音频。内置特殊的系统唤醒与音频通道劫持逻辑，**完美突破 iOS/Safari 等移动端设备在“静音模式”下的发声限制**。
- 🌍 **原生多语言 (i18n)**：支持实时无缝切换 **日本語 (默认)**、**简体中文** 和 **English**。
- 🏛️ **典雅学术排版**：全面摒弃粗体，采用高优先级的 `Times New Roman` 结合各语言专属衬线体（明朝体 / 宋体），呈现出如学术文献般纯粹的视觉质感。
- 🛡️ **安全交互逻辑**：在播放状态下更改任何参数（类型、节拍数值、BPM），系统会瞬间触发自动停止并重置游标，避免视听错乱。

## 🚀 快速开始 (Quick Start)

本项目为完全静态的纯前端单页面应用 (SPA)，**零依赖，无需构建**。

1. 克隆或下载本仓库至本地。
2. 双击打开 `index.html`，推荐使用现代浏览器（如 Chrome, Safari, Edge）。
3. 调整各项参数，点击 **「再生 / 一時停止 (Play / Pause)」** 即可体验。

## 🛠️ 技术栈 (Tech Stack)

- HTML5
- CSS3 (Flexbox 布局, 动态字体挂载)
- Vanilla JavaScript (无任何第三方库)
- Web Audio API

## 📄 许可证与版权 (License & Copyright)

本项目遵循 **[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)** (署名 4.0 国际) 协议开源。

- 允许任何人在任何媒介以任何形式复制、发行本作品。
- 允许修改、转换或以本作品为基础进行创作，甚至用于商业目的。
- **唯一限制**：必须给出适当的署名（Attribution Required）。

© 2026 Xing-Yu Zhu. All rights reserved.
