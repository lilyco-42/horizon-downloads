# 云枢 Horizon 下载站

Horizon（Minecraft Java Edition 26.3 Rust 重制客户端）· 全平台安装包 · 完整离线包 · 资源库

服务器：`123.60.38.191:25565`（离线验证 + 白名单）

## 下载

**Windows 电脑 → 下载 `horizon-launcher-setup.exe` 双击安装（标准安装向导，不用解压任何 zip）**
**Android 手机 → 下载 `Horizon-Android-v1.0.1-arm64-v8a.apk` 点击安装**

| 需求 | 去哪 |
|---|---|
| Windows / 安卓 / Linux / macOS 客户端 | [Releases → client-v1.0.1](https://github.com/lilyco-42/horizon-downloads/releases/latest) |
| 完整离线包（含 110 资源 + 19 mod，约 1.2 GB） | [Releases → offline-full-v1.0.1](https://github.com/lilyco-42/horizon-downloads/releases) |
| 鸿蒙 HarmonyOS NEXT（AMCL 方案） | Releases → client-v1.0.1 里的 amcl 文件 |

### Windows

`horizon-launcher-setup.exe`（x64，绝大多数电脑）双击一路下一步；`horizon-launcher-setup-arm64.exe` 仅限骁龙本等 ARM 设备。

### Android

`Horizon-Android-v1.0.1-arm64-v8a.apk`（现代手机首选）→ 传手机安装 → 允许「未知来源」→ 打开 Horizon。

### Linux / macOS

Linux 用 `horizon-launcher-linux-x86_64.AppImage`（chmod +x 后直接运行）；macOS 按芯片选 dmg（M 系列选 arm64，Intel 选 x64）。

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

## 夸克网盘 · 按需下载（点哪个下哪个，永久有效、免提取码）

**Windows：**
- `horizon-launcher-setup.exe`（x64，绝大多数电脑）→ https://pan.quark.cn/s/343a17aa21e3
- `horizon-launcher-setup-arm64.exe`（骁龙本）→ https://pan.quark.cn/s/ec7de7b2cfd8

**Android：**
- `Horizon-Android-v1.0.1-arm64-v8a.apk`（现代手机首选）→ https://pan.quark.cn/s/c38837286191
- `Horizon-Android-v1.0.1-armeabi-v7a.apk`（32 位老机型）→ https://pan.quark.cn/s/86f45daabb5d
- `Horizon-Android-v1.0.1-x86_64.apk`（x86_64 模拟器）→ https://pan.quark.cn/s/caff8b1c015d
- `Horizon-Android-v1.0.1-x86.apk`（32 位模拟器）→ https://pan.quark.cn/s/b095778e29d3
- `horizon-android-light-1.0.1.zip`（在线轻量包）→ https://pan.quark.cn/s/fb7aec56dd83

**Linux / macOS：**
- `horizon-launcher-linux-x86_64.AppImage` → https://pan.quark.cn/s/3f1e8bbc9bd2
- `horizon-launcher-macos-arm64.dmg`（M1–M4）→ https://pan.quark.cn/s/9e7dc7c62b99
- `horizon-launcher-macos-x64.dmg`（Intel）→ https://pan.quark.cn/s/c179d20b73a4

**鸿蒙 HarmonyOS NEXT：**
- `amcl-v1.0.7-sideload-unsigned.hap`（侧载包）→ https://pan.quark.cn/s/a3672b581f33
- `amcl-harmony-1.0.7.zip` → https://pan.quark.cn/s/87146250beed

**完整离线包（1.2 GB，含 110 资源 + 19 mod）：**
- `horizon-offline-full-1.0.1.zip` → https://pan.quark.cn/s/70aab3261dd3

GitHub 直链与网盘直链内容完全一致，下载慢就换另一边。
