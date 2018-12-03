# webftp
modified webftp

https://github.com/cwpdev/cwp-monsta-webftp 的个人修改版。

实现功能：将ftp列表通过http显示在网页中(有一定美化作用)，下载直接跳转到对应文件的ftp直连。

![](https://ws1.sinaimg.cn/large/675bda05ly1fxtiub5dw7j20sw0kaq3g.jpg)

![](https://ws1.sinaimg.cn/large/675bda05ly1fxtixngl8hj20t50kemyy.jpg)

![](https://ws1.sinaimg.cn/large/675bda05ly1fxtiylzu91j20sw0kaq3a.jpg)

# 自定义

1. `config.php` 修改 ftpHost，其他设置参考原项目；
2. 修改 `index.php 1216行` 以及 `ajax.js 840行` 中的下载ftp直连。grep -n '115.156' index.php;
3. 登录页面的默认 用户名以及密码通过修改 `index.php 483行` anonymous实现，密码同；
4. 精简了语音，修改默认语言到language文件夹对应语言php第7行，具体看文件内部说明；

# 其他
php 需要开启ftp支持。
