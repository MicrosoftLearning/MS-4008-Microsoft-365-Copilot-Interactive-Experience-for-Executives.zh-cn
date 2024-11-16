---
title: 联机托管说明
permalink: index.html
layout: home
---

# MS-4008：Microsoft 365 Copilot Interactive Experience for Executives 

## 内容目录

本课程的演示基于加速器工具包“[演示指南和话题.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG)”中的演示。

在提供此培训之前，请务必熟悉演示。 对于多个实验室，将利用示例文档和预先创建的 Teams 会议和电子邮件。

- 请在[此处](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/tree/master/ResourceFiles)预下载所有示例文档。
- 按照[此处](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG)的说明设置 Teams 会议和电子邮件线程。
- 熟悉交互式体验：
    - 选项 1：[aka.ms/CopilotEE](https://aka.ms/CopilotEE)
    - 选项 2：[aka.ms/TeamsEE](https://aka.ms/TeamsEE)

    > **备注：** 如果学员没有 Microsoft 365 Copilot 许可证，他们可以使用在 [aka.ms/CopilotWebEE](https://aka.ms/CopilotWebEE) 上找到的免费商业版的体验。

## 课程描述

了解 Microsoft 365 Copilot 如何提升工作场所的工作效率和创新能力。 这一体验是为现代商业领袖量身定制的，它提供有关为 Copilot 创建情景式提示的见解，并包括引人入胜的用例练习来展示与日常工作流程的无缝集成。

此交付的主要目标是：

- 向参与者介绍 Microsoft 365 Copilot，教他们如何创制有效提示
- 演示 office 应用中的 Microsoft 365 Copilot （最多 3 个演示）
- 引导参与者完成交互式体验
- 邀请参与者下载并尝试 Microsoft Copilot for Mobile

## 课时安排（估计） 

| # | 主题                                 | 总时间      |
|---|---------------------------------------|-----------------|
| 1 | Microsoft 365 Copilot 简介 | 10 分钟    |
| 2 | 制定有效提示的执行指南 | 30 分钟      |
| 3 | Microsoft 365 Copilot Interactive Experience  | 20 分钟      |
|   |                                       | **总时间 60 分钟** |


下面列出了每个演示的超链接。

## 演示

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| 演示 |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
