# Chrome Tab Groups

Chrome-style tab management for Obsidian (desktop only). The interface is in Chinese.

## Features

- **Tab groups**: add tabs to a named, colored group. The group chip sits on the left of the group's first tab.
  - Click the chip to collapse / expand the group; right-click it to rename, recolor, add a new tab to the group, ungroup, close the group, or move the group to a new window.
  - Drag the chip to move the whole group anywhere in the same window's tab bars.
- **Chrome rules**: a group lives in one tab bar and its tabs always stay together. Dragging a tab out of the group, or into another pane / window, removes it from the group; dropping it in the middle of a group adds it.
  - "New tab to the right", duplicated tabs and links opened in a new tab (⌘-click) join the current group. ⌘T and the "+" button do not.
  - Collapsing the group you are looking at switches to the nearest tab outside it (or opens a new one); switching back to a collapsed tab expands the group.
- **Tab context menu**: New tab to the right, Add tab to new split view (always to the right, max 3 columns), Add tab to (new) group, Remove from group, Duplicate tab.
- **Tab search**: fuzzy-search all open tabs and jump to one.
- **Commands** (no default hotkeys; assign your own in Settings → Hotkeys): add to new group, remove from group, collapse / expand group, edit group, close group, search tabs, new tab to the right, duplicate tab, add tab to new split view, pin tab and move it to the far left.

Groups are saved by tab id in the plugin's `data.json` and restored after restart.

## Installation

Search for **Chrome Tab Groups** in Settings → Community plugins, or copy `main.js`, `manifest.json` and `styles.css` from the latest release into `<vault>/.obsidian/plugins/chrome-tab-groups/`.

## Feedback and updates

To follow new features, send feedback or keep up with progress, follow me on Twitter: [@Matsurimywaifu](https://x.com/Matsurimywaifu).
---

# Chrome Tab Groups（中文）

仿 Chrome 的标签页管理（仅桌面端）。

- **标签页分组**：给组命名、选颜色；色块嵌在组内第一个标签页左侧。点色块折叠 / 展开，右键色块编辑（名称、颜色、在组中新建、取消组合、关闭组、移至新窗口），拖色块把整组挪到别处。
- **照 Chrome 的规则**：一个组只在一个标签栏里，组内标签页始终挨在一起；拖出组外 / 拖到别的分屏或窗口就退组，拖进组的中间就进组。「在右侧新建」、复制标签页、⌘点击链接在新标签页打开都进同一组；⌘T 和「＋」新建的不进组。
- **右键菜单**：在右侧新建标签页、向新拆分视图添加标签页（固定向右，最多 3 栏）、将标签页添加到（新）组、从组中移除、复制标签页。
- **搜索标签页**。
- 所有操作都有命令，不带默认快捷键，在「设置 → 快捷键」里自己绑。

分组按标签页 id 存在 `data.json` 里，重启后恢复。

## 反馈与后续

想追踪后续功能、反馈问题、关注后续进展，欢迎关注我的 Twitter：[@Matsurimywaifu](https://x.com/Matsurimywaifu)。
