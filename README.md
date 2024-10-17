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

Part Two

