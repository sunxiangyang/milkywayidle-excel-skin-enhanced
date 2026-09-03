# MilkyWayIdle - Excel 换肤（自定义仓库）

这是基于 Greasy Fork 脚本 573318（版本 1.0.5）的本地 fork 基线。

## 来源

- 原脚本：https://greasyfork.org/scripts/573318
- 原始源码：https://update.greasyfork.org/scripts/573318/MilkyWayIdle%20-%20Excel%E6%8D%A2%E8%82%A4.user.js

## 开始修改

脚本文件为 `milkywayidle-excel.user.js`。修改后请递增 `@version`，并在发布前将 `@downloadURL` / `@updateURL` 改为你自己仓库的地址或删除。

当前源码保留原作者的元数据和许可证声明。重新发布时请保留版权及 MIT 许可证，并明确列出你的修改。

## 本地修改

- 修复开启“隐藏库存图标”后，从其他页面切换到“装备”页面时物品名称没有重新注入的问题。现在会在游戏根节点发生 React 页面更新时重新扫描并注入装备名称。

## 许可证

MIT License，详见 [LICENSE](LICENSE)。依赖库和资源可能适用各自的许可证。
