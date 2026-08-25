# V0.19.0 Restored

<div align="center">
  <img src="https://raw.githubusercontent.com/tw93/Kaku/main/assets/logo.png" alt="Kaku Logo" width="120" height="120" />
  <h1 style="margin: 12px 0 6px;">Kaku V0.19.0</h1>
  <p><em>A fast, out-of-the-box terminal built for AI coding.</em></p>
</div>

### Changelog

1. **Pane Input Broadcast Is Gone**: Typing in one pane no longer echoes into the others, a fan-out that was too easy to trigger by accident and could repeat a risky command somewhere you were not looking, and the old key assignments now load as no-ops.
2. **Sessions Come Back Intact**: Reopening Kaku restores your windows, their panes, and the directory each pane was in, and one pane that fails to save no longer takes the rest down with it.
3. **Closing Hits What You Picked**: A close confirmation stays tied to the pane you opened it from, and closing the active tab leaves you on the one you expected.
4. **Display and Integration Fixes**: Selected text stays visible in the light theme, lazygit opens correctly inside nested shells, clearing history no longer disturbs a full-screen program, renaming a tab does not freeze its title, and slow synchronized output stops tearing.

### 更新日志

1. **移除分屏输入广播**：往一个分屏里打字不会再同步到其他分屏，这个功能太容易误触，一不小心就把有风险的命令在你没看着的地方重复一遍，原来的快捷键还在，按了不会有反应。
2. **重开还是原来的样子**：重新打开 Kaku，窗口、分屏和每个分屏当时所在的目录都会回来，个别分屏没能存下来也不会连累其他的。
3. **关掉的是你选的那个**：确认框对应的始终是你点开它的那个分屏，关掉当前标签页之后也会停在你预期的那一个。
4. **显示与集成修复**：浅色主题下选中的内容不再看不见，lazygit 在嵌套 shell 里能正常打开，清空历史输出不会再打断全屏程序，重命名标签页不会卡住标题，慢速的同步输出也不再撕裂。

Special thanks to @shlroland and @dufu1991 for their contributions to this release.

> https://github.com/tw93/Kaku
