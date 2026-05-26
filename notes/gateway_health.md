# 网关健康检查
## 检查命令
openclaw gateway status
curl http://localhost:18789/health

## 预期返回
{
  "status": "healthy",
  "gateway": "running",
  "code": 200
}

## 检查结果
✅ 网关正常运行
✅ 健康检查通过
