Xiaomi8SE 海外版本刷机教程、

1.解除BL锁。

http://www.miui.com/shuaji-393.html 小米官方自带解锁教程

Tips:

- 在解锁的过程中要进入fastboot模式。

- 部分同学说解锁失败，或者不可以解锁，因为你本身机器没有打开解锁的设置。步骤：
  - 手机打开开发者模式
  - 更多设置-解锁按钮-打开
    
    

2.使用twrp更新系统自带的recovery系统。（注意可能被自带系统覆盖，所以更新后使用recovery重启进入新的recovery系统。保证不被覆盖）

（因为是针对M8se，我不做其他机型的介绍，但是都差不多。）

1. 首先要找到对应的twrp的img包。 附上链接（https://pan.baidu.com/s/1HmHUzeGREqFOaUEcK_dHBg）请注意，这个是针对MI8SE优化过的twrp。其他手机应该使用通用版本，我就不找了，但是如果大家实在找不到，留言。
2. 安装也很傻瓜。（点击第一条下载下的rar包，点击此文件“mi8se-recovery-twrp一键刷入.bat”）这里有一点要注意，我建议保持手机处于fastboot的情况下使用这个cmd脚本。因为我还没有使用过开机状态下的这个脚本。因为我已经成功了。
3. 脚本执行完成后，手机会自动进入twrp这个recovery系统，别担心，你之前的miui系统还在，只是你的recovery的系统换了。这两个是分开的，不要恐慌。
4.  把这个单独做一点是因为，在我安装的过程中，没有执行这一步导致饶了很多弯路。我不希望你们也这样。进入新的twrp系统，你首先应该重启!!!重启！！！重启！！！点击一下TWRP的重启！！！！！！！！点重启啊！！！！！！找到重启，重启进入twrp系统。这样系统自带的recovery系统就不会覆盖掉你的twrp。重启之后-》
5. 首先你应该做备份，备份这个操作也在twrp这里操作。（比原生的recovery好用多了，功能更强大）

3.download对应的 卡刷包。

先附上链接：

https://sourceforge.net/projects/xiaomi-eu-multilang-miui-roms/files/xiaomi.eu/MIUI-WEEKLY-RELEASES/8.7.19/xiaomi.eu_multi_MI8SE_8.7.19_v10-8.1.zip/download

请注意，这个是卡刷包，请不要把这个东西当线刷包使。很蠢。

下载这一步没啥好说的。

4.使用twry备份当前的数据和系统。（这步一定要做，之后要返回旧的系统使用twry很方便）

咦，这个在2， 我提醒过了对吧。

5.使用twry安装最新的刷机包。

注意，这里有个坑，就是你使用twry安装新的刷机包的时候，会发现，所有的文件名都是乱码，总之你看不懂那种。这个我查了查，是因为安卓手机全盘加密的原因。这个很简单，你只需要进入twry的清除那个菜单。清除所有的数据（这一步一定要确认你是否是否是否备份好之前的数据）不然你找我我不负责的啊。（妹子除外）

选中第三部你download的卡刷包。twry自动刷好 重启。

这里你可能会遇到一个问题，重启卡在logo界面，没关系，再试一次重启就好。（说实话我慌得要死，哈哈哈）

6.重启进入新的系统。

到这一步，你已经成功了，恭喜你。google套件，无广告极为纯净的系统。

我真的很喜欢小米手机，但是他的那个傻逼商店，还有每次安装应用后给我推荐傻逼的应用我，受够了。

自由，每个人都有权利去追求。尽管阻碍重重。



7.done.

那就是这样啊，这一节没啥说的，希望大家点一下star.就这样。



参考资料：

	http://www.miui.com/thread-16712001-2-1.html ----get到了最新可用的卡刷包

	http://www.miui.com/thread-2870129-1-1.html  -----你不想刷国际版但是又想用谷歌套件

	http://www.miui.com/thread-4123791-1-1.html- -----全网通7.2.4稳定版 twrp备份镜像 算是twrp的基本入门，有界面，可以参考一下。

	http://www.miui.com/thread-8505693-1-1.html     -----twrp文件乱码解决方案（清除数据）

	https://pan.baidu.com/s/1HmHUzeGREqFOaUEcK_dHBg ----MI8SE twrp中文优化版本，本教程都是基于该软件操作

	http://www.anzhuorom.com/recovery/7906.html#down   ----MI8SE twrp中文优化版本软件介绍

	http://en.miui.com/download-346.html  另外，这个是海外版本的系统，我还没有用这里的卡刷包试twrp，因为之前正经的卡刷方式（也就是官方的卡刷方式失败了），大家想玩可以试试。但是，这里的线刷包和SE不兼容。请注意了。不兼容。



至此，我要去玩我的MIUI10 国际版了。

链接：https://pan.baidu.com/s/1PLEKrAMk7XOOdKQgARGX2w 密码：0osg
1. mi8SE优化后的twrp
2. markdown格式的教程
3. 海外可用的MIUI10系统压缩包。
	
