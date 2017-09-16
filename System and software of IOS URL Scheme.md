# URL-Scheme大全-hughcharles

[iOS常用软件](#ios常用软件)、[iOS系统应用](#ios系统应用)、[支付宝](#支付宝)、[Spark](#spark)、[Workflow](workflow)、[Surge](#surge)、[Day One](#day-one)
[搜索引擎](#搜索引擎)

	
---
## iOS常用软件

|名称       	 |urlscheme                          |
|:----------|:-----------------------|
|**快捷方式**
|1Password	|onepassword://|
|欧路词典		|eudic://dict/%@|
|欧路词典		|eudic://x-callback-url/searchword?word=%@|
|OMnifocus 	|omnifocus://x-callback-url/add?name|
|Workflow	|workflow://run-workflow?name=X|
|Surge		|surge:///toggle?autoclose=true|
|虾米音乐： 	|xiami://|
|支付宝：    		|alipay://|
|微信：   			|wechat://|
|QQ：        		|mqq://|
|QQ国际版  		|mqqiapi://|
|Evernote   		|evernote://|
|Spark			|readdle-spark://|
|Reeder			|reeder://|
|知乎：        	|zhihu://|
|新浪微博： 					|weibo://|
|新浪微博-国际版：			|weibointernational://|
|新浪微博-weico客户端： 	|weico://|
|**功能**
|微   信-扫一扫: |wechat://scanqrcode|
|支付宝-扫一扫:	|alipay://platformapi/startapp?saId=10000007
|支付宝-付款码:	|alipay://platformapi/startapp?saId=20000056
|支付宝-收款码:	|alipay://platformapi/startapp?saId=20000123
|**搜索**
|链接		 |url://
|1Pass	 |onepassword://search/%@|
|欧路词典	 |eudic://x-callback-url/searchword?word=%@|
|谷歌		 |https://www.google.com/search?q=%@|
|百度百科	 |http://baike.baidu.com/item/|
|维基中文	 |https://zh.wikipedia.org/wiki/%@|
|知乎		 |https://www.zhihu.com/search?q=%@|
|豆瓣		 |https://m.douban.com/search/?query=|
|淘宝		 |http://s.m.taobao.com/h5?q=Input|
|**其他**
|Chrome	|googlechrome://|
|Chrome	|googlechrome://www.google.com/search?&q=%@|
|优酷：       		|youku://|
|QQ音乐      		|qqmusic://|
|QQ音乐-最近 	|qqmusic://today?mid=31&k1=2&k4=0|
|豆瓣fm：     	|doubanradio://|
|网易公开课：	|ntesopen://|
|名片全能王：	|camcard://|
|Documents5	|rdocs://|
|豆瓣FM       	|doubanradio://|
|网易公开课  	|ntesopen://|
|百度云       		|baiduyun://|
|全民K歌： 		|qmkege://|
|腾讯视频       	|tenvideo://|
|爱奇艺PPS     	|ppstream://|
|哔哩哔哩动画 	|bilibili://|
|摩拜单车       	|mobike://|
|ofo        		|ofoapp://|
|扫描全能王 		|camscanner://|
|UC浏览器  		|ucbrowser://|
|有道云笔记  	|youdaonote://|
|SimpleMind 	|simplemind://|
|MindMeister 	|mindmeist://|
|WPSOffice  		|kingsoftofficeapp://|
|Clear      		|clearapp://|
|Calendars5 	|calendars://|
|PDFExpert5 	|pdfexpert5presence://|
|金山词霸   		|com.kingsoft.powerword.6://|
|有道词典   		|yddict://|
|蜻蜓FM       	|qtfmp://|
|酷我音乐   		|com.kuwo.kwmusic.kwmusicForKwsing://|
|QQ安全中心     |qmtoken://|
|百度贴吧   		|com.baidu.tieba://|
|搜狐新闻   		|sohunews://|
|随手记       		|FDMoney://|
|挖财记账   		|wacai://|
|网易新闻   		|newsapp://|
|掌阅iReader		|iReader://|

-------

## iOS系统应用
|名称        |urlscheme               	|
|:----------|:---------------|
|地图： 		|maps://				|
|电话：    	|tel:					|
|短信：   		|sms:					|
|Mail邮件:	|mailto:				|
|iBooks：	|ibooks://			|
|音乐： 		|music:				|
|视频			|videos:				|
|邮件: 		|MESSAGE://			|
|Tel电话: 	|mobilephone://	|
|Note备忘录:	|mobilenotes://		|
|电话:			|tel://					|
|App Store:	|itms-apps://		|
|iTunes：  	|http://itunes.apple.com 
|设置：		|App-prefs:root=SETTING 
|通知			|App-Prefs:root=NOTIFICATIONS_ID
|锁定：		|App-Prefs:root=General&path=AUTOLOCK
|定位服务:  	|App-prefs:root=LOCATION_SERVICES
|无线局域网	|App-Prefs:root=WIFI
|蓝牙			|App-Prefs:root=Bluetooth
|蜂窝移动网络|App-Prefs:root=MOBILE_DATA_SETTINGS_ID
|个人热点		|App-Prefs:root=INTERNET_TETHERING
|运营商		|App-Prefs:root=Carrier
|通用			|App-Prefs:root=General
|-关于本机	|App-Prefs:root=General&path=About
|-辅助功能	|App-Prefs:root=General&path=ACCESSIBILITY
|-储存空间	|App-Prefs:root=General&path=STORAGE_ICLOUD_USAGE/DEVICE_STORAGE
|-键盘		|App-Prefs:root=General&path=Keyboard
|-语言与地区	|App-Prefs:root=General&path=INTERNATIONAL|
|-还原		|App-Prefs:root=Reset
|亮度：		|App-Prefs:root=Brightness
|墙纸			|App-Prefs:root=Wallpaper
|声音: 		|App-Prefs:root=Sounds
|Siri			|App-Prefs:root=SIRI 
|电池: 		|App-Prefs:root=BATTERY_USAGE
|隐私			|App-Prefs:root=Privacy
|Safari		|App-Prefs:root=SAFARI 
|音乐			|App-Prefs:root=MUSIC 
|音乐-均衡器	|App-Prefs:root=MUSIC&path=com.apple.Music:EQ|
|照片与相机	|App-Prefs:root=Photos
|FaceTime	|App-Prefs:root=FACETIME 

-------

## 支付宝

|名称      	   |urlscheme                                    
|:-------  |:----------------------------------
|支付宝：   |alipayqr://            	
|扫一扫：   |alipayqr://platformapi/startapp?saId=10000007|
|转账：      |alipayqr://platformapi/startapp?saId=20000116|
|付款码：   |alipayqr://platformapi/startapp?saId=20000056|
|收款码：   |alipayqr://platformapi/startapp?saId=20000123|
|红包：	   |alipayqr://platformapi/startapp?saId=88886666|
|卡券：      |alipayqr://platformapi/startapp?saId=88888888|
|手机充值：|alipayqr://platformapi/startapp?saId=10000003|
|余额宝：   |alipayqr://platformapi/startapp?saId=20000032|

-------

## Spark
[官方文档原文](https://helpspot.readdle.com/spark/index.php?pg=kb.page&id=791)

|名称        |urlscheme                                    |
|:----------|:---------------------------|
|Open Spark:|readdle-spark://|
|open Spark mail composer:|readdle-spark://compose|
|launching Spark compose mode with Subject, Body and Recipient already filled test@test.com follows this structure: |readdle-spark://compose?subject=test&body=test2&recipient=test@test.com|

-------
## Workflow
|名称        			|urlscheme                                 |
|:---------------|:---------------------------|
|运行特定flow	|workflow://run-workflow?name=X
|包含输入			|workflow://run-workflow?name=X&input=text&text=[YOUR INPUT]|
|输入剪贴板		|workflow://run-workflow?name=X&input=clipboard
|x-callback		|workflow://x-callback-url/run-workflow?name=X&input=X&x-success=http://example.com

-------

## Surge
|名称        			|urlscheme                                 |
|:---------------|:---------------------------|
|**Action**|
|Start with selected configuration.|surge:///start
|Stop current session.|surge:///stop
|Start or stop with selected configuration.|surge:///toggle
|Install a configuration form a URL. The URL should be encoded in percent encoding.|surge:///install-config?url=x
|**Option**|
|Example：|autoclose=true
|Auto close Surge after action completed. (Cannot be used with install-config):| surge:///toggle?autoclose=true

-------

## Day One
|名称        			|urlscheme                                 |
|:---------------|:---------------------------|
|**Navigation:**
|Open Day One:		|dayone://
|Open Activity Feed: 	|dayone://activity
|Open Timeline: 		|dayone://entries
|Open Calendar:		|dayone://calendar
|Open Starred: 			|dayone://starred
|Preferences: 			|dayone://preferences
|**Entry Create:**
|Create Entry with Text: |dayone://post?entry=Hello Self
|Create Entry with Tags: |dayone://post?entry=Hello Self&tags=My Tag, Test
|Create Entry in Journal: |dayone://post?entry=Hello Self&journal=Day One
|Create Entry with Clipboard Image: |dayone://post?entry=Hello Self&imageClipboard=1
|**Entry Edit:**|
|Edit Entry: |dayone://edit?entryId=\[UUID] (Don't include brackets.)

-------

## 搜索引擎
|名称         	|urlscheme                           |
|:---------|:----------------------------------|
|知乎 	     |https://www.zhihu.com/search?q=|
|谷歌 	     |https://www.google.com/search?q=|
|百度 	     |https://m.baidu.com/s?word=|
|维基 	     |https://en.m.wikipedia.org/wiki/|
|维基中文 |https://zh.wikipedia.org/wiki/%@|
|有道词典 |http://m.youdao.com/dict?q=|
|京东       |http://so.m.jd.com/ware/search.action?keyword=|
|淘宝 	     |http://s.m.taobao.com/h5?q=Input|
|豆瓣 	     |https://m.douban.com/search/?query=|
|百度百科     |http://baike.baidu.com/item/|
|微博 	     |http://m.weibo.cn/main/pages/index?containerid=100103type%3D1%26q%3D|






