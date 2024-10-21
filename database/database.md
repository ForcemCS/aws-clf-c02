## Self-Managed Datastores

### Database Running on an EC2 Virtual machine or ECS or EKS

EC2 instance contents
- Most “unmanaged” option
- More control
- More responsibility
- Cost less in service dollars
- Cost more in Operational Overhead

Amazon Elastic Kubernetes Service (Amazon EKS)
- Most “unmanaged” option
- More control
- More Responsibility
- Cost less in service dollars
- Cost more in Operational Overhead
- 可以通过 Fargate 而不是 EC2 集群来降低成本

## AWS-Managed Datastores

### SQL-datastores

**1. Amazon Relational Database Service (RDS):** RDS 是托管的关系型数据库服务，支持多种流行的数据库引擎，包括：

- **MySQL:** 适用于 Web 应用程序、电子商务平台、内容管理系统等。例如，一个在线商店可以使用 MySQL 存储产品信息、客户数据和订单信息。
- **PostgreSQL:** 适用于需要高级功能（如地理空间数据支持、JSONField）的应用程序，以及对数据完整性要求较高的场景。例如，一个地图应用可以使用 PostgreSQL 存储地理位置数据，一个金融机构可以使用它来存储交易记录。
- **Oracle:** 适用于企业级应用程序，以及需要 Oracle 特有功能（如 PL/SQL）的场景。例如，一个大型企业可以使用 Oracle 数据库来管理其复杂的业务数据。
- **SQL Server:** 适用于需要与 Microsoft 技术栈集成的应用程序。例如，一个使用 .NET 框架开发的应用程序可以使用 SQL Server 作为其后端数据库。
- **MariaDB:** MySQL 的一个分支，与 MySQL 高度兼容，并且在某些方面进行了改进。适用于与 MySQL 类似的场景，并可作为 MySQL 的替代方案。
- **Amazon Aurora:** MySQL 和 PostgreSQL 兼容的关系数据库，性能和可用性更高。适用于对性能和可用性要求很高的应用程序，例如高流量的 Web 应用程序和游戏平台。

**2. Amazon Aurora Serverless:** Aurora 的无服务器版本，可以根据工作负载自动扩展和缩减数据库容量，从而降低成本并简化运维。适用于负载波动较大的应用程序，例如开发/测试环境、移动后端和物联网应用。

**3. Amazon Redshift:** 一个数据仓库服务，专为大规模数据分析和商业智能而设计。例如，一个电商平台可以使用 Redshift 来分析用户行为数据，从而优化营销策略

### NoSQL-datastores

去掉前两个

<img src="C:\Users\ForceCS\Desktop\aws\database\img\1.png" alt="1" style="zoom:50%;" />

