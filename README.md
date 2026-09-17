# 同于野

[下载最新版本](https://github.com/DongAI-API-transfer-station/tongyuye-harness/releases/latest)

## r5

- 点击模型名称直接展开可切换模型，保留推理等级设置。
- 简化提供方设置：隐藏内置“添加提供方”，自动生成 Provider ID。
- 更新系统提示词、上下文注入、对话及轨迹中的产品显示名称。
- 请求等待状态显示“思考中…”。
- 保留 r4 的盘符根目录新建会话修复。

Release 提供 Windows x64 安装包、供 Apple 芯片 Mac 编译的源码 ZIP 和 SHA-256 校验文件。Mac ZIP 是源码，不是 Mac 安装包。

应用内部版本：0.1.5-rc.2。Windows 为未签名构建。安装更新不会自动删除已有聊天记录或模型配置。

相关回归测试 620 项通过，已在隔离数据下验证 Windows 桌面交互。Mac 编译尚未验证，编译步骤见源码包内的 MAC编译说明.md。
