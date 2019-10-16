{{indexmenu_n>2}}

# 木马检测

uhids自主研发的木马检测功能，拥有代码分析、数据流分析、异常网络流量分析等多种检测手段，使用云端大数据分析和静态规则相结合的检测体系，能够发现常见的php、jsp等网站后门。

## 检测原理

uhids会检查服务器上特定目录和进程情况，来判断是否存在木马，如果存在则会告警。

## 检测周期

默认每个小时检测一次。

清理风险后，1小时内会对该风险再次检测，如果发现风险已经修复，会自动删除该条告警。

### 检测项

Webshell 木马文件