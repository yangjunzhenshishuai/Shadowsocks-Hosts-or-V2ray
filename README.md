# Shadowsocks or Hosts
## 影梭和Hosts的科学上网
----------
![](https://i.imgur.com/upTVEr3.gif)
----------
### Hosts科学上网（Hosts Science Online）
- IPV6
	1. 如果网络支持IPv6，我们通常使用IPv6访问Google和YouTube。(If the network supports IPv6, we usually use IPv6 for access to Google and YouTube)
	2.如果是Windows系统，可以在C:/windows/system32/drivers/etc修改DNS，并保存信息，之后可以直接地访问Google和YouTube。( If you are an Windows system, you can find host in C:/windows/system32/drivers/etc, modify DNS, and save information after modification, and finally you can directly access the Internet scientifically.)
	3. 该开源项目编写了一个hosts更改或恢复的[项目](https://github.com/lovelyyoshino/SS-or-ipv6_host/releases)，相关的代码和exe可以在这个项目中下载。（This developed project set a project to change or restore hosts，and this relevant code and exe can download in this project）
	4.如果hosts失效可以将下载文档中的hosts删除并重新添加lennylxx利用Scprits生成的[hosts文件](https://github.com/lennylxx/ipv6-hosts/blob/master/hosts) （If hosts fails, the hosts which is in the download document can be deleted and added to the Scprits which hosts file generated by lennylxx.）
- IPv4
	1. IPv4和IPv6一样，均可以用该软件一键注册，直接访问 Google和Youtube ，但是普通家庭一般没有IPv6所以建议注册IPv4（IPv4 and IPv6 can use this software to register  and visit Google and Youtube directly, but normal families usually don't have IPv6, so it is recommended to register IPv4.）
	2. 如果是学校（教育）网络可以使用IPv6，因为这个更加全面。（If the network is school (education) network can use IPv6, because this is more comprehensive.）
	3. 如果hosts失效可以将下载文档中的hosts删除并重新添加googlehosts生成的[hosts文件](https://github.com/googlehosts/hosts/blob/master/hosts-files/hosts)（If hosts fails, the hosts which is in the download document can be deleted and added to the file which hosts file generated by googlehosts.）

### Shadowsocks科学上网
- 科学上网自建教程
	1. 以下为自己搭建SS/SSR或v2ray服务器教程,以下两个Github项目操作均适合新手。

	 	####[自建ss/ssr服务器教程](https://github.com/Alvin9999/new-pac/wiki/%E8%87%AA%E5%BB%BAss%E6%9C%8D%E5%8A%A1%E5%99%A8%E6%95%99%E7%A8%8B)

	 	####[自建v2ray服务器教程](https://github.com/Alvin9999/new-pac/wiki/%E8%87%AA%E5%BB%BAv2ray%E6%9C%8D%E5%8A%A1%E5%99%A8%E6%95%99%E7%A8%8B) 
	2. VPS推荐：

		####Vultr 	
		*知名服务器供应商；全球15个服务器位置可选，KVM框架，最低2.5美元/月。支持支付宝和paypal付款。不怕被封ip，因为vultr是折算成小时计费，且可以随时删除和开通服务器，新服务器就是新的ip。*
		####Linode
		*inode是一家美国的VPS主机托管商，成立于2003年。最低配的方案为1G内存，20G SSD硬盘，价格为$5/月。实际上，它是按照小时收费的，每小时的价格为$0.075，如果你用满一整个月，那么最多只需要支付$5，但大部分的月份都低于$5。*

