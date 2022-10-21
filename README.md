# Digitization Strategy:
目标：使用技术/数据
- 助力业务成交；
- 提升团队效率；
- 减少交易风险；

## SECTION 1 :  Projects Existing: -- enhancement
### Phase i 
- 字段的增加优化 和 minor bugs
	>maintain: 50k RMB
### Phase ii
- 新业务场景的加入，如：
- 对内、对外定制化；
	>maintain:50~100k RMB
	>license: 50k RMB

## SECTION 2 : Project Researching :
### phase iii
-	**企业 投保风险识别：**
	> 通过外部企业信息接口汇聚信息，结合银行的一些企业风险模型，通过打标后通过机器学习，输出给梧桐树等其他；
-	**买数据:**
	> 行业/公开数据 
	  国家卫生健康委员会、国家医疗保障局、中国保险业协会数据、CIA World Factbook、世界卫生组织委员会、世界银行、人民银行数据
	> 百万医疗数据、团险数据等
	> -->vendor: 通联、万得、朝阳永旭 ;--> Aon H&B team；
-	**数据预测->精算评估自动化:**
	> CI 经验分析 -- in progress
	> MM 经验分析 -- to be researched, more data to be collected
-	**MKT:**
		[咨询公司](https://pdf.dfcfw.com/pdf/H3_AP202101071448331614_1.pdf?1610032066000.pdf)  --> survey
		internal report --> dashboard development
	
-	**CRM system:**   for 信息共享, No 枷锁； 
	>**1.  parnters (insurer / reinsurer /channel) management**
	>业务偏好，喜欢做啥不喜欢做啥(tag) & key person/contact

	>**2. 业务机会(pipeline & treaty)管理：**
	```mermaid
	graph LR
	A[BD] --> B((Placement))
	B --> C(Operation)
	```

	|Team      | Function|
	|----------|----------|
	|BD        |  产品描述和属性(tag) |
	|Placement |根据tag推荐RFP模板和再保市场|
	|          |system track record mail / key stage|
	|          |remind|
	|Operation |treaty information(合约日期等)|
	|          |sales volume record;|
	|          |续期提醒;|

	>**3. documentation management**

	>**BD**: (raw files: 产品需求、条款等)；

	>**Placement**: (RFP\final RI Terms\Experience data & rate level table)

	>**Operation**: (Slip\Bordereau)
		
### SECTION 3: Others : use technology to helps teams;
	收件人组等；
	数据清洗的自动化流程以及需求梳理 ;
	数据清洗流程规范化和数据问题管理 ;
	数据安全路径:bordereau\理赔材料的脱敏等;
