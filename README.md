# cfnat_repack
cfnat win版打包，美化，隐藏CMD

cfnat是自建workers和pages节点的好搭档，按照作者的话来说：“cfnat 专治泛播ip动态路由”

这个打包版主要是为了美化，隐藏黑乎乎的CMD窗口到托盘，并且配上图标，让你在win下使用更方便美观一些。只是个重新打包，没有任何技术含量。

简单使用说明，具体的cfnat使用参数在官方的发布频道里自行查看:

1：如果你是电信/联通线路，直接双击cmd_tray.exe启动程序即可

2：如果你是移动线路，打开cmd_tray.yaml，按照里面的提示修改并保存，然后运行cmd_tray.exe即可。

启动后cfnat程序会花一点点时间才会优选完成，耐心等待。

在优选完成后，如果你在本机使用，那么你的优选IP为127.0.0.1 端口为1234

如果你局域网其它设备使用，你的优选IP为当前运行cfnat主机的局域网地址。

如果你要查看状态，右击托盘图标，选择第二项 显示/隐藏控制台，即可呼出界面，如想再次最小化到托盘，不要点击窗口上的X来关闭！不要点击窗口上的X来关闭！不要点击窗口上的X来关闭！会造成软件无法退出！再次右击托盘图标选择显示/隐藏控制台即可最小化到托盘。

此打包程序只包含win下的64位版本，以后如果更新cfnat，用新版解压缩到此文件夹覆盖即可

设置开机启动：

创建一个cmd_tray.exe的快捷方式，然后按 win+r 在弹出的窗口中输入 shell:startup 然后回车。

这时会打开开机启动文件夹，把刚才创建的cmd_tray.exe的快捷方式拖动到这个文件夹中即可。

致谢：
cfnat的TG发布频道：https://t.me/CF_NAT/38840
打包所用的程序：https://github.com/TunMax/cmd_tray
