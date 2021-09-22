---
title: 了解企业Creative Cloud和Acrobat序列号过期
description: 了解适用于企业和Acrobat的Creative Cloud的序列号过期体验
role: User
level: Beginner, Intermediate
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: 6b819aef801e003e5a160d24ba69522cf6a7e715
workflow-type: tm+mt
source-wordcount: '848'
ht-degree: 3%

---

# 了解企业Creative Cloud和Acrobat序列号过期

以往，Adobe通过我们的应用程序(如Creative Suite、企业Creative Cloud、Acrobat XI、Acrobat DC)向企业定期许可协议(ETLA)的客户发布序列号。 这些序列号确实有过期日期。 到期日期过后，产品将不再工作，因此在序列号过期之前计划迁移非常重要。 本页概述了确保您的最终用户能够继续访问其Adobe应用程序和服务所需的步骤。

## 检查序列号的过期日期

### 查找序列号

与您的ETLA协议关联的序列号许可证可通过[Adobe许可网站](https://licensing.adobe.com/)(LWS)获取。 按照以下说明显示和下载：

1. 使用您的Adobe ID和密码登录到[Adobe许可网站](https://licensing.adobe.com/)(LWS)。
1. 选择&#x200B;**许可证>检索序列号**。
1. 输入&#x200B;**最终用户ID**&#x200B;或&#x200B;**部署到ID**。
1. （可选）选择&#x200B;**产品名称**、**产品版本**&#x200B;或&#x200B;**平台**&#x200B;以筛选结果。
1. 单击“搜索”。
1. 此时会显示产品名称和序列号。
1. （可选）选择“导出至CSV”以下载序列号列表。

![查找序列号](assets/retrieveserialnumbers.png)

### 检查过期日期

[AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html)是一个命令行实用程序，供IT管理员检查计算机上的Adobe产品是否使用已过期或即将过期的序列号。 该工具将显示产品许可标识符(LEID)、加密序列号和过期日期等信息。 此[页面](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html)包含有关在Mac或Windows计算机上下载和使用该工具的说明。

## 了解序列号过期前后的最终用户体验

Acrobat和Creative Cloud企业版应用程序将在过期60天前开始显示消息（在应用程序中）。 序列号过期后，产品将停止工作，并提示用户采取操作。

### Creative Cloud企业体验

以下信息概述了最终用户体验。 下面是一个简短的视频，然后是对最终用户体验的回顾。

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**到期前**

从序列号过期60天前开始，企业Creative Cloud的所有应用程序都会向最终用户显示“产品内”对话框。 此消息将每周显示，直到到期前30天，然后将每天显示，直到到期日，显示&#x200B;*您的许可证即将过期。 此Adobe产品使用的许可证将于2020年11月29日到期。 请联系您的管理员以确保继续访问*。

![过期消息之前的CCE](assets/cceexpiring.png)

**过期后**

序列号过期后，用户将无法再访问企业Creative Cloud。 在过期后首次启动时，系统将提示用户显示一个对话框，其中显示&#x200B;*您输入的序列号已过期。 无法许可此产品。 请联系客户支持*。

![过期消息后的CCE](assets/cceafterexpire.png)

对于所有后续启动应用程序的尝试，系统将提示最终用户立即登录&#x200B;**，然后选择创建自己的Adobe ID并进入试用模式。**&#x200B;但是，最终用户创建的任何新Adobe ID将不会与您组织的许可证关联，并会给您的用户带来额外的混乱。 为避免业务中断和/或不必要的混淆，请在序列号过期之前将用户迁移到指定用户许可。

![CCE登录对话框1](assets/ccesignin1.png)

![CCE登录对话框2](assets/ccesignin2.png)

### Acrobat体验

以下信息概述了最终用户体验。 下面是一个简短的视频，然后是对最终用户体验的回顾。

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**到期前**

从序列号过期60天前开始，Acrobat会向最终用户显示产品弹出消息。 此选项将每周显示一次，直到过期7天。 然后，它将开始每天显示，显示&#x200B;*您的Adobe Acrobat许可证将于30/11/2020过期。 请联系您的管理员以继续使用Acrobat而不中断。*

![Acrobat过期消息](assets/acrobatexpiring.png)

**过期后**

序列号过期后，用户将无法再访问Acrobat。 在过期后首次启动时，系统将提示用户显示一个对话框，其中显示&#x200B;*您输入的序列号已过期。 无法许可此产品。 请联系客户支持。*

![过期消息后的Acrobat](assets/acrobatafterexpire.png)

对于所有后续启动Acrobat的尝试，系统将提示最终用户“立即登录&#x200B;**”，然后选择创建自己的Adobe ID并进入试用模式。**&#x200B;但是，最终用户创建的任何新Adobe ID将不会与您组织的许可证关联，并会给您的用户带来额外的混乱。

![Acrobat登录对话框1](assets/acrobatsignin1.png)

![Acrobat登录对话框2](assets/acrobatsignin2.png)

## 如需帮助，请联系我们

如果您对使用[AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html)工具有疑问，或者需要帮助从序列号部署迁移到指定用户，则可以选择以下选项：
* 向Adobe企业入职团队发送电子邮件 — **entonb@adobe.com**
* 在[Admin Console](https://adminconsole.adobe.com/support)中打开支持票证
* 联系您的Adobe客户经理或客户成功经理
