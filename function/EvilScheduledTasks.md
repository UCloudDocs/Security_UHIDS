

# 恶意定时任务检测 
___

UHIDS自主研发的恶意定时任务检测功能，拥有恶意定时任务行为分析手段，通过使用云端大数据分析和静态规则相结合的检测体系,能够发现常见的黑客通过定时任务方式来隐匿、守护恶意进程木马。

## 检测原理

安装完成Agent客户端插件之后,UHIDS会自动在系统常见的定时任务启动目录、位置进行内容读取,读取到的内容进行数据分析,最终根据具体的任务行为进行恶意评定,输出告警通知.

## 检测周期

- 启动插件时默认每个2小时检测一次。
- 清理风险后，2小时内会对该风险再次检测，如果发现风险已经修复，会自动删除该条告警。

### 检测项

| 检测项    | 说明                   |
| ------ | -------------------- |
| Crontab定时任务检测   | Linux的计划任务设置    |
| 开机启动任务检测 | Linux的开机启动任务设置 |