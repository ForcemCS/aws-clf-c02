## Demo

默认的vpc概览

<img src="./img/d1.png" alt="d1" style="zoom:50%;" />

### 创建示例VPC

1. <img src="./img/D2.png" alt="D2" style="zoom:50%;" />

   其他信息保持默认

2. 创建subnet（已使要部署的资源放到其中）

   <img src="./img/d3.png" alt="d3" style="zoom:50%;" />

   现在此子网中的资源是无法与互联网进行通信的，且互联网无法访问资源

3. 创建互联网网关

   <img src="./img/d4.png" alt="d4" style="zoom:50%;" />

   <img src="./img/d5.png" alt="d5" style="zoom:50%;" />

4. 为子网新增路由表，以使流量发送到互联网网关

   

   <img src="./img/d6.png" alt="d6" style="zoom:50%;" />

   <img src="./img/d7.png" alt="d7" style="zoom:50%;" />

   <img src="./img/d8.png" alt="d8" style="zoom:50%;" />

**以上部分完成了将私有子网subnet-01转变为公有子网，接下来我们将确定哪些流量可以流量这些子网，然后我们再利用安全组，控制流向单个设备的流量**

5. 创建安全组

   <img src="./img/d9.png" alt="d9" style="zoom:50%;" />

   <img src="C:\Users\ForceCS\AppData\Roaming\Typora\typora-user-images\image-20241014161259686.png" alt="image-20241014161259686" style="zoom:50%;" />

   创建入栈规则后，默认返回的流量是允许的

6. 创建NACL

   <img src="./img/d12.png" alt="d12" style="zoom:50%;" />

   <img src="./img/d13.png" alt="d13" style="zoom:50%;" />

   如果你想为哪几个子网使用此NACL

   ![D14](./img/D14.png)

   

