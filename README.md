# emulestep3_3rdparty_cryptopp
Crypto++是个免费的C++加解密类库,资格老但是持续更新,目前的最新版本是CryptoPP 8.2

下载地址:https://www.cryptopp.com 
压缩包解压之后，找到解决方案文件cryptopp820\cryptest.sln 。源包一共有四个工程，ConsoleMD5是我自己加入的一个测试工程。一般来说，编译项目cryptdll即可。从输出目录中找到cryptopp.dll、cryptopp.lib备用。
dll/lib端一定要与客户端在配置上保持一致。1.debug=dubug release=release 2.项目->属性->c/C++->代码生成->debug->运行库：多线程调试 (/MTd) 项目->属性->c/C++->代码生成->release->运行库：多线程 (/MT)

