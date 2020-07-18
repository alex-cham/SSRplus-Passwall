# SSRplus-Passwall

SSRplus-Passwall的IPK安装包及其全部依赖。

从众所周知的openwrt源编译所得，可以在没有安装任何依赖的固件安装SSRplus 和 Passwall 插件。

安装方法：

1：通过winscp全部上传至 /tmp
2: opkg install *.ipk
3: 安装过程中由于顺序原因，肯定有些插件无法安装，提示缺少依赖。按照提示先安装确实依赖的ipk，再安装之前无法安装的ipk。
4: 再次执行 opkg install *.ipk。
5：还会有步骤3的问题，同样的方法解决，直至全部IPK安装完成没有错误提示。

在k**lshare 2.35固件测试通过。
