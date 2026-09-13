# club-oa-app（客户端壳集合）

| 目录 | 形态 | 技术 |
| --- | --- | --- |
| `android-shell/` | Android App（PWA 壳） | Kotlin + WebView + 厂商推送 SDK |
| `harmony-shell/` | HarmonyOS NEXT App（PWA 壳，规划中） | ArkTS + ArkWeb + Push Kit |
| `electron/` | 桌面端（Windows/macOS/Linux，规划中） | Electron + 共享 Vue 前端 |

共同要求（见需求 13.1.1）：**服务器地址不硬编码**，首次启动配置并校验 OIDC discovery，支持随时切换。
