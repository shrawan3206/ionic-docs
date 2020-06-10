---
title: '苹果应用商店'
previousText: '目标概述'
previousUrl: '/docs/appflow/destinations/destinations'
nextText: '部署到 Google Play 商店'
nextUrl: '/docs/appflow/destinations/google'
---

Apple App Store目标允许您上传您已完成的二进制文件到 App Store Connect 为iOS 设备提供的服务。


![/docs/assets/img/appflow/apple-add-destination.png](/docs/assets/img/appflow/apple-add-destination.png)

对于这个目标您需要：

> **前提条件：** 为了构建您可以上传到苹果应用商店的二进制文件，您将需要一个在应用流中配置的生产安全配置文件。 详细信息 [这里](https://ionicframework.com/docs/appflow/package/credentials#ios-credentials)


- **Apple App Store目标的实例名称**
    - 用户将引用此配置的内容为
- **您的 Apple ID**
    - 不需要是所有者帐户，但需要是一个可以上传二进制文件并更新应用程序的帐户。
- **您的 Apple ID 的专用密码**
    - 要设置一个特定应用程序密码，您需要为您的帐户启用两步验证。
    - 一旦启用，登录到 [https://appleid.apple.com/](https://appleid.apple.com/) 并且在安全部分有一个创建/管理专用密码的选项
- **App Store Connect 中应用的Apple ID**
    - 这是一个由苹果生成的值，这是您的应用程序所独有的。 要找到它：
        1. 登录到 App Store 连接: [https://appstoreconnect.apple.com/](https://appstoreconnect.apple.com/)
        2. 导航到应用程序
        3. 在应用程序的页面上，在一般信息下，Apple ID (应全部为数字)

    ![/docs/assets/img/appflow/apple-apple-id.png](/docs/assets/img/appflow/apple-apple-id.png)

- (可选) 您的团队名称，您的 Apple ID (如果您的帐户在多个团队中)