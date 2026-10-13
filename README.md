# Skill 二创工作台

处理 Skill 雷达导出的创作任务包，依据原作快照和个人目标完成 Skill 或 Prompt 二创、检查并打包结果，用于导回原创作项目。用户只想搜索或收藏资源时不使用。

`skill-remix-workbench` · 原创 Skill · 内容版本 `3fb1252b713d`

## 适用场景

处理 Skill 雷达导出的创作任务包，依据原作快照和个人目标完成 Skill 或 Prompt 二创、检查并打包结果，用于导回原创作项目。用户只想搜索或收藏资源时不使用。

## 安装与使用

```sh
git clone https://github.com/shuaige619/skill-remix-workbench.git
cd skill-remix-workbench
```

将此目录按宿主支持的方式登记为本地 Skill，或把 [SKILL.md](SKILL.md) 交给支持 Agent Skills 的助手读取。保留 `scripts/`、`references/` 等配套目录的相对位置；下载完成不代表宿主已加载。

需要能读取本地 Markdown 的 Agent 环境。其他工具与依赖以 SKILL.md 中的要求为准。

## 输入与输出

**输入：** 按 SKILL.md 提供任务材料、必要参数和明确的输出位置。

**输出：** 按 SKILL.md 的交付约定生成结果，并报告未完成或待确认的项目。

## 使用示例

```text
请使用 skill-remix-workbench 处理我提供的材料。先核对必要输入，再按 SKILL.md 执行并回读实际输出。
```

以上是调用示例，不是已完成业务运行的记录。

## 工作方式

- 准备
- 二创
- 检查与打包



## 验证与限制

本发布步骤核对文件结构、README、上传前后文件摘要；未在本步骤重新执行业务效果验证。

模型输出与业务事实需要结合具体材料核对；结构和上传检查不能替代业务效果测试。

## 来源与二创说明

由作者围绕本任务设计，发布包保留当前 Skill 与配套文件。

文件身份与发布标准版本记录在 [发布清单](skill-release.json) 中。问题反馈请附复现输入、期望结果及内容版本，并先移除私人数据。

## 许可证

以仓库随附的 LICENSE / NOTICE 为准；未附许可证的部分尚未授予额外使用许可，请联系作者。
