# 鱼叉式网络钓鱼的新境界

> 原文：<https://www.social-engineer.org/social-engineering/a-new-level-to-spearphishing/>

slashdot 上最近的一个故事引起了我的注意，我们已经将它归档在社会工程师档案中新的和改进的[鱼叉式网络钓鱼](: https://www.social-engineer.org/framework/general-discussion/real-world-examples/phishing/) [攻击部分。](https://www.social-engineer.org/framework/general-discussion/common-attacks/)

这个故事让我感到有趣，让我在地球上发布博客的最糟糕的时间赶过来打这篇文章，是因为这些攻击被“变得新”了。

大多数聪明的 IT 管理员不会点击“看布兰妮裸体”或“调整你的美国银行账户”的链接，因为他们知道这是[网络钓鱼。](https://www.social-engineer.org/framework/general-discussion/real-world-examples/phishing/)

但随之而来的是“新的和改进的闪亮的网络钓鱼”。这些社会工程师已经做了功课。他们有 IT 管理员的名字，他们有当前项目的名字和细节以及其他信息，这使得电子邮件非常可信。但还不止于此，这才是会让你站起来关注的部分。他们并不要求点击一个链接或运行一个文件或访问一个网站，他们只是要求管理员改变他们服务器的一些配置。这些改变将允许他们的邮件服务器被用来发送垃圾邮件，或者在他们的服务器中打开一些其他的漏洞。

看看这样一封邮件:
 `---------------------------------
Dear Valued Customer,`

我们很高兴地宣布新数据中心的上线日期，计划于 2010 年 4 月 19 日上线。
请更新您的防火墙规则，以允许来自以下 IP 地址范围的 SMTP 流量通过端口 25:XXX . XXX . XXX . XXX . XXX/xx(XXX . XXX . XXX . XXX–XXX . XXX . XXX . XXX . XXX)xx . XXX . XXX/xx(xx . XXX . XXX . xx–xx . XXX . XXX . XXX . XXX)

如果您的电子邮件服务器上有控制允许连接电子邮件中继的 IP 的设置，请确认这些设置也已更新。

我们将能够在 2010 年 4 月 19 日前一周测试和验证连接。此外，我们将在发布前代表所有客户主动运行连接测试，如果我们无法从您的任何域的所有指定 IP 地址连接到该域，我们将直接与您联系。

在发布新的 IP 地址之前，我们建议您使用管理中心中“域属性”页面上的“延期通知”选项，为您的域设置和配置延期通知警报功能。当您的域中的延期电子邮件达到或超过自定义阈值时，延期通知警报功能会向您发送一封邮件。新的 IP 地址启用后，此功能将有助于确保发送到您的域的电子邮件不会因为尝试连接到您的网络失败而被延迟，并且在电子邮件被延迟超过您可接受的限制时，您会收到警报。有关如何设置延期通知提醒功能的更多信息，请参见资源中心的《管理中心指南》。

请参考管理中心的“配置”子选项卡，以获得允许随时连接到您的环境的 IP 的完整列表。
———————

一个不知情的管理员会这样做，他们会上当，对网络造成严重破坏。

直到下一次…