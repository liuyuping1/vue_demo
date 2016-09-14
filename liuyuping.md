
	 

#WAMP下载、安装及配置 #

#下载#

	 【下载安装包】：在百度搜索wamp，然后下载相应版本的安装包。
![](http://b.hiphotos.baidu.com/exp/w=480/sign=8983fc0e0af79052ef1f46363cf3d738/faf2b2119313b07e63a7df150fd7912397dd8c91.jpg)

#安装#
     
		1.【安装】：打开安装包，选择“next”。然后接受授权，选择“next”。
![](http://e.hiphotos.baidu.com/exp/w=480/sign=de9eb0ded4ca7bcb7d7bc6278e086b3f/64380cd7912397dd0dd411195a82b2b7d0a2877a.jpg)
![](http://g.hiphotos.baidu.com/exp/w=480/sign=f5d67ed0ff039245a1b5e007b794a4a8/faedab64034f78f0c12e12ee7a310a55b3191c81.jpg)
	  
     2.【选择安装路径】：在选择路径对话框选择安装路径，点击“next”。选择按桌面安装快捷方式，选择“next”，然后点击“install”开始安装。
![](http://e.hiphotos.baidu.com/exp/w=235/sign=4839307997eef01f4d141fc6d5ff99e0/94cad1c8a786c9178388db24ca3d70cf3bc75720.jpg)
![](http://h.hiphotos.baidu.com/exp/w=235/sign=bc7b21afd258ccbf1bbcb2392cd9bcd4/fd039245d688d43f883119ef7e1ed21b0ef43b16.jpg)
![](http://f.hiphotos.baidu.com/exp/w=480/sign=b29845f1d200baa1ba2c46b37711b9b1/c995d143ad4bd1135e553f2f59afa40f4bfb0516.jpg)

	 3.【完成安装】：完成安装后选择“finish”，在桌面出现了wamp的快捷方式。
![](http://b.hiphotos.baidu.com/exp/w=480/sign=615f74ad66380cd7e61ea3e59144ad14/fcfaaf51f3deb48f5d752ac3f31f3a292df5788b.jpg)
![](http://b.hiphotos.baidu.com/exp/w=480/sign=116d9b3296cad1c8d0bbfd2f4f3e67c4/aa18972bd40735fac7eec5a49d510fb30f240894.jpg)

	 4.【启动wamp】：双击快捷方式，启动wamp。如图说明启动成功。
![](http://b.hiphotos.baidu.com/exp/w=480/sign=13c9fd3b6e224f4a5799721b39f79044/342ac65c103853435ac00c3c9013b07eca8088a4.jpg)

	 5.【在浏览器查看wamp是否启动成功】：打开浏览器，在地址栏输入localhost，如图说明成功。
![](http://e.hiphotos.baidu.com/exp/w=480/sign=f74f0d318401a18bf0eb1347ae2e0761/21a4462309f79052e4b9cc230ff3d7ca7bcbd50d.jpg)

#phpmyadmin配置#

	 6.【查看php配置信息】：在页面点击“phpinfo()”进入php配置信息页面。
![](http://h.hiphotos.baidu.com/exp/w=480/sign=376e270f710e0cf3a0f74ff33a46f23d/b17eca8065380cd7361f28f0a244ad34598281ae.jpg)
![](http://g.hiphotos.baidu.com/exp/w=480/sign=7558f0efd662853592e0d329a0ef76f2/bd3eb13533fa828b481617fefe1f4134970a5af2.jpg)

	 7.【使用phpmyadmin操作数据库】：点击页面“”进入phpmyadmin管理页面。
![](http://f.hiphotos.baidu.com/exp/w=480/sign=958c8bb6003b5bb5bed721f606d2d523/3801213fb80e7bece95f89fc2c2eb9389b506b22.jpg)
![](http://h.hiphotos.baidu.com/exp/w=480/sign=c686072378ec54e741ec1b1689399bfd/b2de9c82d158ccbf8b383f271ad8bc3eb1354123.jpg)

#Apache配置#
	 1.点击任务栏右侧的wampserver图标，之后会出现如下图示的菜单。
![](http://h.hiphotos.baidu.com/exp/w=480/sign=c259dc823ff33a879e6d0112f65d1018/b8389b504fc2d56292558f5fe21190ef76c66c26.jpg)

	 2.主要有9个菜单，localhost对应的分别是localhost对应的是网站的首页，通过它访问网站，phpMyAdmin对应的是MySQL的数据，可以通过它管理数据库，www directory对应的是网站的目录，这个目录可以再配置文件里重新配置，其他的我会在下面介绍
	 3.Apache菜单是介绍Apache的内容，有它的版本信息，它的服务信息，可以通过重启Apache的服务来只重启Apache服务，而不重启其他的服务。
![](http://g.hiphotos.baidu.com/exp/w=235/sign=53bb3c5884cb39dbc1c06055e51709a7/b64543a98226cffc9068e700bc014a90f703eac6.jpg)
![](http://c.hiphotos.baidu.com/exp/w=235/sign=d7d53b79b7fb43161a1f7d7915a54642/d439b6003af33a8703e85ba8c35c10385243b5ff.jpg)
![](http://d.hiphotos.baidu.com/exp/w=480/sign=1a16a56d73094b36db921ae593cd7c00/5d6034a85edf8db1e0a827d60c23dd54574e74f9.jpg)
		
	 4.打开Apache菜单对应的http.conf,这就是Apache的配置文件，可以配置网站的很多东西，比如网站的目录，网站的模块，如下图。可以根据个人的喜好来配置Apache
![](http://b.hiphotos.baidu.com/exp/w=480/sign=c301a2940c24ab18e016e03f05fbe69a/f703738da9773912227cc2d3fd198618367ae22e.jpg)
![](http://h.hiphotos.baidu.com/exp/w=480/sign=cfda8f9d4434970a47731127a5cbd1c0/b7fd5266d0160924cc11e5a9d10735fae6cd344f.jpg)


#推荐#
	 推荐laravel
	 优点：1..安全性高，功能强大。比如它能够根据用户在浏览器中的当前页生成一系列分页链接。
	 2.在laravel中直接在模型中建立映射
	 缺点：1.laravel最新版要求php版本最低为5.5.9
	 2.上手来说相对比较困难，中文资料少
