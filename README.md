# Attractive Communication Skill | 高吸引力沟通 Skill

> 真正有吸引力的人，不是让别人不得不思考自己，而是让别人愿意思考自己。

一个中文优先、宿主无关的 Agent Skill，将聊天分析、语言留白、幽默、情绪分享和表达训练结合起来。

**核心原则：不是让答案不确定，而是让话题不终结。**

## 功能

- 分析聊天截图或文本，区分事实、推测与未知。
- 推荐一条可以直接发送的回复，按需提供自然型、幽默型、留白型选项。
- 根据日常社交、约会、朋友、职场及事务场景调整表达。
- 解释沟通策略，识别过度解读与强行维持对话。
- 尊重真实、信任、边界和对方的交流意愿。

## 使用方式

下载或克隆本仓库：

```bash
git clone https://github.com/closer11/attractive-communication.git
```

将整个 `attractive-communication` 文件夹放入支持 Agent Skills 的宿主所指定的技能目录，或将 [SKILL.md](SKILL.md) 内容作为自定义指令使用。具体安装位置和启用方式以宿主文档为准。无需 API Key 或额外依赖。

在对话中输入：

> 使用 attractive-communication Skill，分析下面的聊天内容，给我一句自然、有互动感、可以直接发送的回复。

也可以发送聊天截图并请求分析。请注意保护聊天参与者的隐私。

## 示例

对方：你最近怎么这么忙？

推荐：最近在做一件自己挺期待的事，忙得倒也开心。

前提是这符合你的真实情况。没有必要故意制造悬念。

更多示例见 [references/examples.md](references/examples.md)。

## 文件结构

```text
attractive-communication/
├── SKILL.md
├── README.md
└── references/
    └── examples.md
```

版本：1.0.0。公开可阅读；本项目暂未指定开源许可证。兼容性取决于宿主对 Agent Skills 的支持。
