# 扩展方块形状 · Blockus 联动

简体中文 · [English](./README.en.md)

为 Blockus 的建材补充扩展方块形状，把 Blockus 材质用到主模组提供的更多建筑构件上。

## 下载与安装

- 版本 · [v3.2.2](https://github.com/OpenRongMC/Extended-Block-Shapes-Blockus/releases/tag/v3.2.2) (已发布)
- 下载文件 · `rongmc-extshape_blockus-fabric-3.2.2.mc26.3.jar`
- 运行环境 · Minecraft Java 26.3, Fabric, Java 25
- Fabric 模组 ID · `rongmc_extshape_blockus`
- JAR 声明的依赖 · [Fabric API](https://modrinth.com/mod/fabric-api), `blockus` `>=2.18.2`, [`rongmc_extshape`](https://github.com/OpenRongMC/Extended-Block-Shapes) `>=3.2.0`

把发行 JAR 放入对应实例的 `mods/` 目录。这是联动子模组，两端须同时有 Blockus、Extended Block Shapes 与本扩展。选择三个项目都支持的 Minecraft 26.3 发行。

## 如何验证

用一款 Blockus 建材查找对应楼梯或其他变体，再实测放置和方向。遇到缺材质或注册失败时，附上三份 JAR 的版本。

## 开发

构建入口见 [`build.gradle`](./build.gradle)。运行前检查脚本需要的工作区目录与依赖。

## 文档与反馈

- [原 README（旧版指南、贡献者与署名）](https://github.com/OpenRongMC/Extended-Block-Shapes-Blockus/blob/499072c7f209929c075c486636dbc06d64e3a472/README.md)
- [上游项目与文档](https://github.com/SolidBlock-cn/extshape)
- [报告 RongMC 移植问题](https://github.com/OpenRongMC/Extended-Block-Shapes-Blockus/issues) · 请附游戏版本、两端 JAR 文件名、复现步骤和相关日志。

## 许可与署名

请参阅本仓库的 [LICENSE](./LICENSE) 及原项目的许可、署名和第三方资源说明。
