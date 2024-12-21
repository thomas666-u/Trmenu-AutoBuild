# CoreProtect-AutoBuild

每日自动拉取并构建一次CoreProtect。

## 为什么会有这个仓库？

自2024年5月推出22.4版本后，CoreProtect未再发布适用于Minecraft 1.21的更新。然而，通过在Patreon上支持该项目，用户可以获得最新构建版本。

尽管开发者未在SpigotMC或Modrinth平台更新，CoreProtect的GitHub仓库持续保持活跃更新。因此，我们得以维护一个每日同步最新构建版本的仓库。

## 注意事项

本仓库构建的 CoreProtect 为 `development` 版本。根据 SpigotMC 及 Discord 上其他用户的反馈，**手动拉取仓库构建的这些版本**无法使用`22.4`及之前版本的数据库，因此你需要删除原来的数据库才能继续使用这些版本的插件。

提示：

- 如果你使用的是SQLite数据库，我建议你将原来的数据库及插件增加一个`.disabled`的后缀名来禁用，需要恢复的时候把后缀名删掉即可。
- 如果你用的是MySQL，那为啥不直接新建一个数据库呢？

## 汉化文件下载及使用

请按照以下步骤操作以更新 CoreProtect 插件的语言文件：

1. 前往[MineBBS](https://www.minebbs.com/resources/coreprotect.8820/)下载中文语言文件压缩包。
2. 解压下载的文件，找到解压后得到的 `language.yml` 文件。
将此新的 `language.yml` 文件复制到你的服务器插件目录中，路径为 `/plugins/CoreProtect/`。
3. 注意: 复制时，请确保替换现有的 `language.yml` 文件。这将用新下载的版本覆盖旧版本。
4. 完成上述步骤后，CoreProtect 插件将使用更新后的语言设置。建议在执行此操作前备份当前的语言文件，以防需要恢复到之前的设置。

## CoreProtect 介绍

![CoreProtect](https://userfolio.com/uploads/coreprotect-banner-v19.png)

CoreProtect is a blazing fast data logging and anti-griefing tool for Minecraft servers.
CoreProtect 是适用于 Minecraft 服务器的超快速数据记录和反恶意破坏工具。

For a detailed description of the plugin, please visit [coreprotect.net](https://coreprotect.net).
有关插件的详细说明，请访问 [coreprotect.net](https://coreprotect.net)。

## bstats

[![bStats Graph Data](https://bstats.org/signatures/bukkit/CoreProtect.svg)](https://bstats.org/plugin/bukkit/CoreProtect)
