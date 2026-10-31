# AircraftEngineerPrompts / 飞机与系统工程角色 Prompt 合集

<p align="center">
  <img alt="AircraftEngineerPrompts" src="https://img.shields.io/badge/Scope-Aircraft%20%26%20Systems%20Engineering-1E90FF?style=for-the-badge" />
  <img alt="Language" src="https://img.shields.io/badge/Language-Chinese%20%2F%20English-00A693?style=for-the-badge" />
  <img alt="Roles" src="https://img.shields.io/badge/Roles-26-FF8C00?style=for-the-badge" />
</p>

A curated collection of role-based prompts for aircraft and systems engineering, designed for AI-assisted analysis, design review, requirement breakdown, safety evaluation, verification planning, and cross-discipline collaboration.

一个面向飞机与系统工程领域的角色化 Prompt 集合，用于 AI 辅助分析、设计评审、需求分解、安全性评估、验证规划与跨专业协同。

## Overview / 项目概览

This repository includes 26 engineering roles covering aircraft-level design, systems integration, requirements, safety, reliability, testing, project management, and ATA-specific subsystem design.

本仓库包含 26 个工程角色，覆盖飞机总体设计、系统工程、接口集成、需求管理、安全性、可靠性、试验验证、项目管理以及 ATA 专项分系统设计等内容。

## Repository Structure / 仓库结构

```text
AircraftEngineerPrompts/
├── LICENSE
├── README.md
├── README_说明与目录.md
├── 文件清单.json
├── Prompts/
│   ├── 01_HVAC高级工程师.txt
│   ├── 02_飞机总体与初步设计工程师.txt
│   ├── ...
│   └── 26_ATA51_57_结构设计与集成工程师.txt
├── skills/
│   ├── 00_通用底线规则.md
│   ├── 01_HVAC高级工程师.md
│   ├── ...
│   └── 26_ATA51_57_结构设计与集成工程师.md
├── skills/README.md
└── .gitignore (if present)
```

## What is included / 包含内容

### Prompt files / 原始 Prompt 文件

`Prompts/` stores the full role-specific TXT prompts ready for direct copy-paste into ChatGPT, Copilot, Claude, or similar AI tools.

`Prompts/` 中保存的是可直接复制到 ChatGPT、Copilot、Claude 等 AI 工具中的完整 TXT Prompt。

### Skill files / 统一 Skill 文件

`skills/` stores the same domain knowledge in a reusable “skill” format, better suited to AI assistants, coding agents, and structured workflows.

`skills/` 中保存的是整理后的“角色 skill”版本，更适合 AI 助手、代码代理和结构化工作流使用。

## Role List / 角色目录

1. HVAC高级工程师 / HVAC Advanced Engineer
2. 飞机总体与初步设计工程师 / Aircraft Concept and Preliminary Design Engineer
3. 运行概念与利益攸关方需求工程师 / Operational Concept and Stakeholder Requirements Engineer
4. 飞机系统综合工程师 / Aircraft Systems Integration Engineer
5. 飞机级系统工程师与架构师 / Aircraft-Level Systems Engineer and Architect
6. 系统工程师与系统负责人 / Systems Engineer and System Responsible
7. 接口与集成工程师 / Interface and Integration Engineer
8. 需求工程师 / Requirements Engineer
9. 安全性评估工程师 / Safety Assessment Engineer
10. 研制保证与DAL分配工程师 / Development Assurance and DAL Allocation Engineer
11. 构型管理工程师 / Configuration Management Engineer
12. 过程保证与质量工程师 / Process Assurance and Quality Engineer
13. 适航与合格审定工程师 / Airworthiness and Certification Engineer
14. 项目与技术管理工程师_项目经理 / Project and Technical Management Engineer_Project Manager
15. 试验与集成验证工程师 / Test and Integration Verification Engineer
16. 可靠性分析工程师 / Reliability Analysis Engineer
17. ATA21_空调与增压系统设计工程师 / ATA21 Environmental Control and Pressurization Design Engineer
18. ATA22_自动飞行系统设计工程师 / ATA22 Flight Control System Design Engineer
19. ATA23_通信系统设计工程师 / ATA23 Communication System Design Engineer
20. ATA24_电源系统设计工程师 / ATA24 Electrical Power System Design Engineer
21. ATA25_设备与装饰系统设计工程师 / ATA25 Equipment and Furnishings Design Engineer
22. ATA26_防火系统设计工程师 / ATA26 Fire Protection System Design Engineer
23. ATA27_飞行操纵系统设计工程师 / ATA27 Flight Controls System Design Engineer
24. ATA31_指示与记录系统设计工程师 / ATA31 Instruments and Recorders Design Engineer
25. ATA61_71_72_螺旋桨与动力装置发动机设计工程师 / ATA61_71_72 Propeller and Powerplant Design Engineer
26. ATA51_57_结构设计与集成工程师 / ATA51_57 Structures Design and Integration Engineer

## Quick Start / 快速开始

### Option A: Use the raw prompt / 方案 A：直接使用原始 Prompt

1. Open `Prompts/`
2. Choose the role you need
3. Copy the TXT content into your AI chat
4. Fill in your actual task and project data

1. 打开 `Prompts/`
2. 选择对应角色文件
3. 复制 TXT 内容到 AI 对话中
4. 填写真实任务与项目资料

### Option B: Use the skill version / 方案 B：使用 Skill 版本

1. Open `skills/`
2. Use the relevant `.md` file as a reusable skill
3. Combine with your specific analysis objective and constraints

1. 打开 `skills/`
2. 使用对应的 `.md` 文件作为可复用 skill
3. 结合具体分析目标、边界和约束使用

## Usage Guidelines / 使用说明

- Use real project data, requirements, standards, and evidence. Do not rely on generic assumptions.
- 真实项目数据、需求、标准和证据必须优先；不要依赖泛化假设。
- Clarify responsibilities, interfaces, approval authority, and verification ownership before multi-role collaboration.
- 多角色协作前，需明确职责边界、接口关系、批准主体和验证责任。
- The prompts are decision-support tools, not legal, certification, or design approval authority.
- 本仓库中的 Prompt 仅用于结构化分析与协同辅助，不构成法律、认证或设计批准权限。

## Important Notes / 重要说明

This project does not replace official engineering standards, certification processes, or technical approval authority. It is intended to structure reasoning, accelerate analysis, and better support AI-assisted system engineering work.

本项目不替代正式工程标准、适航认证流程或技术批准权限。它的目的是结构化工程思考、加速分析和提升 AI 辅助系统工程工作的表达质量与协同效率。

## Related Files / 相关文件

- `README_说明与目录.md` — Chinese orientation and index
- `README_说明与目录.md` — 中文说明与目录入口
- `skills/README.md` — skill overview and directory
- `skills/README.md` — skill 版本说明与目录
- `Prompts/` — complete prompt texts
- `Prompts/` — 原始 Prompt 文件目录
- `skills/` — reusable skill versions
- `skills/` — 可复用 skill 目录

## License / 许可证

This project is licensed under the MIT License. See `LICENSE` for details.

本项目采用 MIT License，详细内容见 `LICENSE` 文件。

## Contact / 联系方式

This repository is intended for engineering knowledge organization and AI-assisted workflow support.

本仓库用于工程知识整理与 AI 辅助工作流支持。

If you want, I can also prepare a more polished English version or a more compact GitHub homepage version.

如果你愿意，我还可以继续为这个仓库准备更正式的英文版说明，或者做成更适合 GitHub 首页展示的精简版 README。
