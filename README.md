本仓库是 [DreamLand](https://github.com/Morristin/DreamLand) 的子仓库。
访问该仓库文档以获取关于本配置的更多信息。

## Installation

本仓库包含的内容：

- Obsidian 中的 Editor 设置。包括开启严格换行和关闭括号与 Markdown 语法自动补全。
- Obsidian 中的 Files and Links 设置。包括调整了新笔记和附件的默认存储位置，停用了 WikiLink 语法。 
- Obsidian 中的 Hotkeys 设置。根据 JetBrains 在 Mac 平台的 Keymap 进行了部分设置。 
- CSS Snippet: Invert PDF in dark mode。在暗黑主题下将 PDF 颜色反转以适应主题。

本仓库不包含的内容：

- 任何的主题。
- 任何的第三方插件，包括插件代码、配置或所需额外资源。

### Themes and Third-Party Plugins Recommendations

> [!warning]
> 
> **在运行下方所有代码之前，请先确保你的 Obsidian 开启了 Command-Line Interface**。 
> 
> 如果你需要激活 Command-Line Interface，只需在 Obsidian 中按下 `⌘ + ,` 打开设置，
在 General 中找到 Command Line Interface 选项并将开关打开。你可能需要输入密码来安装相关服务。

本仓库所使用的主题与第三方插件在下方列出。

你可以通过运行下方附属的代码将所有主题或插件统一在 Obsidian 中进行安装（代码不会自动启用这些主题或插件）：

```shell
obsidian theme:install name="Baseline"
obsidian theme:install name="Border"
obsidian theme:install name="Underwater"
obsidian theme:install name="Velocity"
```

```shell
obsidian plugin:install id="animated-cursor"
obsidian plugin:install id="cm-chs-patch"
obsidian plugin:install id="easy-typing-obsidian"
obsidian plugin:install id="fontsource"
obsidian plugin:install id="obsidian-advanced-uri"
obsidian plugin:install id="obsidian-hider"
obsidian plugin:install id="obsidian-icon-folder"
obsidian plugin:install id="obsidian-latex-suite"
obsidian plugin:install id="obsidian-style-settings"
```