## 个人简介
* 吴于康 | 1994年
* **15336200123** | 18836617@qq.com
* 陕西理工大学 | 本科
* 求职意向: **Python开发工程师** 

## 技能
* 熟练使用Python进行web开发
* 熟练使用Django model设计, 前端模板编写, view业务处理
* 熟悉Git版本控制
* 熟悉Linux基本命令
* 了解Python爬虫
* 了解Django REST framework
* 了解HTML, CSS


## 项目经验
### 1. 电商网站后台
项目采用前后端分离设计, 后端主要技术Django, Django REST framework, 联合Routers, Serializers, ViewSets功能实现接口开发, 每一个业务模块均有专门的接口及实现类. 数据访问采用Django ORM实现, 代码简洁,可适应不同数据库.

(主要负责后端接口实现)  

* 用户业务 
	* 实现登录,注册,个人详情,商品收藏接口 
	* 短信验证注册,对接短信服务平台API,正则匹配手机号非法性
	* 集成Django REST framework JWT登录认证
	* Django ORM验证用户是否存在

* 商品业务
	* 实现商品展示,商品分类, 商品详情
	* throttling控制商品列表API访问频率
	* Django-filters实现商品过滤功能
	
* 交易业务
	* 实现购物车,订单管理接口
	* 支付宝支付, 对接支付宝支付API

### 2. 在线教育平台
项目采用Django MTV模式, 定制xadmin后台管理系统.  
(主要负责后端业务逻辑, 前端模板代码)

#### 前台功能模块
* 登录 (Django自带登录验证)
* 邮箱验证
	* 注册 (发送激活链接邮件)
	* 找回密码 (发送重置密码链接邮件)
* 课程展示
	* 通过get请求返回的参数实现搜索,排序功能
	* 利用pure_pagination实现分页功能

* 热门课程推荐 (推荐学习人数最多的前3门课程)
* 用户收藏 (通过post请求判断用户收藏的类型, 用户是收藏还是取消收藏)

#### 后台管理系统

* 集成xadmin后台管理系统
* 定制xadmin样式
* xadmin注册所有model
* 自定义xadmin菜单顺序, 标题


## 其他

* GitHub: [https://github.com/Yokong](https://github.com/Yokong)
* Vim爱好者
