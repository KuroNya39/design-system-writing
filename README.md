# design-system-writing

面向 UI 的「设计系统」规范写作与维护范式（Claude Code Skill）。

先定 2–3 条设计原则，再建 token 体系（primitive → semantic，语义色一整套）与单一规范源 `design-system.md`；改 UI 只引用 token、不写裸值；附章节骨架与自检清单，要求规范与代码、README 截图始终同步。

## 安装

```bash
# Skill 名 = 目录名 design-system-writing
mkdir -p ~/.claude/skills/design-system-writing
cp SKILL.md ~/.claude/skills/design-system-writing/SKILL.md
```

装好后在对话里输入 `/design-system-writing` 即可调用。

## 适用场景

- 项目还没有设计系统，界面配色 / 间距 / 字号靠手感——建一份 `design-system.md` + 设计 token 当单一依据
- 已有规范，改了 UI / 新增设计 token 后回来同步
- 要改界面前，拿一份「照这个做、别自己发明」的约束，避免风格漂移
- 界面被指出不统一：同样控件两个样、颜色乱、图标混用

## 目录

- `SKILL.md` —— 设计系统写作与维护范式本体（token 方法论、规范章节骨架、行文规则、常见坑、自检清单）
