# T&F Dashboard 审稿人邀请徽章

[![许可证: MIT](https://img.shields.io/badge/许可证-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![版本](https://img.shields.io/badge/版本-1.0.0-green.svg)](https://greasyfork.org/zh-CN/scripts/545460-t-f-dashboard-reviewer-invite-badges)
[![在 Greasy Fork 安装](https://img.shields.io/badge/安装于-Greasy%20Fork-blue.svg)](https://greasyfork.org/zh-CN/scripts/545460-t-f-dashboard-reviewer-invite-badges)
[![Greasy Fork 下载量](https://img.shields.io/greasyfork/dt/545460?label=下载量)](https://greasyfork.org/zh-CN/scripts/545460-t-f-dashboard-reviewer-invite-badges)

一个用于在 Taylor & Francis Dashboard 稿件卡片中"Out for Review"状态旁显示审稿人邀请徽章的用户脚本。

## 用途

该用户脚本通过在界面中自动显示审稿人邀请时间戳和修订版本号来增强 T&F Dashboard 功能。帮助作者快速查看每轮投稿中审稿人的邀请时间。

![功能截图](feature.jpg)

## 徽章格式

每个徽章显示格式：`R{修订版本} Invite: YYYY-MM-DD HH:mm`

示例：
- `R0 Invite: 2024-04-06 14:27`
- `R1 Invite: 2025-01-03 11:21`

## 安装方法

### 快速安装（推荐）
1. **[从 Greasy Fork 直接安装](https://greasyfork.org/zh-CN/scripts/545460-t-f-dashboard-reviewer-invite-badges)**
2. 您的用户脚本管理器（Tampermonkey/Greasemonkey）将自动处理安装过程

### 手动安装

#### Tampermonkey (Chrome/Edge)
1. 安装 [Tampermonkey 扩展](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
2. 复制 `main.js` 文件内容
3. 在 Tampermonkey 中创建新的用户脚本并粘贴代码
4. 保存并启用脚本

#### Greasemonkey (Firefox)
1. 安装 [Greasemonkey 扩展](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)
2. 复制 `main.js` 文件内容
3. 在 Greasemonkey 中创建新的用户脚本并粘贴代码
4. 保存并启用脚本

## 使用方法

1. 使用上述方法之一安装用户脚本
2. 访问 Taylor & Francis Dashboard：`https://rp.tandfonline.com/dashboard`
3. 展开任何状态为"Out for Review"的稿件卡片
4. 审稿人邀请徽章会自动显示在状态文本旁边

## 兼容性

- ✅ Chrome 配合 Tampermonkey
- ✅ Firefox 配合 Greasemonkey
- ✅ Edge 配合 Tampermonkey
- ✅ 其他支持用户脚本管理器的浏览器

## 许可证

MIT License