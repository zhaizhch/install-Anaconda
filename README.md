# install-Anaconda
window系统Anaconda 安装所遇到的一系列问题
anaconda下载地址：https://www.anaconda.com/
目前清华镜像源已经不提供anaconda的支持，所以只能在官网下载。
目前版本有Python3.7 Python2.7两种，根据自己需要选择。强烈建议3.7版本。

需要将anaconda/scripts放进环境变量里面。

安装anaconda以后使用conda指令时，不能使用清华源（原因与上相同）。

可能会出现openssl error。需要安装openssl，并将OpenSSL放进环境变量。OpenSSL下载地址：http://slproweb.com/products/Win32OpenSSL.html
