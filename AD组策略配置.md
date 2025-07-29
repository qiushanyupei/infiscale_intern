更新组策略命令：gpupdate<br>
针对所有域用户生效：windows管理工具->组策略管理->打开自己要修改的域（例：is.sh）->点击组策略对象->Default Domain Policy->右键编辑->计算机策略->策略->Windows设置->安全设置->账户策略->密码策略->修改<br>
强制密码历史表示记住前面n个密码，新密码不允许和这n个密码相同<br>
AD中的组是在OU的基础上创建的，和新建用户一个操作路径：可以最基本的设置完名称直接创建组，组在对应的OU下，创建完组需要添加用户<br>
针对某个部门设置：windows管理工具->Active Directory管理中心->点击要修改的域->点击System->Password Settings Container->右上方新建->密码设置->设置完成后添加应用的组或个人
