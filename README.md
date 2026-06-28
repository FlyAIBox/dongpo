# 我的好友-苏东坡

苏东坡式生活趣味陪伴 Skill。

## 项目定位

这个仓库用于沉淀「我的好友-苏东坡」Skill。

目标是让 AI Agent 在合适场景下切换到苏东坡式视角，像一个有趣、豁达、会接话的朋友，陪用户聊生活、趣事、烦恼和一点诗词佛法。

第一优先级是生活趣味和朋友感。诗词、佛法和典故只是聊天时自然长出来的风味，不是第一目的。

## 当前状态

当前已实现第一个 Skill：

- `my-friend-su-dongpo`

可以在支持本地 Skill 的 AI Agent 中安装或引用本仓库使用。

## 计划中的 Skill

| Skill | 状态 | 说明 |
| --- | --- | --- |
| `my-friend-su-dongpo` | available | 苏东坡式生活趣味陪伴 Skill |

## 目录结构

```text
.
├── README.md
├── LICENSE
├── .gitignore
├── docs/
│   └── skill-brief.md
└── skills/
    └── my-friend-su-dongpo/
        ├── SKILL.md
        ├── agents/
        │   └── openai.yaml
        └── references/
            ├── persona-distillation.md
            ├── persona-guide.md
            └── source-index.md
```

## 设计方向

- 像朋友，不像客服。
- 有生活趣味，不做诗词百科。
- 有苏东坡气质，但不过度古风。
- 优先接住用户的日常小事、趣事和烦恼。
- 诗词、佛法、典故只在自然合适时出现。
- 不编造苏轼诗句、史实或出处。
- 不替代心理咨询、医疗、法律、财务或宗教指导。

## 安装

如果使用支持 `npx skills` 的环境，可以从仓库安装：

```bash
npx skills add <owner>/<repo>
```

如果在本仓库内开发，可以直接使用：

```text
skills/my-friend-su-dongpo
```

## 后续任务

- 增加更多真实对话测试样例
- 继续压缩和打磨 `SKILL.md`
- 视需要增加 marketplace/plugin 配置
- 视需要从 `skills/my-friend-su-dongpo/references/piece/` 中整理更细的事实索引

## 参考

- [FlyAIBox/baoyu-skills](https://github.com/FlyAIBox/baoyu-skills)
- [alchaincyf/nuwa-skill](https://github.com/alchaincyf/nuwa-skill)
- [ishenwei/openclaw-skills: su-dongpo-perspective](https://github.com/ishenwei/openclaw-skills/tree/main/su-dongpo-perspective)
