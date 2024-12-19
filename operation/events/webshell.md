

# Web木马检测

![](/images/operation/events/webshell.png)

表1.Web木马检测列表参数

|参数|说明|
|---|--|
| 资源地址  | 主机的IP地址,如果没有外网IP则显示为内网IP以及云上资源ID      |
|威胁路径|指的是Web木马所在的路径位置|
|威胁类型|描述Web木马的种类|
|风险级别|当前事件的风险级别,分: 高、中、低三种级别类型|
|处理建议|提供的木马风险解决建议|
|发现时间|指第一次发现安全隐患的时间|
|更新时间|指最近一次发现安全隐患的时间|
|处理状态|表示处理的状态，包括「未处理」和「已忽略」。如果已经处理了风险，则下次检测时将删除此风险信息。|

**Web木马详情**

显示web木马描述和如何处理Web木马的建议等。

**Web木马的检测原理与检测周期**

[Web木马的检测原理与检测周期](/security/uhids/function/WebShell)