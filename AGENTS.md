# Agent Instructions

本仓库是 `Business-Unit-for-Energy-Saving` 维护的上游 MyEMS fork，承载能源管理产品代码和业务集成准备工作。

## 规则

- 修改前先读取 `README.md`、`README_CN.md` 以及相关组件文档。
- 需求、场景研究和产品规划放在 `Business-Unit-for-Energy-Saving/requirements`；本仓库只承载代码、产品文档和必要的示例配置。
- 不提交真实凭据、客户隐私、生产参数、内部合同或未经授权的数据。示例数据库和环境文件只能使用占位符，并明确要求部署时设置凭据。
- 上游同步、代码、CI、部署、权限和架构变更使用分支和 PR；简单文档修订可以直接维护 `main`。
- README 中的上游能力、认证、项目数量和支持承诺必须标明来源，不能把上游声明写成本业务单元已核验事实。

## 验证

```bash
git status --short
git diff --check
```
