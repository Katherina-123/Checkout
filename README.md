# Checkout
小凯账本APP，安卓端，个人的课程设计


## 需求分析
小凯账本APP是为了解决用户快捷方便记账的一款APP，所有的核心功能都是围绕记账展开，目的是为了简化方便记账流程，所以该APP的基本功能需求如表所示。

|功能|说明|
|:------|:--|
|添加账单分类|账单分为收入和支出两类，具体在向下细分为用户自定义账单的分类，例如工资、红包等收入和购物、饮食等开销支出。用户自定义的账单分类需要用户根据自己的具体需求来添加和更改，方便用户在记账的过程当中能够更加清晰快捷的定位自己的账单归类。
|账单的增删查改|账单的增删查改是该APP的核心要素，在开发这一块需要对于用户的操作体验流程做一个详细的规划，让用户可以用最简单，操作次数较少，体验过程较为流程的情况之下对自己账单进行操作管理。当然在数据库这一方面也要优化，保证APP的性能和流程。
|账单数据报表分析|用户除了可以看到自己的账单明细之外，该APP还需要提供一个报表给用户提供直观的数据分析，通过总结和分析用户近日的消费支出数据给用户以图表反馈，体现该APP的应用价值。
|语音备忘功能|相对于其他的记账APP，小凯账本还提供以语音备忘功能，该功能的应用场景在于用户在支出收入匆忙的环境下，没有充足的时间去记下自己的账单，通过语音备忘功能，用户只需在短短几秒的时间类通过单手的简单操作就可以将自己需要记录的账单以语音的方式保存下来，方便日后再去处理。
|云端备份功能|以上所有的功能都是不需要联网的单机环境下就可以完成的，使用的是安卓自带的SQLite本地数据库来存储数据的，但是用户总会有数据迁移的功能需求，将用户的数据备份到云端服务器上可以保证数据永不丢失，并且可以实现跨设备去同步自己账本，这可以增加用户的使用粘度，提升用户的使用体验。

## 框架

![](https://github.com/TONKIA/Checkout/blob/master/img/framework.png?raw=true)

## 页面UI

![](https://github.com/TONKIA/Checkout/blob/master/img/ui.png?raw=true)

## 明细页

![](https://github.com/TONKIA/Checkout/blob/master/img/detailui.png?raw=true)

## 录音功能

![](https://github.com/TONKIA/Checkout/blob/master/img/record.png?raw=true)

## 三方引用
- bumptech/glide
- AlexLiuSheng/BadgeView
- akexorcist/Android-RoundCornerProgressBar
- ws123/VoiceLine
- lecho/hellocharts-android
- shaohui10086/BottomDialog
- armcha/Space-Navigation-View
- LitePalFramework/LitePal
- square/okhttp
- hdodenhof/CircleImageView
- niniloveyou/StateButton
