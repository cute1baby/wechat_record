# wechat_record
小程序实战记录的一些笔记，包含登录和一些实用技巧


# 小程序登录实战
### 我们可以用openid来标识用户的唯一性,session_key能保证当前用户进行会话操作的有效性。且session_key是微信服务端给我们派发的。

>* 通过wx.login({})获取code
>* 通过appid、secret、js_code、grant_type获取openid和session_key.
>* checkSession进行检查storage中是否存在skey ？ 检查登录是否过期 : login()

[参考链接](https://juejin.im/post/5ac9b72cf265da23906c486a)
