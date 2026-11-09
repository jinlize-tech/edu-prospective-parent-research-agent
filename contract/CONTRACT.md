# 输入输出契约

## 输入字段

| 键 | 名称 | 类型 | 必填 |
|---|---|---|---|
| `research_questions` | 研究问题 | array | 是 |
| `target_parent_segments` | 目标家长分群 | array | 是 |
| `region` | 研究地区 | string | 是 |
| `sample_criteria` | 样本标准 | string | 是 |
| `interview_notes` | 访谈记录或摘要 | array | 是 |
| `competitor_context` | 竞品与替代方案 | array | 否 |
| `institution_courses` | 机构课程信息 | array | 是 |

## 状态

- `completed`：核心成果完整，关键结论人工确认要求满足。
- `completed_with_limits`：至少一项实质成果，说明限制、已完成和受阻范围。
- `needs_input`：必填字段缺失。
- `needs_confirmation`：资料冲突或人工确认未完成。
- `failed`：计算或工具失败。

## 输出

- `访谈方案`：结构化条目数组，不允许空壳或占位文本。
- `访谈指南`：结构化条目数组，不允许空壳或占位文本。
- `编码表`：结构化条目数组，不允许空壳或占位文本。
- `主题报告`：结构化条目数组，不允许空壳或占位文本。
- `购买阻力`：结构化条目数组，不允许空壳或占位文本。
- `信息需求`：结构化条目数组，不允许空壳或占位文本。
- `反证`：结构化条目数组，不允许空壳或占位文本。
- `下一步研究`：结构化条目数组，不允许空壳或占位文本。

完整机器契约见`contract/input.schema.json`、`contract/output.schema.json`和`contract/runtime_contract.json`。
