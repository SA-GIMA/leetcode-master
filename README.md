# LeetCode Master Skill Project

这是一个为 Gemini CLI (OpenClaw) 设计的自定义 Skill，专注于 LeetCode 热题 100 的学习与原创题目生成。

## 文件夹内容
- **SKILL.md**: Skill 的核心逻辑和触发规则。
- **references/hot100.md**: 预置的 LeetCode 热题 100 题目列表及其核心考点总结。

## 功能特性
1. **考点速查**：自动关联热题 100 的核心算法，总结面试考点。
2. **原创题生成**：通过交互式询问（难度、类型、场景），为您定制原创的 LeetCode 风格算法题。

## 安装与使用
在 OpenClaw (Gemini CLI) 中，您可以直接通过安装文件夹来启用它：

1. 执行安装命令：
   ```bash
   gemini skills install /Users/sagima/Desktop/leetcode-master --scope workspace
   ```
2. 重新加载：
   `/skills reload`
