## 前置知识

- [ ] 掌握操作系统使用
- [ ] 熟练重装系统
- [ ] 什么是web网站？
    - https://baike.baidu.com/item/web/150564
- [ ] HTML/CSS/JS

    - https://www.w3schools.com/

    - https://developer.mozilla.org/zh-CN/docs/Web

    - https://www.runoob.com/tags/ref-standardattributes.html
- [ ] Golang（未来趋势，良好的跨平台、优秀的多线程和网络处理）
  - [【坤哥力荐】4星期速成学会poc，摆脱脚本小子](https://www.bilibili.com/video/BV1vM411r7GW/)
- [ ] Python（社区庞大，入门简单，可以作为初学语言）
  - https://www.bilibili.com/video/BV1qW4y1a7fU
- [ ] Java（后端开发主流语言，通用漏洞发现几乎是最多的语言，学习难度大，不推荐）
- [ ] 数据库（一种类型选择一个了解）
  - Sql
  	- [ ] MySQL（推荐）
  	- [ ] Oracle
  	- [ ] MSSQL
  - NoSql
  	- [ ] Redis（推荐）
  	- [ ] MongoDB
  	- [ ] ElasticSearch
- [ ] Linux基础命令（日常操作、应急和搭建靶场）
  - [Linux命令速查手册](http://linux-command.kit.secself.com/)
  - [Linux 命令大全](https://www.runoob.com/linux/linux-command-manual.html)
- [ ] Docker（了解原理，日常使用无障碍）
  - [Docker 教程](https://www.runoob.com/docker/docker-tutorial.html)
  - [Docker Compose ](https://github.com/docker/compose)

掌握一门后端编程语言，有编程基础后续学习更顺利。

### 协议

助安社区开源的基础速成，大部分基础协议都已整理完毕，点击 👉  [安全速学手册](http://security-base.book.secself.com/protocol/index.html)

- [ ] HTTP协议

  - [超文本传输协议（HTTP）](https://developer.mozilla.org/zh-CN/docs/Web/HTTP)

  - [HTTP 教程](https://www.runoob.com/http/http-tutorial.html)
- [ ] ARP
- [ ] DHCP
- [ ] SMB
- [ ] DNS
- [ ] 代理
- [ ] HTTP
- [ ] Socks5
- [ ] VPN
- [ ] FTP
- [ ] SSH

...

## 信息收集

### 网络

- [ ] 子网掩码（B段、C段）

  - [ ] [如何理解子网掩码？](https://www.zhihu.com/question/56895036)
  - [ ] 工具
  	- [ ] [Masascan](https://github.com/robertdavidgraham/masscan)
  	- [ ] [Zmap](https://zmap.io/)
  	  - [ ] [zgrab2](https://github.com/zmap/zgrab2)
  	- [ ] [Nmap](https://nmap.org)
- [ ] ASN

	- [什么是自治系统？| 什么是 ASN？](https://www.cloudflare.com/zh-cn/learning/network-layer/what-is-an-autonomous-system/)
	- ASN 查询
	
		- https://hackertarget.com/as-ip-lookup/
	
		- https://dnschecker.org/asn-whois-lookup.php
	- 工具

		- [ ] [Amass](https://github.com/owasp-amass/amass)
		- [ ] [Zmap](https://zmap.io/)
		  - [ ] [zcrypto](https://github.com/zmap/zcrypto)
- [ ] IP反查域名

	- https://www.ipaddress.com/

### 域名

- [ ] 子域名（A记录/AAAA记录（IPV6））
- [ ] CNAME
- [ ] 邮箱记录（MX）
- [ ] TXT
- [ ] 历史记录

	- https://securitytrails.com
- [ ] 工具

	- [ ] Whois
	- [ ] [Amass](https://github.com/owasp-amass/amass)
	- [ ] [subdomain3](https://github.com/yanxiu0614/subdomain3.git)
	- [ ] [dnsmap](https://github.com/resurrecting-open-source-projects/dnsmap)
	- [ ] [ksubdomain ](https://github.com/knownsec/ksubdomain.git)

### 公开信息

- [ ] 搜索引擎

	- [ ] [黑客常用的Google搜索语法](https://www.exploit-db.com/google-hacking-database)

- [ ] 网络空间搜索引擎

	- [ ] [FOFA](https://fofa.info/)

	- [ ] [Shadow](https://www.shodan.io/)

	- [ ] [Censys](https://censys.io/)

	- [ ] [ZoomEye](https://www.zoomeye.org/)

- [ ] 工商信息

	- [ ] 证书

	- [ ] 邮箱

	- [ ] [ICP备案信息](https://beian.miit.gov.cn/)

	- [ ] 子公司

	- [ ] 集团

	- [ ] 合作商

	- [ ] 供应商

### HTTP

- [ ] 网站目录

### 工具

- [ ] [Maltego](https://www.maltego.com/)

- [ ] [JSFinder](https://github.com/Threezh1/JSFinder)

- [ ] [OneForAll](https://github.com/shmilylty/OneForAll)

- [ ] [subdomain-scanner]( https://github.com/topics/subdomain-scanner)

### 指纹

待补充

## 漏洞挖掘

### WEB漏洞（原理搞懂，靶场实践几次）

- [ ] Owasp 漏洞

	- [OWASP Top 10 2021 介紹 ](https://owasp.org/Top10/zh_CN/)
- [PDF中文下载地址](http://www.owasp.org.cn/OWASP-CHINA/owasp-project/OWASP-TOP10-2021%E4%B8%AD%E6%96%87%E7%89%88V1.0%E5%8F%91%E5%B8%83.pdf)
- [ ] JSONP劫持
- [ ] CRLF注入
- [ ] 命令执行
- [ ] 代码执行
- [ ] XXE
- [ ] CSRF
- [ ] SSRF
- [ ] DDOS
- [ ] CRLF injection
- [ ] 反序列化漏洞
- [ ] 弱类型漏洞
- [ ] 变量覆盖漏洞
- [ ] Sql注入

	- [ ] 类型

		- [ ] 报错

		- [ ] 联合查询

		- [ ] 堆查询

		- [ ] 盲注

	- [ ] 攻击利用

		- [ ] 寻找注入点

			- [ ] POST

			- [ ] GET

			- [ ] Cookie

			- [ ] Header

		- [ ] 手工注入

		- [ ] DNSLog

		- [ ] 工具注入

		- [ ] GetShell

		- [ ] 绕过防御

	- [ ] 预防修复

		- [ ] 应用层

		- [ ] 网络层
- [ ] 文件漏洞

	- [ ] 文件上传漏洞

		- [ ] 逻辑

			- [ ] 黑白名单绕过

			- [ ] MIME绕过

			- [ ] 后端校验缺失

		- [ ] 通用漏洞

			- [ ] 截断

			- [ ] 利用中间件漏洞绕过

				- [ ] IIS 5.x/6.0

				- [ ] Nginx

				- [ ] apache

			- [ ] 编辑器漏洞

				- [ ] DotNetTextBox

				- [ ] fckeditor

				- [ ] eWebEditor

				- [ ] UEditor

			- [ ] 文件头

			- [ ] .htaccess 绕过

	- [ ] 文件删除漏洞

	- [ ] 文件包含漏洞

		- [ ] ⽂件远程包含

		- [ ] ⽂件本地包含
- [ ] XSS

	- [ ] 基础知识

		- [ ] 反射型

		- [ ] 存储型

		- [ ] DOM型

	- [ ] 攻击利用

		- [ ] XSS盲打平台

		- [ ] DNSLog

		- [ ] 绕过防御

			- [ ] 同源策略

			- [ ] CORS

			- [ ] httpOnly

			- [ ] CSP

		- [ ] 缓冲区溢出GetShell
- [ ] 逻辑漏洞

	- [ ] 系统重装漏洞

	- [ ] 手机验证

	- [ ] 登入爆破
- [ ] 任意用户密码重置

	- [ ] 越权

		- [ ] 纵向

		- [ ] 横向

	- [ ] 数据遍历

	- [ ] 撞库

	- [ ] ⽀付漏洞

	- [ ] 任意密码重置

	- [ ] 失效验证码

		- [ ] 简单验证码（利⽤python图⽚识别出验证码内容）

		- [ ] 验证码可重复使用

		- [ ] 验证码遍历

	- [ ] 短信轰炸

	- [ ] 越权

	- [ ] 甲⽅安全测试方法
- [ ] 敏感信息泄漏

	- [ ] .git

	- [ ] .svn

	- [ ] 备份⽂件

	- [ ] 列⽬录

	- [ ] 注释信息

	- [ ] 默认账号/功能

### 通用漏洞披露

多收集工具，订阅漏洞信息

- [ ] [CNVD](https://www.cnvd.org.cn/)

- [ ] [CVE](https://cve.mitre.org/)

### 漏扫工具

- [ ] AWVS

- [ ] APPSCAN

- [ ] Nessus

- [ ] Owasp ZAP

- [ ]  Xray

- [ ] Pocsuite

- [ ] Goby

## 后渗透

### 操作系统

- [ ] 持久化

	- [ ] 稳定通道

		- [ ] C&C

		- web

			- [ ] 正向代理

			- [ ] 反向代理

	- Bypass

		- 杀毒

			- 360

			- 火绒

			- 卡巴斯基

			- 工具

				- [ ] iodine

				- [ ] Veil

				- [ ] [Empire](https://github.com/EmpireProject/Empire)

				- [ ] Nishang: PowerShell

		- 权限

			- [ ] 本地账户

			- [ ] 域账户

			- 工具

				- [ ] Metasploit Framework

				- [ ] Mimikatz

	- 工具

		- [ ] Rootkit

		- [ ] Cobalt Strike

		- [ ] Webshell

		- [ ] Powersploit

		- [ ] Unicorn

		- [ ] Meterpreter

		- [ ] Empire

- [ ] 信息收集

	- [ ] 账户认证信息

	- [ ] 系统版本

	- [ ] 配置文件

	- [ ] 日志

	- [ ] 网络连接（寻找管理段地址，顺腾摸瓜）

	- [ ] 安全策略

	- [ ] 系统环境变量

	- [ ] 个人PC

		- [ ] 浏览记录

		- [ ] 社交信息

### 内网

- [ ] 信息收集

	- [ ] 网络探测，部分工具参考信息收集部分

- [ ] 拓扑

	- [ ] [六种基本网络拓扑结构](https://zhuanlan.zhihu.com/p/267710797)

	- [ ] [常见的网络拓扑结构是什么？](https://worktile.com/kb/ask/8703.html)

- 横向移动

	- 普通

	- 零信任

	- 域

		- [ ] [域控制器（1）之什么是域控](https://cloud.tencent.com/developer/article/1144854)

		- [ ] [域渗透基本概念](https://www.freebuf.com/articles/web/253705.html)

		- [ ]  Mimikatz

### 虚拟化

- [ ] 容器

- [ ] 云

## 社会工程

### 书籍

- [ ] 社会工程 卷1 安全体系中的人性漏洞

- [ ] 社会工程 卷2解读肢体语言

- [ ] 社会工程 卷3 防范钓鱼欺诈

### 水坑攻击

待补充

### 供应链攻击

待补充

### 钓鱼

待补充

### 工具

-  [Social-Engineer Toolkit (SET)](https://github.com/trustedsec/social-engineer-toolkit)

- https://github.com/topics/phishing

- https://github.com/topics/phishing-tool

## 综合靶场

同类型靶场打两个足以，不是非要都打一遍

- [ ] HackTheBox 

- [ ]  VulnHub

- [ ]  TryHackMe 

- [ ] Metasploitable

- [ ] PentesterLab

- [ ] [hackxor](https://sourceforge.net/projects/hackxor/)

- [ ] [WebGoat](https://github.com/WebGoat/WebGoat)

- [ ] [hackademic](https://github.com/Hackademic/hackademic)

- [ ] [Google推出的Xss在线实验靶场](https://xss-game.appspot.com/)

- [ ] [DVWA](https://github.com/digininja/DVWA)

- [ ] [vulhub](https://github.com/vulhub/vulhub)

- [ ]  [vulab](https://vulab.io/)

## 实战

待补充，红蓝对抗月底前上线。

## 书籍推荐

选择喜欢的看，不是都要看一遍

- [ ] 《白帽子讲Web安全》

- [ ] 《Web前端黑客技术揭秘》

- [ ] 《Web应用安全权威指南》

- [ ] 《黑客攻防技术宝典 Web实战篇》

- [ ] 《白帽子讲网络安全》

- [ ] 《Web渗透测试：实战指南》

- [ ] 《Web安全攻防：漏洞剖析与防范》

- [ ] 《OWASP权威指南》

- [ ] 《Web安全深度剖析》

- [ ] 《Web安全开发指南》

- [ ] 《Metasploit渗透测试指南》

- [ ] 《Web应用程序安全攻防》

- [ ] 《黑客攻防技术宝典：Web实战篇》

- [ ] 《白帽子讲Web安全》

- [ ] 《互联网+安全：从入门到实践》

- [ ] 《Kali Linux渗透测试实战》

- [ ] 《Python渗透测试实战》

- [ ] 《护网必备：网络安全入门与渗透测试实战》

- [ ] 《黑客秘笈：渗透测试实战》

- [ ] 《Web安全攻防之道》

- [ ] 《企业安全渗透测试实战》

- [ ] 《漏洞扫描与渗透测试：Web安全领域最佳实践》

- [ ] 《渗透测试实战案例解析》

- [ ] 《信息安全技术基础》

- [ ] 《黑客攻防技术宝典：网络篇》

- [ ] 《渗透测试实战详解》

- [ ] 《黑客与计算机病毒防范攻略》

- [ ] 《渗透测试实战指南》

- [ ] 《Web渗透测试实战》

- [ ]  《黑客与画家》

## 学习资源

- [freebuf](https://www.freebuf.com/)
- [安全客](https://www.anquanke.com/)
- [先知社区](https://xz.aliyun.com/)
- [助安社区](https://secself.com/)
- [安全脉搏](https://www.secpulse.com/)
- [seebug](https://paper.seebug.org/)
- twitter
- [HackerOne](https://www.hackerone.com/)
- [hacktricks](https://book.hacktricks.xyz/welcome/readme)
- https://weibell.github.io/reverse-shell-generator/
- https://github.com/0x00-0x00/ShellPop
- https://github.com/xct/xc/
- https://github.com/Hack-with-Github/Awesome-Hacking
- https://github.com/zer0yu/Awesome-CobaltStrike
- https://github.com/alphaSeclab/awesome-rat
-  https://www.exploit-db.com/
-  [awesome-cybersecurity-blueteam](https://github.com/fabacab/awesome-cybersecurity-blueteam)    
-  https://www.hackingarticles.in/category/wireless-hacking/
-  https://github.com/The-Art-of-Hacking/h4cker

