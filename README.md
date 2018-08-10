FJWFM
=================================================================================================
# TNS
```
FJWFM =
  (DESCRIPTION =
    (ADDRESS = (PROTOCOL = TCP)(HOST = 134.128.52.106)(PORT = 1521))
    (CONNECT_DATA =
      (SERVER = DEDICATED)
      (SERVICE_NAME = fjwfm)
    )
  )
```
# om_oss/om_oss

IM的FTTX-LITE
=================================================================================================
# TNS
```
(DESCRIPTION =     (ADDRESS_LIST =       (ADDRESS = (PROTOCOL = TCP)(HOST = 134.129.68.15)(PORT = 2015))     )     (CONNECT_DATA =       (SERVICE_NAME = zhzytestdb)     ) )
```
# fttx_im/gxlufttx_im
# ftth_door/ftth_am
* TNS
```
(DESCRIPTION =
    (ADDRESS_LIST =
      (ADDRESS=(PROTOCOL=TCP)(HOST = 134.129.68.197)(PORT = 1521))
    )
    (CONNECT_DATA =
      (SERVICE_NAME = cmdb)
    )
)
```

197
=================================================================================================
# TNS
```
cmdb =
(DESCRIPTION =
    (ADDRESS_LIST =
      (ADDRESS=(PROTOCOL=TCP)(HOST = 134.129.68.197)(PORT = 1521))
    )
    (CONNECT_DATA =
      (SERVICE_NAME = cmdb)
    )
)	
```
# sd_fttx_im/gxlufttx_im  \\ 种子库
# fttx_im/gxlufttx_im	  \\ 测试库 

# 中文正则
* ^((?!(\*|//)).)+[\u4e00-\u9fa5]

User
=================================================================================================
# SOM
* ssh -p 2200 gxluguokq@134.130.136.8
* gxluSrm.123

# [80](134.128.52.80)
*  userName: sa
* passWord: admin789

# ccs
* zhangwei03
* gxluSrm.03

# RTX
* gxluzhangwg
* zhangwei

# url
* [补丁列表](http://134.128.52.80:8283/confluence/dashboard.action)
* [工时](http://172.17.11.182/cas/login?service=http%3A%2F%2F172.17.11.98%3A8080%2Fhome.jsp)

# IP
* 134.128.52.120
* 134.128.52.111
* [DNS](134.128.34.50)


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

# 通用查询
```java
var data = []

var request_url = "commonSearch.html" + data
var iframe = openIframeWin("", 1000, 600, request_url, "Search");
iframe.onload = function() {
    iframe.setParentObj(self);
}

function winReturnInfo(returnData) // returnData就是选中行的json
{
    if (null == returnData) {
        returnData = "";

    } else {
        // returnData.name.Name
    }
}
```
# [参考](/SRMWeb/mmeappweb/easyui/casetool/ommonSearchQueryFiberCoreByLinkBundle.ftl)

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





楼宇库回退内容
===================================================================
# VerificationBuildFragment2
* showSelectAddressCode
* labelBtn.setOnClickListener

# WebActivity
* 

















