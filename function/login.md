{{indexmenu_n>3}}

# 登录安全

登录安全能够检测您服务器上的异常登录行为，当发现异地登录、暴力破解时进行告警提示。

## 检测原理

安装Agent以后，第一次登录的地点将默认设置为常用登录地。并将日志上传至云端保存。如果发现与第一次登录地点不同，则标记为异地登录，将会触发事件告警。

## 检测周期

实时检测，一旦发现异地登录行为、暴力破解成功，立即告警。

## 检测项

| 检测项    | 说明                   |
| ------ | -------------------- |
| 异地登录   | 指从非常用地登录的行为          |
| 暴力破解成功 | 采用暴力破解的方式登录主机，并且尝试成功 |
| 暴力破解失败 | 采用暴力破解的方式登录主机，不过尝试失败 |