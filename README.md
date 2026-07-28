# Constructivist Paper Sci-Fi

一个可移植的 Codex skill，用于创建统一的“构成主义纸片科幻拼贴”视觉，不限于任何行业或媒介。

适用范围包括海报、编辑插画、封面、活动视觉、叙事场景、界面、信息图、图标及系列化视觉资产。

## 仓库结构

```text
constructivist-paper-sci-fi/
├── README.md
├── MANIFEST.sha256
└── constructivist-paper-sci-fi/
    ├── SKILL.md
    ├── agents/
    │   └── openai.yaml
    └── references/
        ├── prompt-patterns.md
        └── style-guide.md
```

内层的 `constructivist-paper-sci-fi/` 是真正可安装的 skill 文件夹；仓库名称与 skill 名称保持一致。

## 安装

把内层的 `constructivist-paper-sci-fi` 整个文件夹复制到：

```text
<CODEX_HOME>/skills/constructivist-paper-sci-fi/
```

`<CODEX_HOME>` 通常是用户目录下的 `.codex` 文件夹。安装后重新启动 Codex或开启新会话。

Windows PowerShell：

```powershell
Copy-Item -Recurse -LiteralPath '.\constructivist-paper-sci-fi' -Destination "$env:USERPROFILE\.codex\skills\constructivist-paper-sci-fi"
```

macOS / Linux：

```bash
cp -R "./constructivist-paper-sci-fi" "$HOME/.codex/skills/constructivist-paper-sci-fi"
```

## 使用

```text
Use $constructivist-paper-sci-fi to create ...
```

也可以用自然语言提出“构成主义纸片科幻拼贴”“深海军蓝剪纸”“几何复古未来主义”等视觉要求。

## 发布到 GitHub

此目录可以直接作为仓库根目录提交。若希望他人依法复制、修改和再发布，请在公开仓库中添加明确的开源许可证；未添加许可证时，默认版权仍归作者所有。
