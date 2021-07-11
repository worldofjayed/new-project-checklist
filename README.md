# New Project Checklist


 - [English](#english)
 - [中文（Chinese）](#中文chinese)

Online Tools: https://phodal.github.io/new-project-checklist/

## English

Focus on four dimensions:

 - [ ] Process, focusing on processes from permissions management, code acquisition, deployment, and code integration.
 - [ ] People, connecting stakeholders, third-party partners (out-of-organization), collaborative teams (within the organization), team members, and more.
 - [ ] Tech, including technical vision, documentation (documents), project code, technology stack, software library management, etc.
 - [ ] Business, covering the requirements of business features such as business vision, business needs, and cross-functional requirements.

### Tech

**0. Technology Vision**

Description: In terms of technology, what are we pursuing?

**1.Documentation**

 - [ ] Path to Production
 - [ ] golive and release diary
 - [ ] other wikis and documentation
 - [ ] Development specification

Description: a good documentation should be versionable.

**2.Architecture**

 - [ ] system architecture diagram, such as C4Model mode
 - [ ] existing technology stacks and their relationships

**3.Code base**

 - [ ] setup guide.Which is ``README``
 - [ ] architecture decision record. in ``docs/ard`` directory.
 - [ ] editor configuration and code style specification
 - [ ] mode and style guide
 - [ ] version manager branch pattern. GitFlow or Feature Branch of Master Flow.
 - [ ] commit message style. open source library style or business style

**4.Security**

 - [ ] test strategy.test layered, test pyramid.
 - [ ] test automation. 

**5.Project Evolution**

 - [ ] Technical risk.Need to spike before project start.
 - [ ] future technology stack
 - [ ] system evolution plan

**6. Security**

 - [ ] security standard. Is safety more important, or is the experience more important?
 - [ ] data encrypt in the code.
 - [ ] code security.

**7. Quality**

 - [ ] project quality tracking.
 - [ ] visualization of code quality.
 - [ ] quality strategy.

### Process

**0. Project Process**

 - [ ] Project's Roadmap? Such as project deadline, milestone, plan (with interation plan).
 - [ ] features's lifecycle. Such as Story card workflow in agile
 - [ ] How to communicate? Such as IM, Email and agile daily standup, remote meeting, Retro, etc.

**1.Path to Development**

 - [ ] development machine and network permission preparation and so on
 - [ ] code repositroy permission management
 - [ ] editor and related tool application setup

Note: different organizations have their own special situations, such as the opening of PC ports, network permissions, codebase permissions, etc., which require a certain process.

**2.Path to Production**

 - [ ] the process of golive's every step
 - [ ] related key people
 - [ ] the tools needed for each step
 - [ ] the process required for each step. such as quality assurance people & process, and golive process

Note: Path to Production in the code is just a description - [ ] for developers, and here's a more detailed explanation.

**3.Path to Roll Off**
 
Note: What do you need when you change a project?

### People

**1.Teammate**

 - [ ] Who are you looking for each problem? 
 - [ ] Team members' technical stack and level
 - [ ] How to bring everyone's skill level: Coach, Pairing, Teach
 - [ ] Project-independent technology, who can find "entertainment" together?
 - [ ] 1 to 1 Meetings

**2.Stakeholders**

 - [ ] Learn about each stakeholder (Level 1). As a developer, most of the time there is no direct communication with stakeholders.
 - [ ] Stay in communication with the stakeholders (Level 2). Proper communication can help the project to work better.

**3.Cross-team collaboration**

 - [ ] What are the relevant partners and who are the respective interfaces?
 - [ ] Team in same project or organizations.

**4.Users**

 - [ ] Who is the user? Are we in direct contact with them?
 - [ ] Feedback loop. How does a user's feedback become requirements?

### Domain

**0.Business Vision**

Explanation: What are we doing, where are we going?

**1.Business**

 - [ ] Is there a list of requirements that are close to full? At a certain time (such as iterations), the demand should be stable.
 - [ ] How does demand go from verbal to to-do list? Is there an irregular problem in the middle?
 - [ ] How is the business changed?

**2.Cross-functional requirements**
 
 - [ ] Operational quality. Quality observed during system operation, such as security and ease of use
 - [ ] Evolution quality. Software system structure and quality related to the development process, such as software testability, maintainability, scalability, etc.

## 中文（Chinese）

关注于四个维度：

 - [ ] Process，关注于从权限管理、获取代码、部署上线、代码集成等的流程。
 - [ ] People，连接利益相关者、第三方合作伙伴（组织外）、协作团队（组织内）、团队成员等相关的人。
 - [ ] Tech，包含了技术远景、文档（文档即代码）、项目代码、技术栈、软件库管理等。
 - [ ] Business，涵盖了业务远景、业务需求、跨功能需求等业务相关功能的需求。

### Tech

**0. 技术远景**

说明：在技术上，我们有什么追求？

**1. 文档**
 - [ ] Path to Production
 - [ ] 上线及发布日记
 - [ ] 项目相关的 wiki 和文档记录
 - [ ] 开发规范

说明：文档即代码——好的文档应该是版本管理的。

**2. 架构**
  - [ ] 系统相关的架构图，如 C4Model 方式描述
  - [ ] 现有的技术栈及其关系

**3. 代码库**
 - [ ] 搭建指南。即 ``README``
 - [ ] 架构决策记录。放置在代码库的 ``docs/adr`` 目录中。
 - [ ] 编辑器配置和代码风格规范。
 - [ ] 模式和风格指南。
 - [ ] 分支管理模式。GitFlow 或者 master，或者 Feature Branch。
 - [ ] 代码提交风格。业务风格或者是开源软件风格？

**4. 测试**
 - [ ] 测试策略。测试层级, 测试金字塔。
 - [ ] 自动化测试。

**5. 项目演进**
 - [ ] 技术风险点。即需要提前 spike 调研的内容
 - [ ] 未来的技术栈
 - [ ] 系统的演进方案

**6. 安全**
 - [ ] 安全标准。安全更重要，还是体验更重要？
 - [ ] 代码中的数据加密。
 - [ ] 代码安全。

**7. 质量**
 - [ ] 项目质量跟踪。
 - [ ] 代码质量可视化。
 - [ ] 应用质量策略。

### Process

**0. Project Process**

 - [ ] 项目的 Roadmap？项目 Deadline，关键时间节点，项目规划等。
 - [ ] 项目功能的生命周期。如敏捷中的故事卡工作流
 - [ ] 沟通方式？如 IM，邮件，还有敏捷的每日站会，远程会议，Retro 等

**1. Path to Development**

 - [ ] 开发机申请及网络等权限准备
 - [ ] 代码库权限管理
 - [ ] 编辑器和相关的工具申请

说明：不同的的组织包含自身特别的情况，如 PC 端口、网络权限、代码库权限等的开通都需要一定的流程。

**2. Path to Production**

 - [ ] 上线每一步的流程
 - [ ] 相关的关键人
 - [ ] 每一步所需要的工具
 - [ ] 每一步所需要的流程。如 QA 测试流程，上线流程

说明：代码中的 Path to Production 只是一份说明——针对于开发人员的，而这里的则需要一个更详细的说明。

**3. Path to Roll Off**
 
说明：换一个项目时，需要哪些东西？

### People

**1. 团队成员**

 - [ ] 非技术问题找谁？
 - [ ] 团队成员的技术栈及水平
 - [ ] 每个人的技术水平，应该怎么带：Coach（教练式）, Pairing（结对式）, Teach（教学式）
 - [ ] 项目无关的技术，可以找谁一起“娱乐”？
 - [ ] 1 to 1 Meetings

**2. 利益相关者**

 - [ ] 了解各个相关者（Level 1）。如作为一个开发人员，大部分时间并不会和利益相关者有直接的沟通。
 - [ ] 和相关者保持沟通（Level 2）。适当沟通，可以帮助项目更好地进行。

**3. 跨团队协作**

 - [ ] 相关的合作方有哪些，各自的接口人是谁？
 - [ ] 同组织、项目下的其它团队。

**4. 用户**

 - [ ] 用户是谁？我们是否与他们直接接触？
 - [ ] 反馈环。一个用户的反馈是如何变成需求的？

### Business

**0. 业务远景**

说明：我们在做什么，我们要去哪里？

**1. 业务需求**

 - [ ] 有没有接近全的需求列表。在一定的时间（如迭代内），需求应该是稳定的。
 - [ ] 需求是如何从口头到待办列表的？中间是不是存在不规范的问题
 - [ ] 业务是如何进行变更的？

**2. 跨功能需求**

 - [ ] 运行质量。在系统运作时观察到的质量，例如保安性及易用性等
 - [ ] 演进质量。软件系统结构及开发过程有关的质量，例如软件可测试性、可维护性、可扩展性、可伸缩性（scalability）等

License
---

Web based on [https://github.com/thedaviddias/Front-End-Checklist](https://github.com/thedaviddias/Front-End-Checklist) See `web/LICENSE` in this directory.

[![Phodal's Idea](http://brand.phodal.com/shields/idea-small.svg)](http://ideas.phodal.com/)

© 2019 A [Phodal Huang](https://www.phodal.com)'s [Idea](http://github.com/phodal/ideas).  This code is distributed under the MIT license. See `LICENSE` in this directory.
