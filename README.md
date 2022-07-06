<p align="center">
    <img src="https://yinduogw.oss-cn-shanghai.aliyuncs.com/static/modules/cms/images/banner.png"  alt="yshop_banner"/>
</p>

<h1 align="center">Yshop 商城框架系统</h1>


## 介绍
Yshop（简称 YS）是一套基于 ThinkPHP6.0 框架开发的高性能开源商城框架系统，秉承极简、极速、极致的开发理念，采用前后端分离，支持分布式部署。框架内部使用面向对象模块化调用，在多个终端、跨平台时采用 REST API 进行数据交互，可直接对接 PC、移动设备、小程序、云部署，构建 Android、IOS 的 APP。

**Yshop**

## 预览
[后台 Demo 预览](https://demo.yshop.yunyingbao.net/admin "后台 Demo 预览") | [RestAPI 接口调试](https://demo.yshop.yunyingbao.net/api "RestAPI 接口调试") | [经典配套款](./white/) | [深灰商务款](./gray/)

## 文档
[文档中心](https://doc.yin-duo.com "Yshop文档中心")

## 生态
Yshop 后台管理模板 

Yshop Rest接口调试 

## 功能
* 微信公众号
* uniapp小程序
* 数据统计
* 重构至ThinkPHP6.0
* REST API内置调试工具
* 商品管理
* 商品分类
* 商品品牌
* 商品模型
* 商品规格
* 商品属性
* 商品评价
* 内置商品预览
* 商品咨询
* 购物车
* 我的足迹
* 我的收藏夹
* 订单管理
* 订单详情
* 订单导出
* 订单打印
* 订单退款
* 退款日志
* 售后管理
* 售后详情
* 满额包邮
* 商品折扣
* 订单促销
* 优惠劵管理
* 优惠劵发放
* 购物卡(充值卡)管理
* 购物卡(充值卡)使用管理
* 会员账户
* 会员账户资金(可充值)
* 会员提现账户
* 会员收货地址
* 会员等级折扣
* 交易结算日志
* 积分发放兑换机制
* 提现管理
* 问答列表
* 内置后台消息通知体制
* 广告位置
* 广告列表
* 文章管理
* 文章分类
* 专题管理
* 资源OSS管理
* 资源OSS样式管理
* 客服模块
* 配送轨迹模块
* 友情链接
* 二维码模块
* 条形码模块
* 管理组人员管理
* 操作日志
* 用户组
* 菜单管理
* 权限规则
* 系统配置管理
* 前台导航
* 支付模块
* 支付日志
* 支付原路退回
* 区域管理
* 快递公司管理
* 配送方式配置
* APP 应用管理
* APP 安装包
* 短信消息
* 邮件消息
* 接口批量调用

## 安装
必须将项目下的`public`目录设为`web访问`目录，第一次访问首页时会进入`安装向导`，务必请通过向导完成安装。

## 快速启动
切换到项目根目录，在命令行输入`php think run -H 127.0.0.1 -p 8080`，启动 PHP 自带的`webserver`服务，  
按键`Ctrl + C`退出服务。

> 建议使用`IP`启动，避免使用`localhost`，并且此方法只适合调试环境。

## 常见问题
- 如何隐藏`index.php`入口文件?  
建议采用`PATH_INFO`访问地址，隐藏入口文件可做伪静态，请参见：  
[https://doc.yin-duo.com/guide/rewrite/](./rewrite/)

#### 声明
Yshop 使用 AGPLv3 开源协议，请遵守 AGPLv3 的相关条款，商用需进行授权，

本项目包含的源码（包括第三方）和二进制文件存在版权信息另行标注的情况。
