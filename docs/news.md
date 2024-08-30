# 前沿快讯

## 2024.08.31 论坛机器人复活

## GitHub Models

[GitHub Models 申请网址](https://github.com/marketplace/models/waitlist/join)

### 普通使用

1. "个人访问令牌" [申请](https://github.com/settings/tokens)，获取一个 token，无需授予令牌任何权限
2. API 域名：https://models.inference.ai.azure.com
2. API 路径：/chat/completions


## 接入 One-API

1. 自定义渠道
2. 渠道地址 https://models.inference.ai.azure.com
3. 密钥: `<your-github-token>`
4. 自定义参数 ChatCompletions 地址填写：/chat/completions

<!-- ### Curl 示例

```bash
curl --location --request POST 'https://models.inference.ai.azure.com/chat/completions' \
--header 'Authorization: Bearer {github_token}' \
--header 'Content-Type: application/json' \
--data-raw '{
  "model": "gpt-4o-mini",
  "stream": false,
  "messages": [
    {
      "role": "user",
      "content": "你是谁？"
    }
  ]
}'
``` -->