Glassware 发布规范
==========

> #### 关于本文档
>
> - **Glassware** 是 Google Glass 应用的专有名词
> - 这是 Glassware 的开发规范，只有符合规范的 Glassware 才能上架官方的 MyGlass 推荐
> - 由于文化和理解上的差异，译文中难免存在纰漏，望各位提出宝贵的意见
> 
> #### 关于我们
>
> 我们（BestApp/BestNG）是国内第一支从事 Glassware 开发的团队，致力于 Glassware 的开发和 Glass 的本土化工作，同时尽可能向社区回馈我们的研究成果和新鲜好玩本土 Glassware。
>
> 更多信息请移步 [GlassX](http://www.glassx.cn/)，欢迎加入到我们的行列。
>
> - 翻译：[Jason Wu](cn.jason.wu@gmail.com)(BestNG)
> - 校对：[XiNGRZ](chenxingyu92@gmail.com)(BestNG)
>
> 原文地址：https://developers.google.com/glass/distributing/checklist

## 图片素材

### 提供 20x20 / 30x30 / 40x40 / 50x50 / 150x150 规格的来源图标

Glass 会在您的时间轴卡片的不同位置以不同大小显示您的图标，一边让用户知道时间轴卡片的来源。请确保您的图标：

- 代表您的品牌
- 除了大小外保持一致
- 白色内容、透明背景，便于 Glass 在不同场景下的展示
- 每个图标完全填满所要求的尺寸

以下是 Glass 使用您的图标的几种形式：

#### 20x40 / 40x40，以你的[标志色](#提供一个标志色)为底色	

![20x20 图标](https://developers.google.com/glass/images/icons/g-20.png)
![40x40 图标](https://developers.google.com/glass/images/icons/g-40.png)

#### 30x30，位于时间轴卡片底部

![30x30 图标](https://developers.google.com/glass/images/icons/g-30.png)

#### 50x50，位于「ok glass」触控菜单

![50x50 图标](https://developers.google.com/glass/images/icons/g-50.png)

#### 150x150，用于激活 Glassware 时发送给您的用户的卡片

![150x150 图标](https://developers.google.com/glass/images/icons/g-150.png)

### 提供 40x40 和 85x85 像素的展示图标

MyGlass 网站会在多个地方向用户展示您的品牌标志，请确保您的图标：

- 代表您的品牌
- 除了大小外保持一致
- 主体彩色，背景为白色或透明

### 提供一个 640x360 卡片图标

MyGlass 会使用该图标和您的 Glassware 名称、20x20 图标以及您的[标志色](#提供一个标志色)一同创建一张用于在 MyGlass 展示的卡片。

#### 原始图标

![原始图标](https://developers.google.com/glass/images/icons/g-640-360-tile.png)

#### MyGlass 卡片

![MyGlass 卡片](https://developers.google.com/glass/images/icons/tile-with-icon.png)

### 提供一个标志色

Glass 使用这个颜色来在不同场景展示您的 20x20 和 40x40 标志。颜色必须为十六进制（比如 #556677）。

### 提供 Glassware 的截图

为了向用户展示您的 Glassware 是怎么使用的，您需要提供一张 Glassware 的截图，以及截图所展示的情景的一个例子。MyGlass 将结合两张图片来创建一张插图，作为您的 Glassware 的截图。

- 情景图片必须为 2528x1856 像素，也就是 Glass 相机的分辨率
- Glassware 的截图必须为 640x360 像素，也就是 Glass 的显示分辨率
- 你必须提交一至五张插图

#### 情景图片和 Glassware 截图

![情景图片](https://developers.google.com/glass/images/icons/context-640.jpg)
![截图](https://developers.google.com/glass/images/icons/traffic.png)

#### MyGlass 的最终插图，已裁剪下半部分

![插图](https://developers.google.com/glass/images/icons/vignette-640.jpg)

## 商标

### 避免单独的时间轴卡片上出现多余的标志

Glass 会自动在时间轴卡片底部显示您的 30x30 像素的标志

### 写一个好的 Glassware 描述

Glassware 的描述将出现在 MyGlass 网站上，并告诉用户您的服务是干什么的：

- 提供您的 Glassware 的一句话简短描述
- 提供您的 Glassware 的一段稍长、不多于 800 字的描述。MyGlass 会将该描述作为更多信息显示在您的 Glassware 上。请勿重复之前的简短描述。
- 表明该 Glassware 是干什么的，以及任何只有 Glass 才有的特性
- 不要包含任何关于 MyGlass 或 Glass UI 使用方式的文字
- 如实描述您的 Glassware 的功能
- 不要包含未注册商标的宣传材料
- 使用「Glassware」指代为 Glass 设计的软件，而不是「app」

### 遵守 Glass 商标指引

你的 Glassware 应当遵守 [Glass 商标指引](https://developers.google.com/glass/brand-guidelines)。

## 设计

### 遵循卡片标准

- 尽可能使用[模拟器](https://developers.google.com/glass/playground)上提供的模板
- 如果您使用自定义 HTML：
  - 确保您遵循[标准边距要求](https://developers.google.com/glass/ui-guidelines#displaying_your_own_custom_html)
  - 对大于 30 像素的文本（主要内容）使用 Roboto Thin 字体，对小于或等于 30 像素的文本（底部）使用 Roboto Light 字体
  - 使用[标准 Glass CSS 文件](https://mirror-api-playground.appspot.com/assets/css/base_style.css)中提供的颜色

### 保持底部中间空白

**ok glass** 上下文语音菜单会出现在底部区域的中间，并挡住它后面的任何内容。

![ok glass](https://developers.google.com/glass/images/glass-screens/contextual-voice.png)

### 不要一张固定的时间轴卡片作为 Glassware 的启动入口

如果您需要一个新的语音指令来解决这个问题，请[提交请求](https://services.google.com/fb/forms/glassvoicecommand/)。

## 内容

######尽可能使用图片而不是文字
如果可能，使图片全屏(640x360像素)或左列(240x360像素)代替文字。图片应保持原有的宽高比例。
######保持信息简洁
每个卡片显示一小块相关信息方便查看
######不要重复发送timeline items
不要太频繁更新.Glass 发送定期更新应该保持一致的值
######遵循媒体格式要求
* 所有公共视频都是事件流,不要附加到timeline items
* 视频的比例是16:9
* 视频分辨率是640x360像素
* 视屏格式: 视频容器:MP4。视频编码:H.264 和 H263。音频: AAC 和MP3

####菜单
######创建合适的菜单图标以及文字
* 图标是完全白色或者透明背景
* 使用50x50像素和描述执行的行为
* 使用[Glass menu icons](https://developers.google.com/glass/downloads/menu-icons-50.zip)如果你想符合GlassUI标准
* 使用简短和可操作的菜单项的显示名字，动词祈使句看起来很棒，像以下例子
![menu item one](https://developers.google.com/glass/images/glass-screens/google.png)
![menu item two](https://developers.google.com/glass/images/glass-screens/take-a-picture.png)
![menu item three](https://developers.google.com/glass/images/glass-screens/record-a-video.png)

#####避免没有明确使用的删除菜单
删除是可以接受的如果有相关Glassware操作(比如:照片分享).如果你使用删除，在Glass上删除timeline项和在你的服务器上进行相关操作

####集合和分页
######适当得使用包
* 使用类似卡片组但不应该是一样的卡片，例如，使用集合为一组新闻故事在一个小时内或者一组体育成绩
* 设计简要集合封面卡片，视觉上包含不同来自集合内的卡片内容
* 每个集合通知用户的通知声音只有一次

######正确地使用分页
* 适当地使用内容分页因为空间限制所有内容不适合显示在一张单独的卡片上.例如：使Email或者新闻故事分页，跨越多个卡片

####分享联系人
######尽可能创建一个简要的描述在分享联系人的时候
* 省略冗余的信息在分享联系人时所显示的，如你的品牌名称
* 为联系人创建一个丰富的图片，图片像素为640x360像素。
* 如果分享多个联系人，确保他们在逻辑上是不同的，可区分的

######添加适当的元数据在共享内容的时候
* 添加“throughglass“”分类共享内容
* 在从Glass分享内容的时候添加"Sent through Glass"，不强求分类

#####适当声明内容的MIME类型
你的联系人有可能不能接受所有类型的内容，声明你的联系人有效的支持类型和‘[acceptTypes](https://developers.google.com/glass/reference/contacts#acceptTypes)'属性

####网站
如果你的Glassware和产品有一个相关的网站，请遵循以下指导标准
* 使用 [Send to Glass](https://developers.google.com/glass/downloads/send-to-glass-buttons.zip) 图标如果从网站上推送内容到Glass
* 确保正确地语法和拼写
* 如果提供 "More info"链接在MyGlass上，链接到网页和Glassware的特定信息例如Glassware的支持或者提示，不要链接到通用产品信息
* 在你的网站上不提供Glassware的取消授权，取消授权只能是在MyGlass上.

####Glassware 设置

提供简单的方法调整和授权Glassware

######提供简操作的授权流程
* 不要有超过两个的授权或者登陆界面
* 设置在一个合理的不需要重复授权的时间范围(小于三个月)
* 如果一个账号和相应的应用程序是不许的，对于那些没有你的服务账号的用户来说，授权流程必须是清晰的。
* 授权链接地址必须和设置链接地址是不一样的
* 如果一个用户账号是必学的，Glassware必须不验证用户没有链接到用户账号(这句表示不懂)

######提供条例清晰有用的设置
* 设置改变保存的时候提供良好的视觉表明
* 显示更新的频率和订阅数量。下面截图是一个例子，允许用户设置更新时间频率和订阅类型

![cnn](https://developers.google.com/glass/images/cnn-settings.png)










