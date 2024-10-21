## Part One

1. 配置虚拟默认 VPC 时，会自动创建 Internet 网关、子网和默认安全组。
2. 公共子网是附加了互联网网关的子网”。 Internet 网关允许公共子网内的资源与 Internet 进行通信，从而使子网可以从 Internet 进行访问。
3. What is the primary purpose of AWS edge locations？
   + 为最终用户提供对内容和服务的低延迟访问”。 AWS 边缘站点是 Amazon CloudFront 全球内容分发网络 (CDN) 的一部分。它们战略性地分布在世界各地，使数据更接近最终用户，减少延迟并提高内容交付的性能。

4. What is the primary purpose of an AWS NAT Gateway?
   + 允许私有子网中的实例访问互联网”。 AWS NAT 网关允许私有子网中的实例建立到互联网的出站连接，同时保持实例本身的私有性并防止直接互联网访问。

5. Which of the following statements accurately describes AWS Global Infrastructure's approach to data center redundancy?
   + 它在每个区域内使用多个可用区来实现高可用性和容错”。每个 AWS 区域都设计有多个物理上独立的可用区 (AZ)，这些可用区通过低延迟链路互连。这种设计提供容错能力，并允许客户构建高度可用的应用程序。

6. Which of the following statements is true about Network Access Control Lists (NACLs) in AWS?
   + AWS 中的网络访问控制列表 (NACL) 在子网级别运行，控制入站和出站流量。它们根据规则允许或拒绝流量，为 VPC 提供额外的安全层

7. What is an AWS security group?
   + 控制 EC2 实例的入站和出站流量的虚拟防火墙”。 AWS 安全组是 AWS 中网络安全的基本组成部分。它充当虚拟防火墙，在实例级别控制入站和出站流量。
8. 子网是用于在 VPC 内路由流量的 IP 地址的集合”。子网是 Amazon VPC 的逻辑划分，允许您分段和管理 IP 地址，以便在 VPC 内的资源之间路由网络流量。
9. What is the purpose of AWS Local Zones in terms of workload placement?
   +  AWS 本地扩展区旨在让 AWS 服务更接近特定地理位置的最终用户。通过将工作负载放置在本地区域中，您可以实现对 AWS 服务的低延迟访问，从而提高应用程序性能和用户体验。

## Part Two

AWS CloudFormation 是一项可帮助您以可预测的自动化方式预置和管理 AWS 资源的服务。它允许您使用模板将基础架构定义为代码，然后部署和管理这些模板中定义的资源

**Refactor migration strategy**涉及对应用程序代码及其底层架构进行重大更改，以针对云原生服务进行优化。通过重构应用程序，您可以充分利用 AWS 提供的可扩展性和性能优势。

**AWS OpsWorks** 是一项配置管理服务，可帮助您自动部署和管理应用程序。它提供了定义应用程序架构、管理实例和自动化任务的功能。 OpsWorks 支持多种配置管理工具，包括 Chef 和 Puppet

**AWS Repurchase migration strategy**是指用不同供应商的解决方案替换现有的应用程序或软件。当前的应用程序或软件不再满足业务需求或有更好的替代方案时，通常会采用这种策略。

AWS MGN 是一项完全托管的服务，可简化并加速应用程序从本地环境到 AWS 的迁移。它提供自动复制、调度和编排功能来简化迁移过程。

Amazon Redshift 是 AWS 提供的完全托管的 PB 级数据仓库服务。它允许您使用 SQL 查询有效地分析大型数据集。 Redshift 针对在线分析处理 (OLAP) 工作负载进行了优化，并提供高性能、列式存储和并行查询执行

**AWS Application Discovery Service** 用于发现和收集有关本地应用程序和依赖项的数据

**AWS Systems Manager Automation** 使您能够在 AWS 环境中自动执行手动和重复性任务。它提供了一种定义和执行工作流程（称为自动化文档）的方法，可对 AWS 资源执行操作。这有助于提高运营效率并减少人工干预的需要

AWS Snow 设备是坚固耐用的便携式设备，旨在帮助您安全地离线传输大量数据。当您需要在直接网络连接不可行或高效的情况下将数据集、备份或存档移入或移出 AWS 时，可以使用它们。

AWS Control Tower 的用于建立安全，合规的多账户AWS环境

AWS re-platform migration strategy降低了迁移遗留应用程序的复杂性。重新平台迁移策略涉及对应用程序堆栈进行细微调整以利用云原生服务。它允许您实现应用程序现代化，同时降低与完整应用程序重新设计相关的复杂性和风险。

Amazon SNS 是一种完全托管的发布/订阅消息服务，支持创建消息并将其传送到分布式系统或独立终端节点。它提供了发布和订阅主题的能力，允许可扩展且灵活的消息传递模式。 SNS 通常用于需要事件驱动架构、推送通知或扇出场景的应用程序。

AWS Snowmobile 是一种安全的数据传输设备，可以处理 EB 级数据迁移到 AWS。它是一个由半挂车牵引的坚固集装箱，旨在以安全高效的方式传输极大的数据集。

AWS Service Catalog 使组织能够创建和管理批准在其环境中使用的 IT 服务目录。它提供了一种受控且一致的方式来分发和管理服务，允许用户找到并部署他们所需的经批准的资源。

AWS DataSync 是一项数据传输服务，用于自动化和加速本地存储系统与 AWS 存储服务之间的数据移动。它简化并加速了数据迁移、数据复制和数据处理工作流程。

AWS Step Functions可让您将多个 AWS 服务协调到无服务器工作流中，从而快速构建和更新应用程序。

AWS Api Gateway 可帮助您使用全面管理的服务构建 HTTP、REST 和 WebSocket API，从而轻松创建、发布、维护和管理

### 数据库服务

RDS提供全面管理的关系型数据库，支持 MySQL、PostgreSQL 和 MariaDB 等 SQL 数据库

**Amazon DynamoDB**完全托管的 NoSQL 数据库，旨在以任何规模运行高性能应用程序

**Amazon ElastiCache**提供可管理的内存数据结构存储，通常用于缓存、会话管理和实时分析

**Amazon Timestream**提供全面管理的专用时间序列数据库引擎，适用于从低延迟查询到大规模数据摄取的各种工作负载。

**AWS Database Migration Service (DMS)**服务允许将数据库迁移到 AWS，且停机时间最短

### 开发者工具

**Amazon X-Ray**服务通过请求跟踪帮助您调试和分析微服务应用程序，从而找到问题和性能的根本原因？

**AWS CodeDeploy**可将代码自动部署到任何实例，包括内部部署和云基础设施

**AWS CodeBuild**服务在云中构建和测试代码，实现持续集成

**AWS CodePipeline**自动完成发布流程中的构建、测试和部署阶段

**AWS CodeStar**用于在 AWS 上创建、管理和使用软件开发项目

### 管理与治理

**Amazon CloudWatch**可以统一查看多个 AWS 资源的运行状况和性能监控？

**AWS CloudTrail**允许您跟踪 AWS API 调用，帮助您进行治理、合规性和运营审计

**AWS License Manager** 服务允许您跨 AWS 和内部部署环境管理来自供应商的软件许可证，帮助您跟踪、控制和优化许可证使用情况

**AWS Organizations**允许您中管理多个 AWS 账户、应用策略并合并计费

**AWS Control Tower**提供一个登陆区，帮助您根据最佳实践建立和管理安全的多账户 AWS 环境

### 示例架构图

+ 具有数据管理功能的全球多区域API

  <img src="C:\Users\ForceCS\Desktop\aws\doc\img\1.png" alt="1" style="zoom:50%;" />

+ 验证和约束

  <img src="C:\Users\ForceCS\Desktop\aws\doc\img\2.png" alt="2" style="zoom:50%;" />
