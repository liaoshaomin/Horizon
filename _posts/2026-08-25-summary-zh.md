---
layout: default
title: "Horizon Summary: 2026-08-25 (ZH)"
date: 2026-08-25
lang: zh
---

> 从 69 条内容中筛选出 4 条重要资讯。

---

1. [微软画图与照片应用隐蔽在本地 AI 处理的图像中嵌入唯一 GUID 水印](#item-1) ⭐️ 8.0/10
2. [How Europe is killing makers and micro-entrepreneurs](#item-2) ⭐️ 8.0/10
3. [Moon \(2024\)](#item-3) ⭐️ 8.0/10
4. [The entire city of San Francisco as a video game](#item-4) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [微软画图与照片应用隐蔽在本地 AI 处理的图像中嵌入唯一 GUID 水印](https://xusheng.dev/posts/reversing/mspaint_invisible_watermark/main/) ⭐️ 8.0/10

逆向工程揭示，微软画图（MS Paint）和照片（Photos）应用会在使用本地 AI 功能处理图像时，默默嵌入包含唯一标识符（GUID）的隐形水印。即使是在纯本地进行 AI 处理，这种水印也会在后台自动嵌入，且无需用户知情或同意。 这一发现引发了严重的隐私和安全担忧，因为在生成或编辑的媒体文件中嵌入唯一追踪标识符会破坏网络匿名性，并可能将文件直接追溯至个人用户账户。这凸显了科技公司在 AI 溯源旗号下悄悄注入持久元数据所引发的日益增长的争议。 虽然用户可以在应用设置中关闭可视的 AI 水印，但该隐藏的隐写水印无法被用户关闭。关于这种嵌入的 GUID 在面对 JPEG 重新压缩或裁剪等常见图像修改时具有多强的抗破坏性，相关技术细节仍待进一步验证。

hackernews · ComputerGuru · 8月24日 15:28 · [社区讨论](https://news.ycombinator.com/item?id=49421158)

**背景**: 数字水印和隐写术是指在不明显改变媒体文件外观的情况下，将元数据或唯一签名等数据隐藏在文件中的技术。微软最近在画图和照片等标准 Windows 桌面应用中引入了图像生成和背景消除等本地 AI 驱动的功能。

**社区讨论**: 社区对隐私和用户追踪表达了强烈担忧，强调唯一的 GUID 可能会使版权传票或法律诉讼通过微软账户轻松揭露匿名用户的身份。评论者还对这种隐形隐写技术抵御有损压缩的技术耐久性提出疑问，并批评微软不当强制注入元数据的做法。

**标签**: `#Privacy`, `#Microsoft`, `#Reverse Engineering`, `#AI`, `#Security`

---

<a id="item-2"></a>
## [How Europe is killing makers and micro-entrepreneurs](https://lectronz.com/u/lectronz/articles/how-europe-is-killing-makers-and-micro-entrepreneurs) ⭐️ 8.0/10

The article critiques proposed EU packaging regulations for imposing overwhelming compliance burdens on independent makers and micro-entrepreneurs, igniting a widespread debate on European business policy.

hackernews · l-one-lone · 8月24日 13:05 · [社区讨论](https://news.ycombinator.com/item?id=49419237)

**标签**: `#EU Regulation`, `#Hardware`, `#Micro-entrepreneurs`, `#Policy`, `#E-commerce`

---

<a id="item-3"></a>
## [Moon \(2024\)](https://ciechanow.ski/moon/) ⭐️ 8.0/10

An in-depth, interactive visual article explaining the physics, orbit, rotational dynamics, and phases of the Moon.

hackernews · simonebrunozzi · 8月24日 22:06 · [社区讨论](https://news.ycombinator.com/item?id=49426466)

**标签**: `#Data Visualization`, `#Astronomy`, `#Interactive Media`, `#Web Development`

---

<a id="item-4"></a>
## [The entire city of San Francisco as a video game](https://sf.thijs.gg/) ⭐️ 8.0/10

An interactive web application that renders the entire city of San Francisco as a playable, drivable 3D video game environment.

hackernews · centrosphere · 8月24日 17:05 · [社区讨论](https://news.ycombinator.com/item?id=49422784)

**标签**: `#3D Graphics`, `#Game Development`, `#GIS`, `#Web Development`, `#Procedural Generation`

---