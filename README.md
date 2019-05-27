
# 中文正则
* ^((?!(\*|//)).)+[\u4e00-\u9fa5]

PATH
=================================================================================================
* echo "export PATH=$PATH:url" >> ~/.bashrc
* source ~./bashrc

# 进程管理
* msconfig

JAVA JS
=================================================================================================
# MQL统计总数
```java 
InstanceQueryParam pa = InstanceQueryEngine.compile(MQL);
pa.setContainsDate(true);
count = InstanceQueryEngine.count(pa);
```
# 消息窗口
* [layer](http://layer.layui.com/)
* /SRMWeb/mmeappweb/easyui/views/include.js ddrivetip()

jboss
======================================================================
# [WebService 端口](JBOSS_HOME/server/default/conf/jboss-service.xml)
* 原端口: 8083 --210行， 具体看实际情况
* name="jboss:service=WebService"

# [JNDI端口](JBOSS_HOME/server/default/conf/jboss-service.xml)
* 原端口: 1099 --251行，具体看实际情况
* name="jboss:service=NAming" xmbean-dd="resource:xmdesc/NamingService-xmbean.xml"

# [RMI端口](JBOSS_HOME/server/default/conf/jboss-service.xml)
* name="jboss:service=invoker,type=jrmp"
  * 原端口: 4444 --426行，具体看实际情况
* name="jboss:service=invoker,type=pooled"
  * 原端口: 4445 --450行， 具体看实际情况

# [HTTP端口](JBOSS_HOME/server/default/deploy/jbossweb-**.war/server.xml)
* HTTP端口: 8080 --22行
* HTTP端口: 8009 --39行

# [JMS](JBOSS_HOME/server/default/deploy/jms/uil2-service.xml)
* 原端口: 8093 --22行

问题
================================
# 号线互查
* 帐号查询两次
  * 解决，蛋疼的不知道怎么写到了td里面
* Acc页卡输入框位置不对（选中radio和实际能输入的位置不同）
* 展示的tab少了(暂时不管)

# 地址管理
* 删除没有刷新
* 批量修改没有刷新


楼宇库回退内容
===================================================================
# VerificationBuildFragment2
* showSelectAddressCode
* labelBtn.setOnClickListener

# WebActivity
* 

扫描标签查看设备增加基本属性和资产编码校验
=================================================================
# ResponseTCASServiceImpl

86170069

/SrmMobileAppFj/src/com/gxlu/fj/rm/service/configuration/link/MainModifyFiber.java 存在问题





