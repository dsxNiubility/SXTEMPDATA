--------------------------------------------------
/*The following content is Chinese.*/
/*以下内容为中文*/
--------------------------------------------------
p12文件密码:111111

developer_identity.p12		必须要导入到Mac系统。
development.mobileprovision	只是用iResign签名，而不是使用Xcode开发App的话，可以不导入Mac系统。
AWDRCA.cer			这个文件是Apple根证书，如果Mac系统没有安装Xcode的话，必须导入此文件。

*只是用iResign签名，可以不装Xcode，但是必须要双击AWDRCA.cer以导入到Mac系统中。

Q: 如何导入文件？
A: 在Mac系统中，双击文件，按照提示，选默认的选项点击"OK"即可。注意，不装Xcode的话，development.mobileprovision无法导入到系统中去。