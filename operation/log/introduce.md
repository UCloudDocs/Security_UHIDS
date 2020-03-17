
日志：
## 日志记录内容
支持的查询日志包括：进程启动的实时日志、外主动连接的实时五元组日志、系统登录成功的流水、账号数据快照、端口监听快照、
支持10TB日志存储空间，日志保存6个月。
支持多日志源关联、时间周期自定义查询，支持查询数据的导出，存储查询条件，便于多次快速查询

**进程快照日志**
| 字段 | 描述 | 范例 |
| --- | --- | --- |
|进程名  | 进程的exe名字 | ps |
| pid | 进程id | 12345 |
|md5| 进程exe对应的md5| 8d499a7a53b0277e7e4dc7fb577da767|
|cmdline| 进程启动的命令行| ps -ef|

**网络日志**

| 字段 | 描述 | 范例 |
| --- | --- | --- |
| 源ip | ip协议的源IP | 1.1.1.1 |
| 源端口 | ip协议的源端口 | 12345 |
| 目的ip | ip协议的目的ip | 2.2.2.2 | 
| 目的端口 | ip协议的目的端口 | 80 |
|传输层协议| 传输层协议| TCP |

**登录成功的流水日志**
| 字段 | 描述 | 范例 |
| --- | --- | --- |
| 账号 | 账号名字 | root |
| 源ip | 登录发起的ip | 1.1.1.1 |
| method | 登录方式 | password | 

