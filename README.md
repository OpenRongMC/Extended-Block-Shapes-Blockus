# 扩展方块形状 · Blockus 联动

上游说明见主模组 [Extended-Block-Shapes](https://github.com/OpenRongMC/Extended-Block-Shapes) 的 README（Blockus 章节）。

本子模组在安装 **Blockus** 与 **Extended Block Shapes** 时，为 Blockus 方块补充楼梯/台阶等形状变种。

---

## RongMC · Minecraft 26.3 Fabric 移植说明

本仓库是 RongMC 维护的 **Minecraft 26.3 / Fabric / Java 25** 移植构建，不是上游官方发行渠道。

### 与原版的主要差异
- Minecraft 26.3；Fabric id `rongmc_extshape_blockus`（provides `extshape_blockus`）。
- 硬依赖 `blockus` 与 `rongmc_extshape`。

### 已知问题 / 限制
- 未安装 Blockus 时不应装本模组（依赖无法满足）。
- Blockus 自身版本需与 26.3 匹配，否则内容对不上。

### 构建与安装
- Fabric mod id：`rongmc_extshape_blockus`（`provides`：`extshape_blockus`，旧依赖名一般仍可解析）
- Release 产物见本仓库 Releases（jar 名带 `rongmc-` 前缀）
- 许可证：本仓以 **GPL-3.0** 发布（见 `LICENSE`）；请同时尊重上游原作者条款与署名

