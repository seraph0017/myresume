# 徐楠的个人简历
===============

## 基本信息

* 性别：男
* 出生年月：1988/9/8
* 地点：上海
* 毕业院校：西北政法大学
* 学历：本科
* 爱好：健身、慢跑

## 自我总结
* 乐观向上
* 善于学习
* 不给自己打标签


## 工作经验

### 1. 互众广告/innotech/趣头条
* 职位：技术总监
* 时间：2015.7 - 现在
* 主要成果：
	- 孵化体系内部自建socket推送系统开发架构
	- 广告rtb系统开发
	- 运维自动化系统开发及架构
	- 多云平台开发及架构
	- 建设完整运维团队（10人）
	- 建设devops团队（10人+）
	- 建设测试团队（20人）
	- 敲定云供应商和多云平台等合作方案（阿里云4.5折等商务也敲定）

### 2. 晶赞科技
* 职位：报表开发/devops
* 时间：2014.8 - 2015.7
* 主要成果：
	- 广告系统报表研发，
	- 广告系统整套ci/cd体系搭建

### 3、favbuy
* 职位：后端开发
* 时间：2013.4 - 2014.7
* 主要成果：开发favbuy网站，并编写搭建整套ci自动化体系

### 4、美科颐康
* 职位：项目经理
* 时间：2009.7 - 2013.4
* 主要成果：完成长安医院无纸化系统


## 项目经验

### 1.  自建推送系统
* 描述：为了解决第三方推送数据粒度不够细等问题，自建socket推送系统为业务运营提供详细数据
* 负责模块：
	- 系统架构
	- bi系统设计
	- sdk集群搭建
	- 强壮性标准制定
* 备注：
	- 采用基于golang开发的自有长连接协议	
	- 过滤本打算使用广告系统的bitmap，但由于时间条件没办法做到全或无，采用es来做过滤
	
### 2.  广告系统
* 描述：主要是
* 负责模块：
	- 系统架构
	- 过滤模块开发
	- 报表开发
	- 第三方对接
* 备注：
	- 采用bitmap来做条件过滤，int64位id传输信息，用rsync来同步配置表

### 3.  运维自动化系统 v1/v2/v3
* 描述：主要是解决广告系统等高性能后台多机部署以及灰度发布，以及版本管理和回滚的问题，以及批量执行命令的问题 
* 负责模块：
	- v1/v2/v3版本系统架构：由python转golang 由ssh转自建agent
	- v1/v2版本后端开发 v3由于精力问题，转为架构
	- 产品设计以及优化方案
	- 微服务架构拆分
* 备注：
	- 采用二次开发的open-falcon代替了ansible的ssh协议增强了命令执行的安全性
	- 由python转为golang使用golang的channel代替了celery增强了稳定性
	- 管理节点1000个左右，同时并发数可配置，可按需调整服务重启间隔时间

### 4. 多云平台
* 描述：结合了阿里云，腾讯云，ucloud等云的操作，ui上合并统一
* 负责模块：
	- 架构方案设计 采用golang微服务框架gokit 配合jeager和promethues做metrics
	- ecs模块开发
* 系统亮点：解决了孵化项目云系统多元化的目标，方便适配各个云厂商的解决方案



## 孵化项目（10+基本都是方案设计参与）

### 1. 今晚八点半
* 描述：直播答题，采用腾讯的嵌入sdk

### 2.ubook
* 描述：小程序视频直播答题 


## 团队建设

### 1、运维团队：
* 10人左右运维团队，负责阿里云月销300W+的团队运维，配合平台团队搭建了稳定的商务渠道和自动化运维体系

### 2、平台团队：
* 8人左右开发短信平台，推送服务，多云平台等基础平台

### 3、测试团队：
* 在芜湖搭建了一个人数为20人左右的手工兼容性测试团队，为孵化项目提供手工兼容性测试支持，平台部门负责支持ci


## 技术栈

* python
	- flask
	- gevent
	- celery
	- ansible
* golang
	- gokit
	- echo
	- gin

## 联系方式

* 手机：18616708172
* E-mail:seraph0017@hotmail.com
