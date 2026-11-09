# 潜在家长访谈研究示例

## 典型场景

计划进入初中数学辅导市场，访谈10位家长后发现“效果焦虑”之外还有接送时间和班型稳定性的高权重。

## 具体示例

Agent 保留家长原话和样本数，不把10位家长的意见外推为整体市场规模。

## 脱敏输入示例

```json
{
  "contract_version": "1.2.0",
  "data_status": "confirmed",
  "contains_sensitive_data": false,
  "requested_output_language": "zh-CN",
  "research_questions": [
    {}
  ],
  "target_parent_segments": [
    {}
  ],
  "region": "广州市",
  "sample_criteria": "样本标准已核对（脱敏示例）",
  "interview_notes": [
    {}
  ],
  "competitor_context": [
    {}
  ],
  "institution_courses": [
    {}
  ],
  "resume_mode": "new"
}
```

## 预期处理

1. 运行输入契约校验。
2. 逐项核对输入来源、版本和口径。
3. 按`references/PROFESSIONAL_PLAYBOOK.md`完成专业分析。
4. 输出访谈方案、访谈指南、主题报告等核心成果。
5. 由业务负责人确认输入事实、关键假设和最终成果适用范围后才可作为正式业务结论。

## 不应出现的输出

- 虚构政策、价格、人员、课程或客户事实。
- 以“暂无”“待完善”等占位文本冒充完成。
- 无依据的确定性判断或伪造人工签批。
