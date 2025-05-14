# 公司内部知识库主索引

**最后更新时间:** 2025-04-20

## 目录 (Table of Contents)

* [1. 引言与导览 (Introduction & Navigation)](#1-引言与导览-introduction--navigation)
* [2. 新人入门指南 (Onboarding Guide)](#2-新人入门指南-onboarding-guide)
* [3. 项目概览 (Projects Overview)](#3-项目概览-projects-overview)
    * [3.1 LIMO 数据构建框架 (LIMO Data Construction Framework)](#31-limo-数据构建框架-limo-data-construction-framework)
    * [3.2 [其他项目 B]](#32-其他项目-b)
* [4. 技术栈与工具 (Tech Stack & Tools)](#4-技术栈与工具-tech-stack--tools)
    * [4.1 编程语言与框架 (Languages & Frameworks)](#41-编程语言与框架-languages--frameworks)
    * [4.2 数据库与存储 (Databases & Storage)](#42-数据库与存储-databases--storage)
    * [4.3 云服务与基础设施 (Cloud & Infrastructure)](#43-云服务与基础设施-cloud--infrastructure)
    * [4.4 数据科学与机器学习 (Data Science & ML)](#44-数据科学与机器学习-data-science--ml)
    * [4.5 CI/CD 与 DevOps (CI/CD & DevOps)](#45-cicd-与-devops-cicd--devops)
    * [4.6 配置管理 (Configuration Management)](#46-配置管理-configuration-management)
    * [4.7 常用开发工具 (Common Dev Tools)](#47-常用开发工具-common-dev-tools)
* [5. 流程与工作流 (Processes & Workflows)](#5-流程与工作流-processes--workflows)
    * [5.1 软件开发生命周期 (SDLC) & 代码架构](#51-软件开发生命周期-sdlc--代码架构)
    * [5.2 代码评审与版本控制流程 (Code Review & Version Control)](#52-代码评审与版本控制流程-code-review--version-control)
    * [5.3 测试流程 (Testing Process)](#53-测试流程-testing-process)
    * [5.4 部署流程 (Deployment Process)](#54-部署流程-deployment-process)
    * [5.5 LIMO 数据构建与模型训练流程](#55-limo-数据构建与模型训练流程)
    * [5.6 需求与项目管理 (Requirement & Project Management)](#56-需求与项目管理-requirement--project-management)
* [6. 最佳实践与规范 (Best Practices & Guidelines)](#6-最佳实践与规范-best-practices--guidelines)
    * [6.1 编码规范 (Coding Standards)](#61-编码规范-coding-standards)
    * [6.2 安全规范 (Security Guidelines)](#62-安全规范-security-guidelines)
    * [6.3 API 设计规范 (API Design)](#63-api-设计规范-api-design)
    * [6.4 文档编写规范 (Documentation Standards)](#64-文档编写规范-documentation-standards)
    * [6.5 LIMO 框架开发规范](#65-limo-框架开发规范)
* [7. 学习资源与知识分享 (Learning & Knowledge Sharing)](#7-学习资源与知识分享-learning--knowledge-sharing)
    * [7.1 LIMO 框架相关文档与资源](#71-limo-框架相关文档与资源)
    * [7.2 内部技术分享会 (Internal Tech Talks)](#72-内部技术分享会-internal-tech-talks)
    * [7.3 推荐阅读与教程 (Recommended Readings & Tutorials)](#73-推荐阅读与教程-recommended-readings--tutorials)
    * [7.4 重要论文/文章研读 (Key Papers/Articles Study)](#74-重要论文文章研读-key-papersarticles-study)
    * [7.5 外部会议/培训资料 (External Conferences/Trainings)](#75-外部会议培训资料-external-conferencestrainings)
* [8. 常见问题与故障排查 (FAQ & Troubleshooting)](#8-常见问题与故障排查-faq--troubleshooting)
    * [8.1 LIMO 框架常见问题](#81-limo-框架常见问题)
* [9. 贡献指南 (Contribution Guide)](#9-贡献指南-contribution-guide)
* [10. 联系人与支持 (Contacts & Support)](#10-联系人与支持-contacts--support)

---

## 1. 引言与导览 (Introduction & Navigation)

欢迎访问公司知识库中心！

本文档是知识库的主入口，旨在提供一个清晰的结构，帮助你快速定位到所需的各类信息，包括团队使用的工具、标准化的工作流程、项目文档、技术分享以及最佳实践等。**特别是关于我们核心的 LIMO 数据构建框架的信息。**

**如何使用本文档:**
* 通过上方的**目录 (Table of Contents)** 快速跳转到感兴趣的章节。
* 每个章节会简要介绍该领域的内容，并提供指向更详细文档或资源的**超链接**。
* 如果你发现信息过时或缺失，请参考 [贡献指南](#9-贡献指南-contribution-guide) 进行更新或补充。

---

## 2. 新人入门指南 (Onboarding Guide)

面向新加入团队的成员，提供快速融入所需的基础信息和设置步骤。

* **环境配置:**
    * [开发环境搭建指南](./02_新人入门指南/dev_environment_setup.md)
    * [常用账号申请流程 (如GitLab, JIRA, Cloud等)](./02_新人入门指南/account_requests.md)
* **团队介绍:**
    * [团队组织架构与成员介绍](./02_新人入门指南/team_structure.md)
    * [团队沟通渠道 (如Slack频道列表)](./02_新人入门指南/communication_channels.md)
* **必读材料:**
    * [公司文化与价值观](./02_新人入门指南/company_culture.md)
    * **LIMO 数据构建框架快速入门:** [LIMO项目概述文档](./03_项目概览/limo/LIMO数据构建Pipeline项目文档.md) ---

## 3. 项目概览 (Projects Overview)

列出团队当前正在进行或已完成的重要项目。

### 3.1 LIMO 数据构建框架 (LIMO Data Construction Framework)
* **简介:** 该框架旨在系统化地生成、评估和筛选高质量的小样本数据集（LIMO数据），用于高效模型微调，解决传统大规模数据微调的数据瓶颈和算力开销问题。核心理念为 "LIMO" (Less Is More for Optimization)。
* **负责人:** 文倩 (协调), 赵翔, 浩智, 潮剑 (具体模块见文档)
* **主要文档:**
    * **项目背景与目标:** [LIMO数据构建Pipeline项目文档](./03_项目概览/limo/LIMO数据构建Pipeline项目文档.md)
    * **工程实现与架构:** [LIMO数据构建框架工程实现文档](./03_项目概览/limo/LIMO数据构建框架工程实现文档.md)
    * [项目设计文档 (链接待补充)]
    * [需求文档 (链接待补充)]
* **代码仓库:** [limo-framework代码库](https://github.com/Drip-Data/datapresso)
* **项目管理:** [链接到LIMO项目的JIRA看板/任务列表]

### 3.2 [其他项目 B]
* **简介:** [一句话或一段话描述项目B的目标、范围和当前状态]
* **负责人:** [项目负责人姓名]
* **主要文档:**
    * [项目设计文档](./03_项目概览/project_b/design_doc.md)
    * [需求文档](./03_项目概览/project_b/requirements.md)
* **代码仓库:** [链接到项目B的代码库]
* **项目管理:** [链接到项目B的JIRA看板/任务列表]

---

## 4. 技术栈与工具 (Tech Stack & Tools)

记录团队使用的主要技术、框架、平台和工具。

### 4.1 编程语言与框架 (Languages & Frameworks)
* **Python:**
    * 主要版本: [例如 3.10+] (LIMO项目要求Python 3.10+)
    * 常用库/框架: [例如 Flask, Django, Pandas, NumPy, Scikit-learn, PyTorch, TensorFlow]
    * 内部规范/最佳实践: [链接到Python编码规范](./06_最佳实践与规范/python_coding_standards.md)
    * [官方文档](https://www.python.org/) | [内部教程](./learning/python_tutorial.md)
* **[其他语言/框架]**

### 4.2 数据库与存储 (Databases & Storage)
* **关系型数据库:** [例如 PostgreSQL, MySQL] - [使用指南] | [最佳实践]
* **NoSQL数据库:** [例如 MongoDB, Redis, Elasticsearch] - [使用指南] | [选型建议]
* **对象存储:** [例如 AWS S3, MinIO] (LIMO框架可能使用S3等进行分布式数据传递) - [使用规范]
* **数据仓库:** [例如 Snowflake, BigQuery, ClickHouse] - [使用指南]

### 4.3 云服务与基础设施 (Cloud & Infrastructure)
* **主要云平台:** [例如 AWS, GCP, Azure]
    * [AWS常用服务指南](./04_技术栈与工具/aws_common_services.md)
    * [云资源申请与管理流程](./04_技术栈与工具/cloud_resource_management.md)
* **容器化:** Docker, Kubernetes (K8s) (LIMO项目可能使用Docker)
    * [Docker基础教程](./04_技术栈与工具/docker_basics.md)
    * [内部K8s集群使用指南](./04_技术栈与工具/k8s_usage.md)
* **监控与告警:** [例如 Prometheus, Grafana, Datadog, Sentry] - [配置指南]

### 4.4 数据科学与机器学习 (Data Science & ML)
* **数据处理:** Pandas, [Spark]
    * **LIMO 框架数据格式:** JSON Lines (详见LIMO文档) - [数据格式规范](./05_流程与工作流/limo_data_format.md)
    * **LIMO 使用库:** Hugging Face datasets, pandas, jsonlines
* **机器学习库:** Scikit-learn, [XGBoost, LightGBM] (LIMO 框架使用 Scikit-learn 进行多样性分析)
* **深度学习框架:** PyTorch, [TensorFlow/Keras]
* **MLOps平台/工具:** MLflow, [Kubeflow, DVC]
* **大语言模型 (LLM) 相关:**
    * **LIMO 数据生成/评估:** 调用大模型API (如 GPT-4) - 参考库: Curator, Loong, Deita Scorer, Loong Verifier
    * **LIMO 高级评估:** 基于模型反馈 - 参考库/概念: Cherry-LLM (IFD), LIMR, LESS
    * **LIMO 微调:**
        * 训练框架: `llamafactory` (集成)
        * 技术: PEFT, QLoRA, RLVR (多样性奖励)
        * 常用基模型: Llama3 等
    * **评估基准:** MMLU, BBH, Helm - [LIMO 模型评估方法](./processes/limo_evaluation_process.md)

### 4.5 CI/CD 与 DevOps (CI/CD & DevOps)
* **版本控制:** Git (LIMO 项目使用 Git) - [Git工作流规范](./05_流程与工作流/git_workflow.md)
* **CI/CD 工具:** [例如 GitLab CI, Jenkins, GitHub Actions]
* **代码质量检查:** [例如 SonarQube, ESLint, Flake8] (LIMO 项目强调测试覆盖率)

### 4.6 配置管理 (Configuration Management)
* **LIMO 配置:** 使用 YAML/JSON 文件, 可参考 Hydra, Pydantic, ConfigArgParse - [LIMO 配置说明](./03_项目概览/limo/configuration.md)

### 4.7 常用开发工具 (Common Dev Tools)
* **IDE:** [例如 VS Code, PyCharm, IntelliJ IDEA] - [推荐插件与配置]
* **项目管理:** [例如 JIRA, Trello, Asana]
* **文档协作:** [例如 Confluence, Google Docs, Notion, 本地Markdown]
* **API 测试:** [例如 Postman, Insomnia]

---

## 5. 流程与工作流 (Processes & Workflows)

定义团队协作和执行任务的标准流程。

### 5.1 软件开发生命周期 (SDLC) & 代码架构
* [概述团队遵循的开发模型](./05_流程与工作流/sdlc_overview.md)
* [各阶段定义与交付物](./05_流程与工作流/sdlc_phases.md)
* **LIMO 框架代码结构:** [查看LIMO工程文档](./03_项目概览/limo/LIMO数据构建框架工程实现文档.md#21-项目目录结构)

### 5.2 代码评审与版本控制流程 (Code Review & Version Control)
* [Code Review 的目的与重要性](./05_流程与工作流/code_review_importance.md)
* **LIMO 代码评审流程:** [详见LIMO工程文档](./03_项目概览/limo/LIMO数据构建框架工程实现文档.md#52-项目协作流程)
* **Git 工作流:** [例如 Gitflow, GitHub Flow]
    * **LIMO Git 分支策略:** main (稳定), dev (集成), feature/模块名 (开发) - [详见LIMO工程文档](./03_项目概览/limo/LIMO数据构建框架工程实现文档.md#52-项目协作流程)

### 5.3 测试流程 (Testing Process)
* [测试策略 (单元、集成、E2E)](./05_流程与工作流/testing_strategy.md)
* [测试用例编写规范](./05_流程与工作流/test_case_writing.md)
* [自动化测试框架与实践](./05_流程与工作流/automated_testing.md)
* **LIMO 测试策略:** 单元测试 (覆盖率 > 85%), 集成测试, 性能测试 - [详见LIMO工程文档](./03_项目概览/limo/LIMO数据构建框架工程实现文档.md#8-测试与质量保证)

### 5.4 部署流程 (Deployment Process)
* [不同环境部署策略](./05_流程与工作流/deployment_environments.md)
* [发布流程与审批机制](./05_流程与工作流/release_process.md)
* [回滚计划与应急预案](./05_流程与工作流/rollback_plan.md)
* **LIMO 部署与运行:** [查看LIMO工程文档](./03_项目概览/limo/LIMO数据构建框架工程实现文档.md#7-部署与运行指南)

### 5.5 LIMO 数据构建与模型训练流程
* **核心流程:** 用户配置 → 种子数据库 → [数据生成] → 质量评估 → 数据筛选 → [高级评估] → 集成训练 → 模型评估
* **各阶段详细说明:**
    * [5.1 用户配置输入层](./03_项目概览/limo/details/user_input.md) * [5.2 种子数据库](./03_项目概览/limo/details/seed_db.md)
    * [5.3 数据生成扩充层 (负责人: 文倩)](./03_项目概览/limo/details/data_generation.md)
    * [5.4 数据质量评估层 (负责人: 赵翔)](./03_项目概览/limo/details/quality_assessment.md)
    * [5.5 数据多维度筛选层 (负责人: 赵翔)](./03_项目概览/limo/details/data_filtering.md)
    * [5.6 高级评估与筛选层 (负责人: 浩智, 潮剑)](./03_项目概览/limo/details/advanced_assessment.md)
    * [5.7 集成训练层 (负责人: 浩智, 潮剑)](./03_项目概览/limo/details/training.md)
    * [5.8 模型评估层 (负责人: 待定)](./03_项目概览/limo/details/evaluation.md)
* **数据流转与格式:** 使用标准 JSON Lines - [详见LIMO文档](./03_项目概览/limo/LIMO数据构建Pipeline项目文档.md#61-数据流转与格式规范)
* **参考文档:**
    * [LIMO数据构建Pipeline项目文档](./03_项目概览/limo/LIMO数据构建Pipeline项目文档.md)
    * [LIMO数据构建框架工程实现文档](./03_项目概览/limo/LIMO数据构建框架工程实现文档.md)

### 5.6 需求与项目管理 (Requirement & Project Management)
* [需求收集与分析流程](./05_流程与工作流/requirement_gathering.md)
* [需求文档模板](./templates/requirement_spec_template.md)
* [项目任务拆解与排期](./05_流程与工作流/task_breakdown_scheduling.md)
* [进度跟踪与风险管理](./05_流程与工作流/progress_tracking_risk_management.md)

---

## 6. 最佳实践与规范 (Best Practices & Guidelines)

沉淀团队在开发过程中总结的最佳实践和必须遵守的规范。

### 6.1 编码规范 (Coding Standards)
* [通用编码原则 (如DRY, KISS, SOLID)](./06_最佳实践与规范/general_coding_principles.md)
* **Python 编码规范:** 遵循 PEP 8 和 Google Python 风格指南 (LIMO 项目要求) - [链接到内部详细规范](./06_最佳实践与规范/python_coding_standards.md)
    * 行长限制 (如 LIMO 要求 <= 100)
    * 命名规范 (详见 LIMO 文档)
    * **类型注解** (LIMO 项目要求)
    * **注释规范:** NumPy/SciPy 风格, 英文注释 (LIMO 项目要求)
* [JavaScript/TypeScript 编码规范](./06_最佳实践与规范/js_coding_standards.md)
* [SQL 编写规范](./06_最佳实践与规范/sql_coding_standards.md)

### 6.2 安全规范 (Security Guidelines)
* [Web 应用安全checklist](./06_最佳实践与规范/web_security_checklist.md)
* [数据安全与隐私保护](./06_最佳实践与规范/data_security_privacy.md)
* [依赖库安全管理](./06_最佳实践与规范/dependency_security.md)
* [认证与授权最佳实践](./06_最佳实践与规范/auth_best_practices.md)

### 6.3 API 设计规范 (API Design)
* [RESTful API 设计指南](./06_最佳实践与规范/restful_api_design.md)
* [API 版本管理策略](./06_最佳实践与规范/api_versioning.md)
* [错误处理与状态码规范](./06_最佳实践与规范/api_error_handling.md)

### 6.4 文档编写规范 (Documentation Standards)
* [为什么以及何时编写文档](./06_最佳实践与规范/documentation_importance.md)
* [README 文档模板](./templates/readme_template.md)
* [设计文档模板](./templates/design_doc_template.md)
* **LIMO 文档要求:** 代码变更同步更新文档, 每周同步项目进度 - [详见LIMO工程文档](./03_项目概览/limo/LIMO数据构建框架工程实现文档.md#52-项目协作流程)

### 6.5 LIMO 框架开发规范
* **模块化设计:** 接口一致性, 配置驱动, 松耦合, 可插拔 (详见 LIMO Pipeline 文档) - [模块化原则](./03_项目概览/limo/development_guidelines.md#modularity)
* **接口规范:** `__init__`, `process`, `get_status`, `update_config` (详见 LIMO 工程文档) - [接口定义](./03_项目概览/limo/development_guidelines.md#interfaces)
* **集成规范:** 配置依赖, 错误处理, 进度报告, 资源管理 (详见 LIMO 工程文档) - [集成规范](./03_项目概览/limo/development_guidelines.md#integration)

---

## 7. 学习资源与知识分享 (Learning & Knowledge Sharing)

汇总有助于团队成员学习成长的资源和内部知识沉淀。
* [GEMINI API 密钥共享_credit_to_赵翔](./07_学习资源与知识分享/api_keys_and_usage.md)

### 7.1 LIMO 框架相关文档与资源
* **核心文档:**
    * [LIMO数据构建Pipeline项目文档 (背景、理念、目标、各层说明)](./03_项目概览/limo/LIMO数据构建Pipeline项目文档.md)
    * [LIMO数据构建框架工程实现文档 (架构、代码、流程、规范)](./03_项目概览/limo/LIMO数据构建框架工程实现文档.md)
* **相关技术/概念:**
    * LIMO (Less Is More for Optimization) 效应
    * IFD (Instruction Following Difficulty) - Cherry-LLM
    * LIMR (Learning Improvement Measurement)
    * LESS (Learning Efficacy Score System)
    * RLVR (Reinforcement Learning with Value-based Rewards)
    * PEFT / QLoRA
    * [相关论文链接 (待补充)]

### 7.2 内部技术分享会 (Internal Tech Talks)
* [YYYY-MM-DD] **主题:** [其他分享主题 A] - [主讲人] - [链接到录屏/PPT/笔记]
### 7.3 推荐阅读与教程 (Recommended Readings & Tutorials)
* **书籍:**
    * [《Clean Code》 学习笔记](./07_学习资源与知识分享/clean_code_notes.md)
    * [《Designing Data-Intensive Applications》 核心概念总结](./07_学习资源与知识分享/ddia_summary.md)
* **在线课程/平台:** 
* **技术博客/网站:** 
    * [The Second Half-姚顺雨](https://ysymyth.github.io/The-Second-Half/)
    * [Nvidia Developer](https://developer.nvidia.com/)

### 7.4 重要论文/文章研读 (Key Papers/Articles Study)
* **LIMO 相关:**
    * [LIMO 效应相关论文 (链接待补充)]
    * [LIMR/LESS/Cherry-LLM/RLVR 相关论文 (链接待补充)]
* **模型微调:**
    * [PEFT/LoRA/QLoRA 相关论文 (链接待补充)]
* **[其他重要或领域相关的论文]**

### 7.5 外部会议/培训资料 (External Conferences/Trainings)
* [外部培训课程资料汇总](./07_学习资源与知识分享/trainings/external_training_materials.md)
* [2024 - DA数智大会-上海站] - credit to 赵翔
    * [理想汽车业务智能系统中的大模型应用实践](./07_学习资源与知识分享/conferences/2025_DA数智大会_上海站/理想汽车业务智能系统中的大模型应用实践.md) - 介绍理想汽车在大模型应用方面的实践经验。
    * [面向领域的大模型思维能力](./07_学习资源与知识分享/conferences/2025_DA数智大会_上海站/面向领域的大模型思维能力.md) - 探讨如何提升领域大模型的思维能力。
    * [网易伏羲有灵众包平台：数据制备与AI能力闭环](./07_学习资源与知识分享/conferences/2025_DA数智大会_上海站/网易伏羲有灵众包平台：数据制备与AI能力闭环.md) - 分享网易伏羲在数据制备和AI能力闭环方面的经验。
    * [OpenSeek项目：全要素开源AI模型构建](./07_学习资源与知识分享/conferences/2025_DA数智大会_上海站/OpenSeek项目：全要素开源AI模型构建.md) - 介绍OpenSeek项目的开源AI模型构建。
    * [相关讲座PPT](./07_学习资源与知识分享/conferences/2025_DA数智大会_上海站/相关ppt/) - 包含上述讲座的PPT文件。


---

## 8. 常见问题与故障排查 (FAQ & Troubleshooting)

收录常见问题及其解决方案，以及通用故障排查思路。

### 8.1 LIMO 框架常见问题
* **数据格式不兼容:** [解决方案参考LIMO工程文档](./03_项目概览/limo/faq.md#data-format-issues)
* **资源不足 (内存/显存):** [解决方案参考LIMO工程文档](./03_项目概览/limo/faq.md#resource-issues)
* **模型训练不稳定:** [解决方案参考LIMO工程文档](./03_项目概览/limo/faq.md#training-instability)
* **第三方API限制:** [解决方案参考LIMO工程文档](./03_项目概览/limo/faq.md#api-limits)
* **[其他LIMO相关问题待补充]**

* **[其他通用问题]**
    * [开发环境问题](./08_常见问题与故障排查/dev_env_issues.md)
    * [服务部署问题](./08_常见问题与故障排查/deployment_issues.md)
* **通用故障排查指南:**
    * [网络问题排查步骤](./08_常见问题与故障排查/network_issues.md)
    * [性能问题分析方法](./08_常见问题与故障排查/performance_analysis.md)

---

## 9. 贡献指南 (Contribution Guide)

指导团队成员如何参与维护和更新本知识库以及 LIMO 框架本身。

* **编辑权限与流程:** [说明谁可以编辑，是否需要审批](./09_贡献指南/editing_permissions.md)
* **文档结构与风格:** [保持本文档结构，遵循Markdown规范](./09_贡献指南/structure_style.md)
* **LIMO 框架贡献流程:**
    * **代码贡献:** 遵循 [Git 工作流](./05_流程与工作流/git_workflow.md) 和 [代码评审流程](./processes/code_review_process.md)
    * **Issue 报告与处理:** [链接到项目 Issue Tracker]
* **文件命名约定:** [例如 `category/sub_category/topic_name.md`](./09_贡献指南/naming_conventions.md)
* **链接格式:** [推荐使用相对路径链接内部文档](./09_贡献指南/linking_format.md)
* **如何添加新页面/章节:** [步骤说明](./09_贡献指南/adding_new_content.md)

---

## 10. 联系人与支持 (Contacts & Support)

如果找不到所需信息或对知识库有疑问，可以联系以下人员或渠道。

* **知识库管理员:** [管理员姓名或团队] - [联系方式如邮箱/Slack]
* **LIMO 数据构建框架项目:**
    * **整体协调:** 文倩
    * **数据生成:** 文倩
    * **质量评估/筛选:** 赵翔
    * **高级评估/训练:** 浩智, 潮剑
    * **项目相关 Slack 频道:** [#limo-project]
* **各技术领域专家 (其他):**
    * 后端: [专家姓名]
    * 前端: [专家姓名]
    * 基础设施: [专家姓名]
* **相关 Slack 频道:** [#knowledge-base-support], [#general-tech-discussion]

---
