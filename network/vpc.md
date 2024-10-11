## VPC

每次您创建账户时，AWS都会自动在每个区域创建一个默认 VPC。



<img src="./img/1.png" alt="1" style="zoom:50%;" />

### Subnet

子网位于单个可用区内（例如子网1，子网2），在aws中创建服务器的时候，必须指定位于哪个子网.

创建子网时，可以是私有子网和公有子网

<img src="./img/2.png" alt="2" style="zoom:50%;" />

<img src="./img/3.png" alt="3" style="zoom:50%;" />

### Internet Gateway

<img src="./img/5.png" alt="5" style="zoom:50%;" />

### NAT Gateway

<img src="./img/6.png" alt="6" style="zoom:50%;" />

<img src="./img/7.png" alt="7" style="zoom:50%;" />

### Virtual Private Gateway（VPN Gateway)

<img src="./img/8.png" alt="8" style="zoom:50%;" />

### Direct Connect

<img src="./img/9.png" alt="9" style="zoom:50%;" />

## Default Vpcs

<img src="./img/10.png" alt="10" style="zoom:50%;" />

## Firewall

- NACL 监控进出子网的流量
- NACL 是无状态防火墙
  - 必须允许输入和输出方向的流量
- 安全组充当个人资源的防火墙
- 安全组是有状态的
  - 只需允许请求方向，响应也自动被允许

无状态的防火墙

<img src="./img/11.png" alt="11" style="zoom:50%;" />

有状态的防火墙

+ 他们跟踪了链接（哪个请求到哪个响应）
+ 如果请求被允许，那么响应也是放行的，也就是不需要出战规则

![12](./img/12.png)

### Network Access Control List (NACL，无状态)

<img src="./img/13.png" alt="13" style="zoom:50%;" />

### Security Group(有状态)

<img src="./img/14.png" alt="14" style="zoom:50%;" />

## 总结

![15](./img/15.png)