# agent-handbook
agent-handbook

用于长期维护个人 AI 指令资产：保存可直接复制的 Prompt、可复用的 Skill、项目级指令模板，以及使用记录与维护说明。

## 目录与导航

| 目录 | 用途 | 已有内容 |
| --- | --- | --- |
| [prompts](prompts/README.md) | 围绕具体任务、可复制到对话中的指令 | [引导式代码学习](prompts/learning/guided-code-learning.md) |
| [skills](skills/README.md) | 可重复执行的工作流程及配套资源 | 收录约定，暂未收录 Skill |
| [templates](templates/README.md) | 供其他项目采用的项目级指令模板 | [AGENTS.md](templates/agents/general/AGENTS.md)、[CLAUDE.md](templates/claude/general/CLAUDE.md) |
| [examples](examples/README.md) | 脱敏后的实际使用记录 | 记录约定，暂未收录使用案例 |
| docs | 编写和维护说明 | [命名约定](docs/naming-conventions.md)、[编写指南](docs/authoring-guide.md) |

[根目录 AGENTS.md](AGENTS.md) 指导 AI 维护本仓库。templates 下的文件是待复制的资产，不是本仓库的全局规则。

## 如何使用

1. 单次对话任务选择 Prompt；重复流程选择 Skill；整个项目持续适用的约定选择项目级指令模板。
2. 阅读资产的适用场景与边界。复制 Prompt 中的指令正文，或将模板复制到目标项目所需的位置。
3. 将所有 `{{占位符}}` 替换为真实且可分享的信息，删除不适用项；命令须在目标项目中核实后填写。
4. 不同工具对指令文件的名称、发现位置、作用范围和 Skill 结构支持可能不同，使用前查看目标工具的对应说明。
5. 通过实际使用检查结果，将必要调整和观察记录到 examples，再据此改进原资产。维护方式见[编写指南](docs/authoring-guide.md)。

请勿写入真实密钥、私人信息或个人绝对路径。当前未添加 LICENSE，许可方式由仓库维护者后续决定；公开可见不代表已授予开源许可。
