1、下发软件静默安装<br>
共享文件夹配置：属性->共享->点击共享（S...）->在网络访问里点击对应用户或者直接everyone（这些用户都是需要在AD里创建的）->在该共享文件夹下放置需要安装的msi文件<br>
下发文件方法：在windows server上，打开组策略管理->win+R，输入gpmc.msc->创建新组策略对象(GPO)->在组策略管理界面->右键点击对应组织单位->选择“创建一个GPO并再次链接”<br>
            ->右键新的GPO->编辑->计算机配置->策略->软件设置->软件安装->新建数据包->选择对应的安装包路径
            ->“分配”：软件将自动安装。;“发布”：用户可以选择安装。
