<p align="center">
  <img src="./logo.png" alt="LoomEngine Logo" width="150" height="150" />
</p>

<h1 align="center">LoomEngine 🚀</h1>

<p align="center">
  <strong>Weaving Legacy Stability and Future Performance. Seamlessly.</strong><br>
  下一代多端动态化原生容器。Android/iOS 守旧求稳，HarmonyOS 激进求快。
</p>

<p align="center">
  <a href="https://loomengine.dev">🌍 Website</a> •
  <a href="https://docs.loomengine.dev">📚 Documentation</a> •
  <a href="mailto:contact@loomengine.dev">💬 Enterprise Support</a>
</p>

---

## 💡 Our Vision (我们的愿景)

性能与动态化永远是技术决策天平的两端，而新的操作系统（**HarmonyOS NEXT**）又带来了沉重的跨越成本。

**LoomEngine** 致力于打破这种二元对立。

我们不强求上层业务重写，也不强求全盘升级技术栈。我们提供一个高抽象的底层“织布机（Loom）”，根据业务 Bundle 的终点，自动为其选择最完美的渲染管线和通信架构。LoomEngine 让企业能够**零成本迁移老旧老 RN 业务到纯血鸿蒙**，同时在鸿蒙端享受极致的新架构性能体验。

## 🎯 Our Core Strategy: Hybrid-Engine Routing (混合引擎路由)

这是 LoomEngine 的核心壁垒。我们在容器底层设计了一套智能路由分发器，针对不同世代的 RN 架构提供不同的运行时：

| 平台 (Platform) | 渲染架构 (Architecture) | 通信机制 (Bridge) | 状态与卖点 (Status & Selling Point) |
| :--- | :--- | :--- | :--- |
| **Android & iOS** | **Legacy (守旧派)** | 旧 Bridge | **稳！** 兼容现有的海量第三方库和历史业务代码，零风险运行。 |
| **HarmonyOS (NAPI)** | **New Architecture (激进派)** | 新 JSI / Bridgeless | **快！** 深度集成 NAPI，操作 C++ `jsi::Runtime`，实现分包毫秒级注入与原生秒开。 |

一套业务代码，在 LoomEngine 的织造下，不仅跨越了平台，更无缝跨越了技术世代。

## 🧩 The Loom Ecosystem (产品生态矩阵)

我们采用 **Open Core（核心开源）** 战略：

### 🟢 开源底座：LoomEngine Core (MIT License)
跨平台高性能动态容器。100% 开源，建立信任。
* **一框两制：** 核心 C++ 层完美适配老 Bridge 和新 JSI/NAPI 两套环境。
* **JSI 注入器：** 针对新架构的 C++ TurboModule，利用 `mmap` 读取字节码。
* 📦 [**探索 `loomengine-core` 仓库**](link-to-repo)

### 🟡 构建工具：Loom Compiler (Free for Dev)
专为超级 App 设计的极限分包构建链。
* **AST 智能分析：** 自动剥离基础包 (Base.hbc) 与业务包 (Biz.hbc)。

### 🔴 企业级云原生：LoomCloud (SaaS / 私有化部署)
企业级热更新与安全管控。
* ** bsDiff 差分更新：** 更新包体积骤降 90%。
* **精细化灰度与定向鸿蒙下发：** 按鸿蒙特定的 API 版本精准灰度发布。
* 💼 [**了解企业版及 SaaS 订阅**](link-to-saas-pricing)

## 🤝 Connect & Contribute

LoomEngine 的“混合”战略为跨端迁移提供了一条全新的、极具性价比的路径。我们欢迎：
* **鸿蒙生态开发者：** 一起完善 NAPI 和 JSI 的底层桥接。
* **Android/iOS 资深开发者：** 维护老 Bridge 的稳定性瓶颈。

---

<p align="center">
  <i>Built with ❤️ by the LoomEngine Team & Community.</i>
</p>
