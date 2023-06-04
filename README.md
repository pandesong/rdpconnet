windows/ssh 远程，统一方便管理，在 windows 10下可以正常运行

1、使用前关闭防火墙或开启3389，22端口（windows 未合入）

2、未添加日志打印

3、ssh 支持密钥登陆，支持富文本,支持sftp上传单个文件，下载单个文件，删除文件（sftp 只展示200个文件，不排序）

4、请不要随意删除data

5、在/etc/ssh/sshd_config 文件中设置    kexAlgorithms  diffie-hellman-group-exchange-sha256

6、2023年6月17日到期，有更新时会后延

东拼西凑可以用，不会收集个人信息，支持1-2个连接(打开一个连接后关闭，需重新打开软件)，需要更多连接及功能可以赞赏购买qq:896420681，抖音号:71250580304
下载地址：

https://gitee.com/tianniao2020/sshremote
https://github.com/pandesong/rdpconnet