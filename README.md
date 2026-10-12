# 微信 AI 技能工厂

面向微信 Agent 生态的可复用技能库，交付底座为腾讯云 CloudBase。

## 目录规划
- `miniprogram/`  工具小程序前端（首个工具：证件照 / 文档处理，待定）
- `cloudfunctions/`  CloudBase 云函数（预约、下单、查询、文档处理、支付回调、多租户）
- `skills/`  Agent 技能说明文档（WorkBuddy / SkillHub 发布用）
- `docs/`  产品方案与接入说明

## 环境
- CloudBase 环境别名：saikebo（ap-shanghai）
- 密钥、AppSecret 一律不入库，使用环境变量
