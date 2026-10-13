# 谈美 · 视频审美

将朱光潜《谈美》的思想用于视频构思、分镜、生成提示词和审片。让情感通过具体形象、动作、节奏与声音，形成完整意境。

它作为现有视频制作流程的审美层使用，保留创作者指定的风格、用途、时长和预算。快切、鲜艳配色、喜剧、商业片与抽象动画都可以成立。

## 安装到 Codex

把整个仓库放进个人技能目录：

```bash
git clone https://github.com/sixgadss/tanmei-video-aesthetics.git "${CODEX_HOME:-$HOME/.codex}/skills/tanmei-video-aesthetics"
```

若目录已存在，请先检查现有版本，避免覆盖自己的修改。

## 使用

在支持 skills 的 Codex 会话中调用：

```text
用 $tanmei-video-aesthetics 为这支视频设计镜头、声音和节奏，保留我指定的风格。
```

这个 skill 提供审美判断，不自带生成模型，也不授予额外的生成、付费重试或发布权限。

## 文件

- [SKILL.md](SKILL.md)：完整准则、执行方式与具体示例。
- [理论来源](references/theory.md)：原著章节、概念边界与原文入口。
- [Codex 元数据](agents/openai.yaml)：名称和默认调用提示。

镜头与声音方面的建议是对《谈美》的视频应用，不是朱光潜的原话。引用原著时应核对可靠出版版本。
