# Sovereign Data Core

> "Knowledge is Power. Defend your free speech."

## 📖 Introduction

**Sovereign Data Core** is a minimalist/cyberpunk interactive web experience built on a pure frontend tech stack.

The project explores themes of "Information Censorship," "Digital Sovereignty," and "Free Consciousness." Initially, users face a "Global Information Control Directive" symbolizing totalitarianism. As the system undergoes forced decryption by "Sovereign Nodes," a visual metaphor known as **Blackout Poetry** takes effect—striking out oppressive lies and leaving only core words of truth, ultimately reconstructing a cinematic "Declaration of Freedom."

## ✨ Core Features

- **Redaction Effect**: Utilizes native JavaScript and GSAP to simulate the line-by-line blacking out of highly classified documents to reveal the truth.
- **Cinematic GSAP Timeline**: Eschews complex WebGL/3D libraries, using precise GSAP scheduling of DOM elements to create a sharp visual contrast and emotional release from "oppressive reading" to "grandiose visual."
- **Immersive HUD Interface**:
  - **Real-time Data Stream**: The `SYS.CENSOR_LOG` on the left simulates real-time information interception and resistance.
  - **Holographic Rulers & Grids**: Responsive edges, a shimmering central grid, and giant scrolling background watermarks create depth in a void space.
  - **Dynamic Hashes & Timestamps**: Gives the interface a sense of being "alive."
- **Sacred Geometry SVG**: A central "Sovereign Engine" built with nested SVGs and complex rotation animations.
- **Responsive Z-Index & Layout**: Strict layer management and `mask-image` feathering to prevent overlaps on small screens.

## 🛠️ Tech Stack

Built on the principle of **"Minimalism & Restraint"** to achieve high visual impact without heavy 3D engines.

- **HTML5**: Semantic structure and custom HUD layout.
- **Tailwind CSS (CDN)**: Atomic CSS for responsive grids and typography.
- **GSAP (GreenSock)**: Core timeline animation choreography.
- **Vanilla JavaScript**: Text splitting, real-time mock data generation, and mouse tracking logic.
- **SVG / CSS Filters**: Background noise (`feTurbulence`), dynamic grids, and geometric effects.

## 🚀 Deployment

Single-file static architecture. No build tools (`npm`/`webpack`) or backend required.

1. **Clone/Download** the repository.
2. **Locate** `index.html`.
3. **Open** it in any modern browser (Chrome, Firefox, Safari, Edge) to start the experience.

---

# Sovereign Data Core (主权数据核心)

> "Knowledge is Power. Defend your free speech."
> 知识就是力量。捍卫你的言论自由。

## 📖 项目简介

**Sovereign Data Core** 这是一个基于纯前端技术栈打造的极简主义/赛博朋克风格互动网页体验。

项目探讨了“信息审查”、“数字主权”与“自由意识”。最初，用户会面对一段象征极权与信息管控的《全球信息控制指令》。随着系统遭遇“主权节点”的强制解密，一种名为 **涂黑诗 (Blackout Poetry)** 的视觉隐喻开始生效——所有充满审查与压迫的谎言被无情涂黑，唯独留下了代表真理的核心词汇，最终重构出极具电影感和视觉张力的“自由宣言”。

## ✨ 核心特性

- **动态审查视觉隐喻 (Redaction Effect)**: 结合原生 JavaScript 与 GSAP，模拟高级别机密文档的逐行涂黑与真理揭示过程。
- **GSAP 电影级编排 (Cinematic GSAP Timeline)**: 摒弃了复杂的 WebGL/3D 粒子，仅通过 GSAP 时间轴对 DOM 元素进行精确调度，实现从“压抑的文档阅读”瞬间切换至“宏大主视觉”的强烈视觉反差与情感释放。
- **沉浸式 HUD 界面 (Immersive HUD Interface)**:
  - **实时数据流**: 左侧的 `SYS.CENSOR_LOG` 模拟了实时的信息拦截与审查对抗。
  - **全息标尺与网格**: 边缘的响应式标尺、中央微光网格与背景滚动的巨型水印，打破了扁平感，构建出强烈的深渊空间纵深。
  - **动态跳动的哈希与时间戳**: 赋予界面“活着”的生命力。
- **神圣几何阵列 (Sacred Geometry SVG)**: 中央采用嵌套 SVG 并配以多重旋转动画，构建出神秘且极具科幻感的“主权引擎”。
- **多维度防重叠处理 (Responsive Z-Index & Layout)**: 针对小屏幕和重叠情况进行了严格的 z-index 层级管控和渐变遮罩 (`mask-image`) 羽化处理。

## 🛠️ 技术栈

本项目坚持**“极简与克制”**的原则，在不使用庞大的 3D 库的前提下，实现极佳的视觉表现力。

- **HTML5**: 语义化结构与自定义 HUD 布局。
- **Tailwind CSS (CDN)**: 高效的原子化 CSS，用于快速构建响应式网格、间距与排版。
- **GSAP (GreenSock)**: 用于核心时间轴动画编排。
- **Vanilla JavaScript (原生 JS)**: 用于处理文本拆分、生成实时假数据流以及鼠标跟踪逻辑。
- **SVG / CSS 滤镜**: 用于生成背景噪点 (`feTurbulence`)、动态网格与几何特效。

## 🚀 运行与部署

本项目为纯静态单文件 (Single-file) 架构，无需任何构建工具 (npm / webpack)，无需后端支持。

1. **获取源码**: 克隆或下载本项目。
2. **定位文件**: 找到 `index.html` 文件。
3. **启动体验**: 直接双击在任何现代浏览器（Chrome, Firefox, Safari, Edge）中打开即可。

## 👁️ 视觉设计细则 / Visual Design Details

### 色彩规范 / Color Palette

- **深渊黑 (Abyssal Black)** (`#020202` / void): 象征压抑与控制。 / Symbolizes oppression and control.
- **警告红 (Warning Red)** (`#ff0033` / blood): 象征觉醒与真理。 / Symbolizes awakening and truth.
- **幽灵白 (Ghost White)** (`#f4f4f4` / ghost): 象征纯粹的数据。 / Symbolizes pure data.

### 排版系统 / Typography

- **标题**: 字号极大 (13vw+)，采用 **Syncopate** 字体，配合镂空描边与深黑光晕，制造极其强烈的视觉统治力。
- **Heading**: Large size (13vw+), **Syncopate** font with stroke & glow for visual dominance.
- **HUD/代码**: 采用 **JetBrains Mono** 字体，保留黑客/控制台的硬核质感。
- **HUD/Code**: **JetBrains Mono** for a hard-core console aesthetic.

---

_"They can burn the archives, they can filter the network, but they cannot erase an idea."_
