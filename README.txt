自行注册e5开发者账号，
一、注册Microsoft 365 E5 开发者订阅

  打开Microsoft 365开发人员中心（https://developer.microsoft.com/zh-cn/microsoft-365）

Microsoft 365开发者中心仪表板（https://developer.microsoft.com/zh-cn/microsoft-365/profile）可在这里面查看订阅剩余天数，用注册时使用的个人Microsoft账户登录。
二，安装对应工具

1，然后在office365中登录并下载软件
2，在电脑上下载node  （https://nodejs.org/zh-cn）
3，根据自己电脑系统下载对应node版本软件
4，打开CMD 运行 npm install -g yo generator-office(第一次运行才需要属于是安装驱动了)
5，cd到项目地址 然后npm start 
       会提示Allow localhost lookback for Microsoft Edge WebView? 直接输入n回车即可
等待EXCEL启动 然后随便玩玩就行了。（excel-插入-add插件）

介绍一下 插件使用方式 
./manifest.xml 加载插件的指令集 类似于 ***.yml文件

1,在当前文件夹./src/taskpan下taskpane.js 包含了所有执行的脚本文件以及命令
2，在当前文件夹./node_modules 必须要带有这个库文件

