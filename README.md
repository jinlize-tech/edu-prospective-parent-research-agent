# 潜在家长访谈研究

设计访谈指南、执行多轮结构化归纳，区分家长原话、研究者推断和待验证假设，形成购买阻力与信息需求。

## 适用用户

校长、市场负责人、课程产品经理、招生主管

## 主要输出

- 访谈方案
- 访谈指南
- 编码表
- 主题报告
- 购买阻力
- 信息需求
- 反证
- 下一步研究

## 安装

将Agent目录按平台要求导入，并保留`.codebuddy-plugin/plugin.json`、`agents/`、`skills/`与`avatars/`的相对结构。

本地验证：

```powershell
node scripts/validate_input.js examples/typical_input.json
node scripts/validate_output.js examples/typical_output.json
```

## 使用

1. 阅读`USAGE.md`。
2. 按`contract/input.schema.json`准备输入。
3. 调用产品或Agent完成专业处理。
4. 使用`scripts/validate_output.js`检查成果。
5. 高风险结论交由业务负责人确认。

## 边界

- 不使用外部收费API。
- 不依赖其他产品完成核心任务。
- 不自动执行正式审批、退款、人员处罚或系统变更。
- 客户可见内容不包含公司品牌推广或内部研发资料。

## 状态

- 版本：`1.0.0`
- 本地契约与自动化测试：见`test-results/`
- 生成式模型运行：`MODEL_RUNTIME_NOT_VERIFIED`
- WorkBuddy安装、调用、审核、上架：`NOT_EXECUTED`
- 安装包：`dist/edu-prospective-parent-research-agent-v1.0.0.zip`

## 许可证

Apache-2.0。详见`LICENSE`。
