## APP-TO-APP

应用程序到应用程序的通信

### Simple Notification Service(SNS)

SNS 用于应用程序通过文本、电子邮件或移动推送向客户发送信息，或将单条信息复制到多个应用程序。

### Simple Queue Service

当您想向另一个应用程序发送消息，但用户流量突然增加有可能产生大量消息时，就需要使用 SQS。

### ELB

### Autoscaling

通常与ELB一起使用

### Amazon AppFlow 

解决了从第三方（如 Salesforce）向 AWS 复制数据的问题。

### Amazon EventBridge 

像邮局一样协调跨应用程序的事件。

### Amazon MQ 

托管队列与 SQS 类似，但使用的是开源软件而非 AWS 专有软件。

### Amazon Step Functions 

解决了如何组织serverless功能，使它们能像完整应用一样工作的问题。