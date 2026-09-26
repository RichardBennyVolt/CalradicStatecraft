# Calradic Statecraft / 卡拉迪亚政略

A single-player governance mod for Mount & Blade II: Bannerlord, with Simplified Chinese and English localization.

《骑马与砍杀2：霸主》单人政略模组，支持简体中文与英文。

## Download / 下载

Open this repository's **Releases** page and download `CalradicStatecraft-v1.3.39-Release.zip`. The automatically generated **Source code** archives are not the mod installer.

请进入本仓库的 **Releases** 页面，下载 `CalradicStatecraft-v1.3.39-Release.zip`。GitHub 自动生成的 **Source code** 压缩包不是模组安装包。

This repository distributes packaged releases and installation information. Its tags identify the distribution files, not the private development repository's complete source history.

本仓库用于分发安装包与安装说明；标签对应发布资料，不代表完整的开发源码历史。

## Gameplay / 玩法

- Governments, laws and titles: reform tax and military-service rules, meet promotion requirements, and change government when the legal and political conditions are met.
- Treasury and administration: collect taxes, track expenditure, subsidize eligible wages and construction, issue bonds, and delegate work to cabinet officials.
- Personal stewardship: landed non-rulers can manage their own estates using a separate family fund, including procurement, recruitment, training and patrols.
- Succession and politics: hereditary succession, native elections, 80-day republican terms, noble factions, legitimacy and coups with hall combat and aftermath.
- Player kingdoms: choose a government and an available fixed coup-hall template when first initializing governance.

- 制度、法律与爵位：调整税收和兵役规则，按资格晋升爵位，满足法律与政治条件后转换制度。
- 国库与行政：征税、查看支出、补贴符合范围的工资和建设、发行债券，并通过内阁官员办理事务。
- 私人管家：有封地的非统治者可用独立家族基金管理自有产业，开展采购、征兵、训练和巡逻。
- 继承与政治：世袭继承、原版选举、共和制80日任期、贵族派系、合法性，以及大厅战斗与战后处置。
- 玩家自立国：首次初始化政略时选择制度和可用的固定政变大厅模板。

## Requirements / 游玩条件

- Bannerlord **v1.4.8**, single-player **Campaign or Sandbox**.
- Four required dependencies, installed separately: **Harmony v2.4.2.248**, **ButterLib v2.12.0**, **UIExtenderEx v2.13.3**, **Mod Configuration Menu v5 / MCM v5.12.3**.
- War Sails is optional. Nord content loads only when the required DLC content is active.
- 游戏版本 **v1.4.8**，支持单人**战役与沙盒**。
- 四项前置必须另行安装：**Harmony v2.4.2.248、ButterLib v2.12.0、UIExtenderEx v2.13.3、Mod Configuration Menu v5 / MCM v5.12.3**。
- War Sails 为可选内容；所需DLC内容启用时才加载诺德内容。

## Installation and load order / 安装与加载顺序

1. Close Bannerlord and its launcher. Back up saves before updating.
2. Extract the ZIP so that `Modules/CalradicStatecraft/SubModule.xml` exists. Replace the previous mod folder as a complete version; do not mix files from different versions.
3. Enable the dependencies and mod in the launcher, in this top-to-bottom order:

   **Harmony → ButterLib → UIExtenderEx → MCM v5 → official modules in dependency order → Calradic Statecraft**

   The core official order is **Native → SandBox Core → Sandbox**. Enable **StoryMode** for Campaign. When **War Sails / NavalDLC** is enabled, retain its required official dependencies, including **StoryMode**, and load NavalDLC after Calradic Statecraft. Keep other enabled official modules in the launcher's dependency order. Avoid duplicate dependency/mod installations.
4. Enter a settlement and look for **Kingdom Governance** in its menu.

1. 关闭游戏和启动器，更新前备份存档。
2. 解压后应形成 `Modules/CalradicStatecraft/SubModule.xml`。以完整版本替换旧模组目录，避免混合不同版本文件。
3. 启动器中自上而下加载：

   **Harmony → ButterLib → UIExtenderEx → MCM v5 → 按依赖排序的官方模块 → Calradic Statecraft**

   官方基础顺序为 **Native → SandBox Core → Sandbox**；战役模式启用 **StoryMode**。启用 **War Sails / NavalDLC** 时，保留其要求的 **StoryMode** 等官方依赖，并将 NavalDLC 放在政略之后。其他已启用官方模块保持启动器依赖排序，前置与模组均避免重复安装。
4. 进入定居点，在菜单中打开**王国政略**。

## V1.3.39 release information / 版本说明

The Release-configuration package expands player-founded kingdoms' initial hall selection to six base-game templates, plus the Nord template when its DLC requirements are met. Existing kingdoms retain their saved hall selections. Save schema remains 32.

本 Release 配置安装包将玩家自立国的首次大厅选择扩展为六套本体模板，满足DLC条件时另提供诺德模板；已初始化国家保留原有大厅选择。存档 Schema32 不变。

The existing launcher display name includes **“V1.3.39 Test”**. This is the verified package's name and does not indicate a Debug build. Automated build, regression and package checks passed; that evidence does not replace in-game scene, navigation, combat and save/load testing.

启动器显示名保留 **“V1.3.39 Test”**，这是已核验安装包的既有名称，不表示该包为 Debug 构建。自动构建、回归与包完整性检查已通过；这些检查不代替大厅场景、导航、战斗与存读档的实机验收。

When reporting an issue, include the mod/game versions, Campaign or Sandbox, DLC state, reproduction steps and relevant logs. Do not post account credentials or unrelated personal files.

反馈问题时请附模组与游戏版本、战役或沙盒、DLC状态、复现步骤和相关日志；勿上传账号凭据或无关私人文件。
