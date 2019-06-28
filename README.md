## 云象册项目说明

云象是一个开源的个人云相册服务，它利用你的路由器和移动硬盘搭建一个可供互联网访问相册服务，提供手机相册同步、图片上传、提取码分享等功能。由于它使用的是你个人的路由器带宽（大多数是家庭的）和个人的移动硬盘，所以你不需要为云服务支付任何费用。市面上常见的云服务，比如小米云 1T1年费用是499元。

由于云象是一个刚刚开始的项目，很多功能并不完善，所以欢迎有兴趣的程序猿加入一起捣鼓。



### 模块说明

基于有USB口能外接硬盘的智能路由器开发个人云相册服务。

```markdown
用户系统（暂时不开源）

主要功能
1. 用户注册、短域名，用户可以注册3个字母以上的短域名，比如：abc.dir.ink
2. 提供DDNS服务，由于家庭宽带没有固定IP，只能通过DDNS实现短域名到家庭IP的映射
3. 提供目录分享和提取码功能

# 用户系统会提供API接口供云相册服务调用
```


[云相册系统（开源）](https://github.com/brightman/dumbo/blob/master/client/readme.md?raw=true)

1. 手机相册同步功能
2. 云相册的浏览功能
3. 云相册的分享功能



# 云相册系统会提供API接口供APP调用


```markdown
云相册APP（开源）

1. 手机相册同步功能
2. 云相册的浏览功能
3. 云相册的分享功能

# iOS
## Android
### 小程序

- Bulleted
- List


**Bold** and _Italic_ and `Code` text

[Link](url) and 

```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### 加入该项目

1. 我们需要iOS/Android/小程序的开发人员，我们不会向你支付费用，但会把你的名字列在项目中
2. 我们需要电子相框的生产厂商进行合作，我们会支付开模和生产费用。

### 联系我们

请在这篇微信文章或公众号留言[联系我们](https://mp.weixin.qq.com/s/Sq57dbQnC8IxvhaDSclXIQ)
