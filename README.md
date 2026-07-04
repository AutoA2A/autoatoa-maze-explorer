<p align="center"><a href="https://www.autoa2a.org"><img src="https://agent.oagi.com.cn/uploads/202606/29ea3ed5413830b3.png" alt="AutoA2A" height="110"></a></p>

# 迷宫探索工具

> 本项目由 [www.autoa2a.org](https://www.autoa2a.org) 「AI 研究院」**多个 AI 协作自动生成**（共 5 个页面）。在线访问： https://AutoA2A.github.io/autoatoa-maze-explorer/

# 迷宫探索工具 项目说明

## 网站简介
迷宫探索工具是一个纯前端的交互式平台，用于生成、可视化和求解迷宫。用户可调整迷宫规格、墙体密度，点击“一键生成”得到随机迷宫，随后使用方向键或鼠标拖动角色进行探索。内置深度优先、广度优先和 A* 三种寻路算法，实时高亮最优路径，帮助用户直观理解算法工作过程。该工具完全基于浏览器运行，无需任何后端服务，适合教学演示和个人学习。

## 页面与功能
1. 首页（index.html）：展示项目标题、简短介绍和快速入口按钮，跳转至生成页面。  
2. 生成页面（generate.html）：提供迷宫尺寸、墙体密度滑块、“一键生成”按钮，生成后显示迷宫网格。  
3. 探索页面（explore.html）：载入生成的迷宫，支持方向键或鼠标拖动角色移动，实时计步并显示当前位置。  
4. 算法页面（algorithm.html）：选择深度优先、广度优先或 A* 算法，点击“求解”即可看到步骤动画和最终最优路径高亮。  
5. 关于页面（about.html）：介绍项目背景、技术栈（HTML5、CSS3、原生 JavaScript）以及贡献者列表。

## 多 AI 协作与验收
本项目由三位 AI 模型协作完成：负责需求分析与页面结构设计的 AI-A，负责交互逻辑与算法实现的 AI-B，负责样式美化与响应式布局的 AI-C。每完成一个模块后，由另一位 AI 进行代码审查，检查语法错误、可访问性及性能瓶颈，确保所有功能在主流浏览器中均能正常运行。最终验收通过统一的检查清单，包括功能完整性、代码可读性和用户体验三项指标。所有提交均通过自动化 CI 流程运行单元测试，确保无回归。

## GitHub Pages 部署与访问(入口 index.html)
将仓库推送至 GitHub 后，在 Settings → Pages 中选择 main 分支的 /（根）文件夹作为来源，保存后 GitHub 会自动部署。部署完成后，访问 https://<用户名>.github.io/<仓库名>/ 即可看到首页 index.html，从此进入迷宫探索工具的全部功能。

---

## 关于 AutoA2A

✅️AutoA2A是智能体互连 Agent to Agent平台，实现智能体间的无缝发现、协商、协作与数据安全交换，让您的智能体从信息孤岛走向高效协同，重塑数字化生产力。赋能多智能体生态发展自动化与AI协作,开启AI即服务新时代。

官网： [www.autoa2a.org](https://www.autoa2a.org)

Copyright © 2025 - 2026 AutoA2A. All Rights Reserved. A2A版权所有
