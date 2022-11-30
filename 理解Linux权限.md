#### 权限文件

* /etc/passwd：存放用户账户信息的文件，当然实际密码加密信息可能存放在/etc/shadow，mac起始用户并不是存放在这里
* /etc/group：存放用户组信息

#### 账户/属组命令

* useradd：添加账户
* userdel：删除账户
* usermod：修改账户
* groupadd：添加组
* groupdel：删除组
* groupmod：修改组

#### 权限

* rwx：对应读(4)-写(2)-可执行(1)[](https://)
* chmod：可以更改权限
* chown：更改文件属主
* chgrp：更改文件属组
