# 逐浪队 · 2026 OceanBase 数据库大赛

## 项目来源

本仓库从 [OceanBase 官方 PowerContext](https://github.com/oceanbase/powercontext) Fork，完整保留上游源码和 Apache-2.0 许可证。
起始提交：`e4efb39bd6b8303a508c83fd5fcde5f99290b785`。
当前是参赛开发起点，尚未加入赛题解答，也没有通过大赛在线评测。

## 报名与提测

- [赛事官网](https://open.oceanbase.com/competition)：报名截止时间为 2026 年 10 月 26 日。
- PowerContext 赛题仓库地址：`https://github.com/z3275630-ops/zhulang-powercontext`。
- 官网允许每队 1–3 人，并允许使用 AI Coding。
- 官网围绕 seekdb、PowerContext 及 AI 生态设置赛题；具体任务、基准分支、评测入口、提交方式，以本届官方完整赛题为准。
- 报名表允许在报名截止前修改仓库地址。报名提交不代表作品通过评测。

## 开发方式

先阅读 [中文说明](README_CN.md)、[贡献指南](CONTRIBUTING.md) 和 [仓库规则](AGENTS.md)，再按赛题修改相关模块。
优先在官方实现上做必要修改，保留公开接口与许可证，避免重写与赛题无关的应用。

上游使用 Python 3.11+、uv 和 Hatchling。常规检查入口为：

```text
make install
make check
make test
```

Windows 支持仍属 experimental；以上命令是上游开发入口，不代表本机已经执行通过。需要 Linux/macOS 专属后端时，再根据正式赛题决定构建环境。

## 验收要求

1. 获取本届完整赛题，核对指定源码分支、必做题和计分方式。
2. 按上游公开接口验证源码可安装、核心流程可运行。
3. 每个赛题变更运行对应行为测试；涉及实际模型或数据库时，记录真实运行结果。
4. 在官方提测平台提交并保存真实反馈，区分本地测试与在线分数。

本仓库不保存学生证、身份证号码、联系方式、报名截图或 API 密钥。
