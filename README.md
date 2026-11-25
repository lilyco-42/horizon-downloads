# 云枢 Horizon 下载站

Horizon（Minecraft Java Edition 26.3 Rust 重制客户端）· 全平台安装包 · 完整离线包 · 资源库

服务器：`123.60.38.191:25565`（离线验证 + 白名单）

## 下载

| 需求 | 去哪 |
|---|---|
| 手机/电脑客户端安装包 | [Releases → client-v1.0.1](https://github.com/lilyco-42/horizon-downloads/releases/latest) |
| 完整离线包（含 110 资源 + 19 mod，约 1.2 GB） | [Releases → offline-full-v1.0.1](https://github.com/lilyco-42/horizon-downloads/releases) |
| 鸿蒙 HarmonyOS NEXT（AMCL 方案） | Releases → client-v1.0.1 里的 amcl 文件 |

### Android（首选 arm64）

`Horizon-Android-v1.0.1-arm64-v8a.apk` → 传手机安装 → 允许「未知来源」→ 打开 Horizon。

### 桌面

Windows x64 用 `horizon-launcher-setup.exe`；Linux 用 AppImage（chmod +x）；macOS 按芯片选 dmg。

### 鸿蒙 NEXT

`amcl-v1.0.7-sideload-unsigned.hap` 为**未签名侧载包**，需 DevEco 自动签名或 hap-sign-tool 重签后 `hdc install`；详见同 Release 的 `harmony-README.txt`。AMCL 跑原版客户端（无 Horizon 渲染优化，.hmod 不可用），是鸿蒙当前唯一可玩路径。

## 进服三步

1. 客户端添加服务器 `123.60.38.191:25565`
2. QQ 添加机器人「lyco」，私聊发 `绑定 <游戏ID> <邀请码>`（邀请码向服主索取，一码一人）
3. 回复「绑定成功」后进服

常用机器人指令：`帮助 / 我的 / 解绑 / 查询 / 地址 / 状态 / 教程 / 下载 / 资源 / 光影 / mod / 备份`

## 校验

每个 Release 附 `SHA256SUMS`。

## 相关仓库

- [lilyco-horizon](https://github.com/lilyco-42/lilyco-horizon) — Horizon mod 开发全家桶 + Web Studio
- 各 mod 独立仓：[horizon-mod-ysm](https://github.com/lilyco-42/horizon-mod-ysm) 等（README 有全表）
- [kuake-studio](https://github.com/lilyco-42/kuake-studio) — 夸克网盘客户端（资源库网盘入口）

## 版权说明

- Horizon 客户端：上游 github.com/GoyDevv（桌面版官网 playhorizon.dev）
- Horizon-Android：github.com/GoyDevv/Horizon-Android
- AMCL：GPL-3.0 社区维护
- 资源包/光影来自 Modrinth 公开下载（各自的许可证适用于各自内容）
