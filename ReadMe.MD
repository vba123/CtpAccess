CTP期货交易平台使用说明

一、	安装：
1、	将Ctp.rar文件解压缩到c:\ctp；

2、	找到c:\ctp\ctpinst.bat，右键单击，选择以管理员身份运行，自动注册控件。

二、	使用：
1、	本程序需要在Office2010或以上版本的Access下才能运行，所以你的电脑上必须安装Office2010或Office2013，注意不是WPS。

2、	启动Access2010或2013，修改选项，将“宏”安全级别改为“启用所有宏”

3、	以上设置好之后，打开c:\ctp\ctpqh.accdb，就可以运行交易平台了，需要将你的期货交易账户输入账户列表窗体。

这个窗体管理多个账户，可以是不同期货公司的账户，每一个账户一行，需要登录的账户，勾选登录框，配置文件是一个.xml文件，在c:\ctp目录下，每一个账户都需要一个，同一个期货公司的账户可以共用一个.xml文件，可以复制一个.xml文件，修改一下名字，然后设置IP地址和端口号。

Configjy.xml范例： 

这个是海通期货的Broker、IP地址和端口号，其中type=trade那一行的IP是交易服务器地址，type=md的IP那一行是行情服务器地址，port是端口号，这些信息都不能错，否则连接不到期货公司服务器，如果不知道这些信息，可以看c:\ctp目录下的“几乎所有brokers”文件，找到你开户的期货公司的拼音首字母，就能查到这3个信息了。
关于如果设置配置文件，可以看我的视频介绍：http://v.youku.com/v_show/id_XNzk0MDY4NTY4.html?spm=a2hzp.8244740.0.0

4、	登录

经过以上步骤之后，恭喜你，应该可以登录了，单击账户列表窗体上的登录按钮，如果成功，登录状态会自动变为“已登录”，就可以正式使用了。

5、	持仓管理界面

持仓信息，显示所有登录账户的持仓信息和交易委托信息以及止盈止损价位，要打开这个窗体，才可以进行持仓管理。

6、	止盈止损界面

持仓管理界面上单击某一个持仓合约，就会弹出一个止盈止损小窗体，这个小窗体可以实现修改止损、止盈价位，手动开平仓等操作。窗体上的“默认”按钮是用于设置默认止盈止损百分比的。

7、	自动执行任务

自动任务，是实现定时自动登录、登出、自动打开持仓管理等的设置窗体，实现无人值守式的管理。

8、	其他

本程序只开放使用权，使用本程序进行期货交易，风险自担，盈亏自负。

  
三、联系作者：

  1、QQ：253675026（注明：来自git） 交流群：301729530
  
  2、微信：guotx-（注明：来自git）
  
