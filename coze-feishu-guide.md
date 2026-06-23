# coze（扣子）接入飞书操作指南

## 1. 创建飞书应用
1. 打开 [飞书开放平台](https://open.feishu.cn/app)
2. 创建「企业自建应用」→ 名称如「coze 助手」
3. 获取 **App ID** 和 **App Secret**

## 2. 配置应用权限
在飞书开放平台 → 应用 → 权限管理，添加以下权限：
- `im:message`（获取与发送消息）
- `im:message.p2p`（单聊）
- `im:message.group`（群聊，如需群内使用）
- 提交版本并发布

## 3. 在 coze 发布到飞书
1. 打开 https://www.coze.cn → 你的 Bot
2. 右上角「发布」→ 选择「飞书」
3. 填入 App ID / App Secret
4. 发布

## 4. 注意事项
- coze 用独立的飞书应用，不要复用「齐秋露的智能助手」
- coze Bot 会和 Autoclaw/Codex 作为不同的机器人出现在飞书
- 群聊里如果加了 coze Bot，记得遵循群聊规则
