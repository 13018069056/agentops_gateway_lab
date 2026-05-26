# 云端智能体配置（脱敏）
## 用途
定义模型提供商与Agent映射
## 位置
D:\agentops-exp4\config\agents.json

{
  "_comment": "云端模型路由配置，密钥从环境变量读取",
  "provider": "redacted-provider",
  "model": "redacted-model",
  "enabled": true
}

## 预期效果
Agent可路由到云端模型，不暴露密钥
