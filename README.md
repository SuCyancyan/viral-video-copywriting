# 短视频爆款文案生产线

> 四步流水线，从拆解到出品一条爆款文案

## 流程

```
用户输入爆款Excel → [1 拆解大纲] → 结构化拆解
                                      ↓
      用户可选附件 ──→ [2 写大纲] → 3套大纲方案
                                      ↓
      爆款标题库 ──→ [3 写稿] → 完整文案（含来源标注）
                                      ↓
                   [4 改稿验证] → 修改建议 → 用户定稿 ✅
```

## 子能力

| # | 能力 | 说明 | 详细规范 |
|---|------|------|---------|
| 1 | 拆解大纲 | 逐句拆解爆款文案，提取骨架结构 | [skill1-deconstruct.md](references/skill1-deconstruct.md) |
| 2 | 写大纲 | 基于拆解结果生成3套差异化大纲 | [skill2-outline.md](references/skill2-outline.md) |
| 3 | 写稿 | 大纲扩充为完整文案，强制标注来源 | [skill3-draft.md](references/skill3-draft.md) |
| 4 | 改稿验证 | 逐条核查数据和案例真实性 | [skill4-verify.md](references/skill4-verify.md) |

## 使用方式

此 Skill 为 [Hermes Agent](https://hermes-agent.nousresearch.com/) 设计，放入 `~/.hermes/skills/` 目录即可自动加载。

## License

MIT
