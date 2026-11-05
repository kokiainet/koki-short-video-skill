# 短视频创作 Skill

[![English](https://img.shields.io/badge/English-2563EB?style=for-the-badge)](README.md) [![简体中文](https://img.shields.io/badge/简体中文-DC2626?style=for-the-badge)](README.zh-CN.md)

把单人口播剪成竖屏短视频：降噪、精剪、中英文字幕、首帧封面、主题素材与可编辑时间线。

这是从我的日常创作流程整理出的独立 Skill，公开版已做脱敏并支持自定义。技能说明与流程参考提供英文和简体中文版本。

## 能做什么

- 先保守降噪，再精剪口播。
- 清理失败重录与明显重复，保留完整意思和自然表达。
- 英文词组与中文意思组分别处理，不机械套同一种字幕节奏。
- 制作首帧封面、开头标题、主题素材和按配置加入的结尾。
- 实际检查人物、字幕、素材与时间线是否正确。

## 安装与使用

把[本仓库链接](https://github.com/leilei926524-tech/koki-short-video-skill)发给你的 Agent，并说明：

```text
安装本仓库 skills/vertical-talking-head 中的技能。如果已有同名 Skill，先保留并说明冲突位置，不要直接覆盖。
```

也可以下载仓库，把完整的 `skills/vertical-talking-head` 文件夹复制到工具的个人技能目录。需要使用支持 Agent Skills 的工具；剪辑还需要可用的编辑器连接。

```text
用 $vertical-talking-head 剪这段竖屏口播。先降噪精剪，英文按词组、中文按意思组做字幕，加入主题素材，保存可编辑项目。
```

默认加载的 [SKILL.md](skills/vertical-talking-head/SKILL.md) 为英文，同时提供完整的[中文说明](skills/vertical-talking-head/SKILL.zh-CN.md)，流程参考包含中英两种语言。实际输出语言按你的要求。

## 改成自己的风格

将 [creator.example.yaml](creator.example.yaml) 复制为当前项目中的 `creator.local.yaml`，填写自己的称呼、素材目录与偏好。配置供 Agent 读取，不会自行执行或连接账号。未提供的私人素材、结尾图片和 CTA 应跳过或说明，不寻找原作者的素材。隐私处理见 [PRIVACY.md](PRIVACY.md)。

## 工具

主要配合 [ChatCut](https://chatcut.io/docs/web-plugin) 使用，请先在 Agent 环境中连接官方编辑器工具。这里开源的是我的自定义流程，不包含 ChatCut 官方插件及内置技能。默认保存可编辑项目，按明确请求导出或发布；外部服务费用与条款由提供方决定。

## 关于作者与联系

作者：**邓小闲 Koki**，反蒸馏 Skill 作者、社会派编程发起人。

[中文个人网站](https://kokiai.net/zh) · [小红书](https://www.xiaohongshu.com/user/profile/5bfe825044363b01b593585e) · [B站](https://space.bilibili.com/438427470) · [抖音](https://www.douyin.com/user/MS4wLjABAAAAjxdS9GqgpuMLfZGvkM-Kctt6XSkvcr03ouQQv9oNlXHNIC64F4TjKr0cp-dkZcMK)

交流或合作请通过[小红书私信](https://www.xiaohongshu.com/user/profile/5bfe825044363b01b593585e)联系我。技能问题与建议可在本仓库提 issue；请勿在公开 issue 中上传私人素材和账号信息。

## 其他创作 Skill

- [文字创作 Skill](https://github.com/leilei926524-tech/koki-writing-skill)
- [长视频创作 Skill](https://github.com/leilei926524-tech/koki-long-video-skill)

## 开源许可

原创技能说明与适配代码采用 [MIT](LICENSE) 许可。第三方产品、字体、媒体与服务保留各自许可和条款。
