# Xtherm 热成像修改版 · 功能解限

官方 Xtherm 红外测温（7.0.260325）的修改版：**解除点测温数量限制，由官方的 3 个点解锁为 6 个点**，其余功能与官方版本完全一致。

修改过程由 **Gemini** 完成，其余均为官方设定。

## 下载

👉 <https://github.com/12-yuba/xtherm-mod/releases/latest>

## 改了什么

- 点测温数量上限：官方 3 个 → **6 个**
- 其余功能与官方版一致

## 与官方版的实测差异

| 项目 | 官方版 | 本版本 |
|---|---|---|
| zip 条目数 | 5529 | 5486 |
| `classes.dex` | 8,010,528 B | 7,904,420 B（有改动） |
| `classes2/3/4.dex` | — | 均有改动 |
| `AndroidManifest.xml` + 全部 res | — | CRC 完全一致，未改动 |
| 签名 | `META-INF/CERT.RSA` | `META-INF/ANDROIDD.RSA` |
| `META-INF/androidx.*.version` | 43 个 | 已移除 |

## 安装注意

本版本为重新签名包 —— 手机若已装官方 Xtherm，**先卸载官方版**再装本版。

## 文件信息

- `geminiXtherm_unlocked.apk` — 73,005,352 字节（69.6 MB）
- MD5：`5feaa81b3520b1d65f46609969b79c50`
- SHA256：`779196fab0f6ee00312faf27ef96ea2bbada5287acd4a748ba5eac19d7c2c2fb`

## 免责

仅供个人学习交流，应用版权归原厂所有，请勿用于商业用途。
