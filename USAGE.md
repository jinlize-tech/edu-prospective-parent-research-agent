# 使用说明

## 适用任务

计划进入初中数学辅导市场，访谈10位家长后发现“效果焦虑”之外还有接送时间和班型稳定性的高权重。

## 准备输入

研究问题、目标人群、地区、样本条件、访谈记录/摘要、竞品与替代方案、机构当前课程。使用前先脱敏姓名、联系方式和与任务无关的敏感信息。

## 操作步骤

1. 定义研究问题
2. 设计筛选与提纲
3. 逐访谈编码
4. 形成主题和反例
5. 对齐决策阶段
6. 输出机会和验证计划

## 校验命令

```powershell
node scripts/validate_input.js examples/typical_input.json
node scripts/validate_output.js examples/typical_output.json
```

## 状态使用

- `completed`：核心成果完整。
- `completed_with_limits`：只完成可验证部分，并说明受阻范围。
- `needs_input`：缺少关键输入。
- `needs_confirmation`：资料冲突或需人工确认。
- `failed`：工具或计算失败，提供恢复动作。

## 人工确认

业务负责人复核输入事实、关键假设和最终成果适用范围后，成果才可进入正式业务使用。
