windows/ssh 远程，统一方便管理，在 windows 10下可以正常运行

1、使用前关闭防火墙或开启3389，22端口（windows 占位集成）

2、未添加日志打印

3、ssh 不支持密钥登陆，支持富文本,支持sftp上传单个文件，下载单个文件，删除文件

4、请不要随意删除data

5、在/etc/ssh/sshd_config 文件中设置    kexAlgorithms  diffie-hellman-group-exchange-sha256

6、有时间在更新完善吧

东拼西凑可以用，不会收集个人信息，支持1-2个连接，需要更多连接可以赞赏购买