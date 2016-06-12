##CN
火力地堡验证快速入门
=============================

在火力地堡AUTH快速入门演示签署的几种方法。

在火力地堡电子邮件/密码，快速入门演示如何使用火力地堡存储的电子邮件和密码 - 你既可以创建并在用户登录。

在火力地堡谷歌登录快速入门演示了使用谷歌帐户进行身份验证使用三种不同的技术来火力点：带有弹出，重定向和身份验证令牌。

在火力地堡的Facebook登录快速入门演示使用Facebook帐户进行身份验证使用三种不同的技术来火力点：带有弹出，重定向和身份验证令牌。

在火力地堡GitHub的登录快速入门演示使用GitHub的帐户进行身份验证使用两种不同的技术来火力：有一个弹出式和重定向。

在火力地堡Twitter的登录快速入门演示使用一个Twitter帐户进行身份验证使用两种不同的技术来火力：有一个弹出式和重定向。

在火力地堡匿名身份验证快速入门演示验证匿名火力地堡。

在火力地堡定制的身份验证的Web快速入门演示了如何可以验证与谁一直从自己现有的预认证系统认证的用户火力地堡。这是通过在一个特定的格式，其使用从由谷歌开发者控制台下载服务帐户的私钥签署生成令牌完成。然后，这个标记可以传递给该用户使用它来验证火力地堡客户端应用程序。

介绍
------------

- [Read more about Firebase Auth](https://firebase.google.com/docs/auth/)
入门

设置您的火力地堡控制台项目 [Firebase Console](https://console.firebase.google.com).。
启用要在验证部分>登录方法选项卡中使用的身份验证方法 - 你不需要启用自定义身份验证。
在谷歌开发者控制台中，访问您在火力地堡控制台创建的项目[Google Developer Console](https://console.developers.google.com),。
对于自定义验证，也创造了在项目开发者控制台一个新的服务帐户，并下载JSON表示 [Developers Console](https://console.developers.google.com/apis/credentials/serviceaccountkey?project=_),。
对于Facebook，Twitter和GitHub上，你需要创建一个应用程序作为其开发者平台上的开发者，白名单的https：// <PROJECT_ID> .firebaseapp.com / __ / auth /中处理程序AUTH重定向和启用和设置应用程序的凭据在火力地堡控制台>验证>在方法的迹象。
编辑你想尝试，并从火力地堡控制台概述复制初始化片段>添加火力地堡到您的网络应用程序转换的.html的<head>部分的验证方法的.html。
运行火力使用火力地堡CLI工具来启动本地服务器，并在Web浏览器中打开示例的.html服务。

支持
-------

https://firebase.google.com/support/

License
-------

© Google, 2016. Licensed under an [Apache-2](../LICENSE) license.
##EN
Firebase Auth Quickstart
=============================

The Firebase auth quickstart demonstrates several methods for signing in.

The Firebase email/password quickstart demonstrates using a Firebase stored email & password - you can both create and sign in a user. 

The Firebase Google Sign in quickstarts demonstrate using a Google account to authenticate to Firebase using three different techniques: with a popup, a redirect and an auth token.

The Firebase Facebook Login quickstarts demonstrate using a Facebook account to authenticate to Firebase using three different techniques: with a popup, a redirect and an auth token.

The Firebase GitHub Login quickstarts demonstrate using a GitHub account to authenticate to Firebase using two different techniques: with a popup and a redirect.

The Firebase Twitter Login quickstarts demonstrate using a Twitter account to authenticate to Firebase using two different techniques: with a popup and a redirect.

The Firebase Anonymous auth quickstart demonstrates authenticate to Firebase anonymously.

The Firebase custom auth web quickstart demonstrates how to authenticate to Firebase with a user who has been authenticated from your own pre-existing authentication system. This is done by generating a token in a specific format, which is signed using the private key from a service account downloaded from the Google Developer Console. This token can then be passed to your client application which uses it to authenticate to Firebase.

Introduction
------------

- [Read more about Firebase Auth](https://firebase.google.com/docs/auth/)

Getting Started
---------------

- Set up your project on the [Firebase Console](https://console.firebase.google.com).
- Enable the authentication method you want to use in the Auth section > SIGN IN METHOD tab - you don't need to enable custom auth.
- In the [Google Developer Console](https://console.developers.google.com), access the project you created in the Firebase Console. 
- For Custom Auth, also create a new Service Account in your project [Developers Console](https://console.developers.google.com/apis/credentials/serviceaccountkey?project=_), and download the JSON representation.
- For Facebook, Twitter and GitHub you will need to create an application as a developer on their developer platform, whitelist `https://<project_id>.firebaseapp.com/__/auth/handler` for auth redirects and enable and setup the app's credentials in the Firebase Console > Auth > SIGN IN METHOD.
- Edit the `.html` for the authentication method you want to try and copy the initialization snippet from the Firebase Console **Overview > Add Firebase to your web app** into the `<head>` section of `.html`.
- Run `firebase serve` using the Firebase CLI tool to launch a local server and open the sample `.html` in a web browser.

Support
-------

https://firebase.google.com/support/

License
-------

© Google, 2016. Licensed under an [Apache-2](../LICENSE) license.
