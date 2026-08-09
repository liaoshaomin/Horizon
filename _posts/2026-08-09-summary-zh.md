---
layout: default
title: "Horizon Summary: 2026-08-09 (ZH)"
date: 2026-08-09
lang: zh
---

> 从 50 条内容中筛选出 1 条重要资讯。

---

1. [UTM 推出 Triton：用于 QEMU 虚拟机的 DirectX 11 驱动程序](#item-1) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [UTM 推出 Triton：用于 QEMU 虚拟机的 DirectX 11 驱动程序](https://blog.getutm.app/2026/introducing-triton-directx-11-driver-for-qemu/) ⭐️ 8.0/10

UTM 宣布推出 Triton，这是一款专为 QEMU 开发的新型开源 DirectX 11 驱动程序，可为 Windows 虚拟机带来硬件加速的 3D 图形性能。这使得虚拟机中的 Windows 环境能够直接利用宿主机的 GPU 资源运行 3D 负载，而无需依赖 dedicated GPU 直通。 长期以来，在 Linux 或 macOS 上的 Windows 虚拟机中实现流畅的 3D 图形加速一直是一项复杂的任务，往往需要专门的硬件直通配置。Triton 降低了虚拟化用户的技术门槛，大幅提升了在虚拟化环境中运行 DirectX 11 游戏和应用的可行性。 Triton 专门针对 QEMU 虚拟化图形架构中的 DirectX 11 API 加速。通过转换 DirectX 指令以共享宿主机的 GPU，它为桌面虚拟化提供了一个高性能的虚拟驱动方案。

hackernews · electricant · 8月8日 13:33 · [社区讨论](https://news.ycombinator.com/item?id=49221711)

**背景**: QEMU 是一款被广泛使用的开源模拟器与虚拟化软件，但由于虚拟 GPU 驱动支持有限，Windows 虚拟机系统的图形性能长期受限。如果没有 GPU 直通（即将一块物理显卡直接分配给虚拟机，通常需要两块物理显卡），Windows 虚拟机内的 3D 渲染只能依赖缓慢的软件模拟。

**社区讨论**: 社区成员对该驱动程序的推出表示欢迎，并指出在单 GPU 的 Linux 配置下，过去的 GPU 直通一直是进行游戏和 3D 任务时的一大痛点。几位评论者还询问了该驱动是否同时支持较旧的 DirectX 版本（DX1-10），或者类似的解决方案能否移植到 VirtualBox 等其他虚拟机软件中。

**标签**: `#Virtualization`, `#QEMU`, `#DirectX`, `#GPU Acceleration`, `#Linux`

---