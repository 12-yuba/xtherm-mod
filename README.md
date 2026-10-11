# Xtherm 热成像修改版 · UNLOCK

官方 Xtherm 红外测温（7.0.260325）的修改版，修改过程由 **Gemini** 完成，其余均为官方设定。

## 下载

👉 <https://github.com/12-yuba/xtherm-mod/releases/latest>

### UNLOCK 版本进行了更加深度的功能修改

1. **设置中加入软件解限开关** —— 关闭时仅启用点/线/面数量（点 ×6、线 ×3、面 ×3），避免视觉影响
2. **修改测温点线面数量** —— 点 ×13、线 ×6、面 ×6
3. **解除对部分产品不支持 HD 超分功能的限制** —— 部分场景画面有提升
4. **修复了一些软件功能加入带来的 BUG**

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
