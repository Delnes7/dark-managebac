# Dark ManageBac

给北京十一学校的 ManageBac 加上深色模式。这是一个 Tampermonkey（油猴）脚本，适用于 `bnds.managebac.cn`。

默认跟随系统外观，也可以手动切到深色或浅色。深色模式下，课表卡片会保留出勤状态的颜色区分，侧栏的快捷键标签也更容易看清。

## 安装

1. 在浏览器里安装 [Tampermonkey](https://www.tampermonkey.net/)。
2. 打开 [Dark-ManageBac.user.js](https://raw.githubusercontent.com/Delnes7/dark-managebac/main/Dark-ManageBac.user.js)。如果弹出 Tampermonkey 安装页，点击「安装」。如果浏览器直接显示代码，就复制全部内容，在油猴菜单里选择「添加新脚本」，替换编辑器里的默认内容并保存。
3. 打开或刷新 [学校的 ManageBac](https://bnds.managebac.cn/)。

如果 Chrome 或 Edge 提示脚本未获运行权限，可以在浏览器的扩展详情里检查 Tampermonkey 的「允许用户脚本」设置。各版本的入口见 [Tampermonkey 官方说明](https://www.tampermonkey.net/faq.php?locale=en&q=Q209)。

## 切换主题

在 ManageBac 页面点浏览器工具栏里的油猴图标，就能在此脚本的菜单中切换主题。

| 选项 | 效果 |
| --- | --- |
| 跟随系统 | 默认选项。系统在深色和浅色之间切换时，页面会同步切换。 |
| 始终深色 | 保持深色模式。 |
| 始终浅色 | 使用网站原有的浅色样式。 |

选择会立即生效，刷新后也会保留。

## 更新

打开仓库里的最新版 [Dark-ManageBac.user.js](./Dark-ManageBac.user.js)，复制全部代码，替换油猴里原来的脚本。保存后刷新 ManageBac，原有的主题设置会保留。

## 致谢

脚本内置 [Dark Reader](https://github.com/darkreader/darkreader) 的动态主题引擎。Dark Reader 的 MIT 许可证随脚本附带。
