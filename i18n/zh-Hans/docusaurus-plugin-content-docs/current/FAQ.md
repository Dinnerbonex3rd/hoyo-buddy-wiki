<!-- markdownlint-disable MD026 MD040 MD047 -->
# 常见问题

## 有东西不运作怎么办？

如果 Hoyo Buddy 出现问题，你可以在[Discord 服务器](https://link.seria.moe/hb-dc)@seria_ati 或者[私信](https://discord.com/users/410036441129943050)以获取协助。

## Hoyo Buddy用着安全吗?

请参阅[账号安全](./Account-Security.md)页面获取详情。

## 我该用哪种登录方式?

| 登录方式 | 用手机登录 | 用电脑登录 | 用主机登录 | 自动与手动兑换码 | 备注
|---|---|---|---|---|---
| 邮箱与密码 | ✅ | ✅ | ✅[*](./Before-Start.md) | ✅ | 较为简单
| 开发者工具 | ❌ | ✅ | ❌ | ❌ | ...

:::note

“邮箱与密码”指的是**Hoyoverse账号的**邮箱和密码, 不是 Google、Apple 等账号。

:::

更多资讯:

- [Hoyo Buddy安全吗？](./Account-Security.md)
- [电子邮箱与密码登录方式如何运作？](./Account-Security.md#how-does-the-email-and-password-login-method-work)
- [为什么兑换码功能仅限于使用邮箱和密码登录的用户？](#why-are-code-redemption-features-exclusive-to-users-logged-in-with-email--password)

## 为什么部分文字仍显示为英文，即使我已经选择了其他语言？

这是因为你看到的文字翻译并未完成。目前 hoyo Buddy 的翻译是由一小组志愿者负责，他们也有自己的生活。所以，如果你希望加快翻译进度，欢迎加入翻译团队！若有兴趣, 请参阅[贡献指南](https://github.com/seriaati/hoyo-buddy/blob/main/CONTRIBUTING.md)获取更多信息。

##我的数据如何被使用?

你的数据不会被第三方共享, 更多详情请参阅 [privacy policy](https://github.com/seriaati/hoyo-buddy/blob/main/PRIVACY.md)页面。

## Hoyo Buddy 是开源的吗？

是，Hoyo Buddy 是开源的。你可以在 [GitHub](https://github.com/seriaati/hoyo-buddy/) 上查看源代码，在使用时请遵守 [授权许可](https://github.com/seriaati/hoyo-buddy/blob/main/LICENSE)。

### 我能自行架设 Hoyo Buddy 吗?

虽然具备技术能力即可自行架设 Hoyo Buddy，但开发者不会为自行架设提供协助。另外，出于版权原因，Hoyo Buddy 使用的资源已被锁定在私人仓库中，这意味着你自行架设的版本将无法通过图片生成功能（除了 /profile 的第三方卡片模板）。

## 为什么按钮或选项无法点击？

为了节省资源, UI元件（比如按钮）会在10分钟后过期。 避免混淆，元件在过期后被禁用。

## 试图用邮箱与密码方法添加账户时出现“Too many requests”错误

大多数情况下，该问题是暂时的，请在30分钟后重试。若问题依旧，你的账户可能已被“软锁” ，请仔细阅读以下指南。(注：有用户报告说等待5天后账户自动解锁。)

1. 首先，切勿重置密码，这无法解决问题，反而会使情况更糟糕。

2. 其次，请停止在HoYoLab/Hoyo Buddy/游戏内使用邮箱/用户名与密码尝试登录。

你是否仍然登录游戏（如原神、绝区零等）？

- 是：首先, [发送电子邮箱给客服](#sending-an-email-to-the-customer-service)。 然后尝试使用[开发者工具](#logging-in-with-devtools)或者[改用邮箱而非用户名](#logging-in-with-email-instead-of-username)登录 Hoyo Buddy。

- 否：请参考[尝试登录游戏](#trying-to-login-into-your-games)。

### 用邮箱登录而非用户名

有用户发现，如果你之前一直使用用户名登录，改用邮箱可以绕过此错误消息。同样的，如果你一直使用邮箱登录，尝试使用用户名登录。

### 使用开发者工具登录

如果你有台式/笔记本电脑，可以使用开发者工具方法登录，该按钮位于邮箱与密码选项旁边。使用此方法，你将无法使用某些功能（如自动兑换码）。

### 尝试登录游戏

你的 Hoyoverse账户是否绑定了任何社交软件（如Google、X等）？

- 是：用绑定的社交媒体登录游戏。然后，[发送电子邮箱给客服](#sending-an-email-to-the-customer-service)。接着，尝试使用[开发者工具](#logging-in-with-devtools)或[改用邮箱而非用户名](#logging-in-with-email-instead-of-username)登录 Hoyo Buddy。
- 否：请参考以下内容。

你是否已经登录[Hoyoverse用户中心](https://account.hoyoverse.com/)？

- 是：将你的账户绑定到一个社交媒体当中，然后使用该社交媒体登录游戏。接着，[发送电子邮箱给客服](#sending-an-email-to-the-customer-service)。然后尝试使用[开发者工具](#logging-in-with-devtools)或 [改用邮箱而非用户名](#logging-in-with-email-instead-of-username)登录Hoyo Buddy。

- 否: 尝试 [这个方法](#logging-in-with-email-instead-of-username)，如果还无法解决，请[发送电子邮箱给客服](#sending-an-email-to-the-customer-service)并耐心等待回应。目前，你可能无法访问游戏账户。

### 发送电子邮箱给客服

邮箱地址: [hoyolab@hoyoverse.com](mailto:hoyolab@hoyoverse.com)

范本:

```
你好，

我无法通我的邮箱和密码登录HoYoLab，当我尝试登录时，总会显示“请求过多，请刷新页面后重试”（如下面截图所示）。我已经等了8个多小时，问题依旧。请客服帮忙解锁下我的账户，我将会感激不尽。
我的邮箱是<你的邮箱>
(附错误记录的截图)
```

##为什么兑换码功能仅限于使用邮箱与密码登录的用户？

Hoyoverse 使用一种特殊的 Cookie，叫 `cookie_token`，用于兑换码操作，但时效性非常短。`cookie_token` 仅在兑换码功能使用，所以这就是为什么其他功能仍正常运行的原因。当用户使用邮箱和密码登录时，会收到一个名叫 `stoken` 的特殊 Cookie，可以用来刷新 `cookie_token`，因此该功能仅限于此类登录方式的账户。

## 为什么登录看不到我的账户？

### 邮箱和密码登录方法

请确保你使用的登录账密与游戏中使用的相同。

- [我用第三方登录方式（Google，Facebook等）](./Before-Start.md#i-login-with-3rd-party-services)
- [我是主机玩家](./Before-Start.md#i-am-a-console-player)

### 开发者工具方法

请确保你在HoYoLab使用的登录账密与在游戏中的相同。 例如，如果你在原神中使用Google账户[a@gmail.com](mailto:a@gmail.com) 登录，那么请使用该Google账户[a@gmail.com](mailto:a@gmail.com)登录HoYoLAB。

如果你看到重复的Cookie项目，请尝试使用隐私模式（无痕模式）窗口进行登录。

##为什么会出现“该交互失败”错误？

大多数情况下，这是由于机器人重启（应用代码更新）引起的，只需重新输入指令即可。然而，如果该问题依旧发生，意味着可能存在问题，你应该在[Discord 服务器](https://link.seria.moe/hb-dc)回报错误。
