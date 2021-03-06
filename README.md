#  **简历**

## 个人信息

姓 名：张山海 <br>
手机： 18811413070 <br>
性 别： 男<br>
出生日期： 1989年11月30日 <br>
居 住 地： 北京-昌平区<br>
工作年限：6年<br>
qq：707582070<br>
户 口： 河北唐山<br>
期望薪资：30k
职业发展发现：技术专家方向


## 教育经历

2009.09 - 2012.06  河北工业大学 计算机网络(专科)

## 工作经验


#### 掌众金融服务有限公司
2017.12 - ：<br><br>
所属行业： 互联网金融<br>
部门：研发部<br>
公司简介：
> - 一家互联网p2p金融公司
> - 掌众财富，闪电借款等产品。
> - https://www.weshare.com.cn/



#### 北京联创科技有限公司
2016.12 - 2017.12 ：<br><br>
所属行业： 互联网<br>
部门：---<br>
公司简介：
> - 自主
> - 一个内容分享网站 [10万加](https://100000p.com)。
> - [app地址](https://itunes.apple.com/cn/app/id1348577356)


#### 掌游天下
2015.1 - 2016.12：<br><br>
所属行业： 手游、互联网广告<br>
部门：玉米广告，自主广告研发平台<br>
公司简介：
> - 公司以手游为主。广告是游戏变现的一种方式。
> - 广告部门分为 聚合广告和**自主研发**。
> - [玉米移动](https://www.yumimobi.com/)



#### 北京维旺明科技有限公司
时间：2012.07 - 2015.01<br>
所属行业：互联网新闻app<br>
部门：服务器组<br>
公司简介：
> 公司已在线阅读杂志，在线阅读咨询为主。
> 在APP上投放合约广告，已到达变现目的。当时统计已有8千万在线用户。
> [viva畅读app地址](https://itunes.apple.com/cn/app/id402641844)

## 项目经历


### p2p撮合协约平台
时间：2017.12 - <br>
担任角色： 开发<br>
项目描述：
> - 整体业务分为，理财，撮合，借款，风控，等。
> - 项目历时两个月。5人开发，1初级，2中级，我，teamleader（负责对外沟通），架构师（还款逻辑开发）。
> - 此项目为撮合交易。 根据政府文件，进行p2p贷款 合规改造。该系统是 借款人 和 理财人的撮合系统。
> - 理财业务端，借款业务端，将数据同步给撮合系统。撮合后，向银行发送打扣款命令。用户收到到卡通知后。返回给 业务端。
> - 还款逻辑（非本人开发）。
> - 迁移老数据到新系统存管银行

本人职责&具体工作内容
 - 项目立项
 - 需求评审
 - 在架构师的帮助下 设计系统。
 - 独自开发撮合核心代码。
 - 引导帮助同事，完成周边功能。例如 数据入库等。
 - 用到的技术有，spring boot，redis，rabbitMq，gradle。
 - 将30万借款订单 与 2万理财订单撮合交易后，同步迁移到新系统中。达到11亿资金一分钱不差。



### 10万加 内容分享平台
时间：2016.12 - <br>
担任角色： 联合创始人<br>
项目描述：
> - 灵感来源，某一领域的 意见领袖，经常分享有意义的文章到qq群或者微博，那么为啥不分类分享呢？
> - 创建 专集，将自己认为有趣的文章通过 web同时填写 url，标签，推荐理由，选择 专集 分享。
> - 类似 掘金、读读日报、google+、saas版本的 掘金日报

本人职责&具体工作内容：
- 功能市场调研，精益画布，需求整理，页面原型，交互原型设计
- 后端restful 风格 api文档编写，代码实现。
- 使用技术，spring boot，spring cloud
- 微服务 架构设计，方便以后添加api 和横向拓展。
- 小程序lite 代码编写。已经上架请在微信小程序搜索 【10万加】
- 通用文章正文内容抽取：用户分享url，后端接收后，抓取该网页，同时抽取正文内容，并将内容转为markdown 存入数据库。
- 微信公众号 文章爬取 程序改造编写。修改开源wechat_spider(go语言）以适应需求。
- 微信机器人编写。在wechat-robot 基础上改造。将文章内容分享给机器人后，它帮我推到默认收藏夹 同时展示在首页上。
- slack。事实通知服务器时间到聊天窗口


### 互联网广告平台
时间：2015.11 - 2016.12<br>
担任角色： 主程序员<br>
项目描述：
> - 自主研发为：sdk -> adserver->adexchange->dsp/api/
> - 直投dsp自主研发为：sdk -> adserver->adexchange->直投dsp

本人职责：
> - adserver 和dsp的 开发和线上运维 工作。
> - 每天日均2亿次请求，4000万 曝光。每天日均2亿次请求，4000万 曝光。
> - 晚间高峰期，保证99%的请求都能得到相应。

具体工作内容：
- 0.负责 ssp和dsp 的广告投放机
- 1.ssp平台，对现有已经离职团队留下的平台进行重写，优化性能
- 2.ssp对接sdk，**定义开发接口**。
- 3.根据 openrtb协议对接adx
- 4.ssp 支持常见的广告形式（原生，banner，插屏，开屏，视频）
- 5.ssp使用redis，存储广告 请求，上报pv，点击等信息，确保 顺序，在线初步防止作弊行为。
- 6.dsp 直投 ，将广告库在redis 内做**倒排索引**完成 **基础定向**。
- 7.**频次控制**，实时超量下线。排期上下线。
- 8.**平滑投放**功能。使用redis计数器，将 广告平滑的投放出去，避免前期投放过多后期下线。
- 9.使用**elasticsearch** 进行第三方物料分析。用于统计举报数量，屏蔽低俗图片
- 10.日常线上运维，使用awk，查找日志。
- 11.改造项目，将非maven改成maven，jenkins建设使系统自动化编译部署，大大节省开发时间
- 12.api 项目，对接三方广告接口api，返回给adx（dsp功能）
- 13.优化ssp系统性能，使用**guava**缓存，分析性能瓶颈代码，优化代码，jmeter显示系统性能提高将近10倍。
- 14.使用guava，在内存中统计 超时率，每分钟调整策略，限制流量 防止 对接 第三方api项目  因为http请求阻塞导致 性能下降。
- 15.优化jvm等。
- 16.提出技术解决方案


### 服务器端 初中级开发

时间：2012.07 - 2015.01 <br>

项目介绍
> - 杂志，资讯（cms），爬虫，广告，接口，客户端。
> - 蜘蛛抓取指定网站文章，图集入库，使用fudannlp对文章进行打标签。对标签分类管理，对文章修改。
> - 文章根据标签走，标签根据表情包走，用户订阅标签包，根据标签包，下发文章给客户端。

责任描述
- 管理面板的开发：调整文章，标注/过滤关键词，管理关键词，搜索词语，标签包运营等。
- 网页抽取正文工具。
- 编辑使用工具开发。
- 图片源抓取蜘蛛。
- 使用**dubbo**，开发查询文章，类目等接口服务给接口工程师。
- 合约广告系统开发。


## 个人技能
sql优化等，python，go语言，jvm 性能调优<br>
了解 devops，chatops <br>
了解 zookeeper

## 职业目标
- 想在计算机，互联网行业长期发展。希望从事互联网，移动互联网，计算广告等 后端工作
- 走架构师 技术路线。

## 自我评价

做不了web、前端等。
就会写接口。



## 特长

自学能力还好，喜欢新型的东西，喜欢研究。

最近研究区块链。

## 对公司/团队的 要求和 期望

要求：

互联网公司

期望：

公司有优秀的文化和 工程师文化开发文化，能够做到重复的事情不手动处理。需求，开发，测试 ，运维 流程完备的团队

技术栈 期望

spring mvc，jpa，go，git，jenkins，docker，slack，chatops，devops

## 熟练使用开源组件技能

spring 家族，docker，Jenkins，storm，elasticsearch，hotspot，mysql，redis，eth,eos,btc,fabric etc.

## 业余作品
[网络收藏夹](http://100000p.com)
[开发api](http://github.com/zhangshanhai/readthis-api)

![](http://p00001.oss-cn-hongkong.aliyuncs.com/app.png)
