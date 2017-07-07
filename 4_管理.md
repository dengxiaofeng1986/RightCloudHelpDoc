# <div align="center" ><font face="微软雅黑" size="5">管理</font></div> #

## <font face="微软雅黑" size="4">部署组管理</font> ##


<font face="微软雅黑" size="2">部署组是一组服务器的组合，支持部署的创建，修改，运行，停止，删除，克隆等操作；
提供对部署中的主机进行添加删除，运行，开机，关机等操作；
支持对部署的基本信息，主机监控信息，运行脚本信息，存储卷信息，告警信息，审计日志，历史信息，变更记录查询等功能。</font>

###<font face="微软雅黑" size="2">创建部署组</font>

<font face="微软雅黑" size="2">点击顶部导航管理，在下拉菜单中选择部署组，进入部署组管理页面，点击左上角创建部署，在弹出窗口中填写部署名称与描述，点击保存后便可在部署列表查看到您新建的部署。

![](http://i.imgur.com/nXvMg6L.png)


###<font face="微软雅黑" size="2">编辑部署组信息</font>

进入部署组管理列表，点击部署组名称进入部署组详情页，即可查看并编辑部署组基础信息，查看服务器信息并对服务器进行操作，查看部署组下主机监控信息，脚本信息以及脚本参数信息等。

+ 基础信息编辑

部署组详情中点击信息选项卡可以查看部署组的描述和标签信息，点击编辑按钮即可对基本信息进行编辑，点击上方部署组名称旁边编辑按钮，可以对部署组名称进行编辑。

![](http://i.imgur.com/ABqW2rH.png)

+ 服务器操作

点击部署组详情下服务器选项卡，可以查看当前部署组下全部的主机信息，选中主机，点击操作菜单，即可对部署组主机实现创建、删除、启动、重启、关机、移动操作。

![](http://i.imgur.com/bxDOveU.png)

+ 监控信息查看

点击部署组详情页监控选项卡，选择监控对象和监控指标，便可查看选定对象的对应监控信息。监控对象必须要安装监控组件，才能有监控数据显示。安装监控组件可以通过脚本选项卡下执行脚本操作安装。

![viewjiankonginfo](http://i.imgur.com/3ijeUsw.png)

+ <font face="微软雅黑" size="2"> 部署组脚本管理

进入部署组详情页，点击脚本选项卡，可以查看部署组中所有的启动脚本，操作脚本，停止脚本。对于每一个脚本可以进行执行操作，点击上方执行脚本按钮，可以转至脚本选择页面，选中脚本后，选择需要执行脚本的服务器，点击执行即可。

![](http://i.imgur.com/q5kKMpK.png)

![](http://i.imgur.com/r8tI5LV.png)

![](http://i.imgur.com/LmuCFB6.png)

+ 脚本参数配置

参数配置选项卡下可以查看部署组脚本中所有识别的参数列表，点击调整按钮即可对参数进行配置。

![](http://i.imgur.com/EgTxABe.png)

+ 磁盘信息查看

<font face="微软雅黑" size="2">点击磁盘选项卡进入磁盘信息页面，即可查看磁盘信息。</font>

![](http://i.imgur.com/285fQZi.png)

+ 创建部署默认值

<font face="微软雅黑" size="2">点击默认值选项卡进入部署默认值信息页面，点击左上角创建部署默认值按钮，即可对部署默认值进行创建，完成后点击保存提交。</font>

![](http://i.imgur.com/nAM06br.png)

对已创建的默认值，可以对其进行编辑与删除

![](http://i.imgur.com/hrbsGUT.png)

###<font face="微软雅黑" size="2">部署组添加服务器</font>

点击部署组名称进入部署组详情页，点击添加服务器按钮，选择要添加主机的云环境，选定后进入服务器模板选择页面，根据选定服务器模板创建实服务器。根据服务器模板创建实例的步骤参见设计-服务器模板模块相关说明。

![](http://i.imgur.com/ZkLmb3N.png)

![](http://i.imgur.com/RXAA3Xr.png)

###<font face="微软雅黑" size="2">添加已创建实例</font>

点击部署组名称进入部署组详情，点击添加已创建实例即可将已创建实例加入当前部署组中管理。

![](http://i.imgur.com/IJVtAuV.png)

###<font face="微软雅黑" size="2">克隆部署组</font>

克隆操作会复制出一个与被克隆对象信息完全相同的副本，该副本可以用来备份或者根据需要进行修改。
点击需要克隆的部署组，进入其详细信息页面，点击页面上方克隆按钮，即可完成克隆操作。克隆后的部署组除了关联信息与版本信息外，其他内容都与原部署组完全一致。

![](http://i.imgur.com/jCHKjms.png)

###<font face="微软雅黑" size="2">删除部署组</font>

删除操作可以通过部署组列表中删除操作或者进入部署组详情页点击删除部署按钮进行删除。

![](http://i.imgur.com/McjYqle.png)


## <font face="微软雅黑" size="4">实例与服务器</font> ##

<font face="微软雅黑" size="2">支持Vmware、OpenStack、阿里云等各环境主机实例自动化创建，删除，开机，关机，Tag添加删除等功能；支持根据服务器模板自动化部署应用脚本、配置告警策略。
支持主机基本信息查询，容器管理，监控信息查询，脚本查询，审计信息查看，卷管理，告警信息，控制台日志查看等功能；
提供非云环境主机导入功能，配置主机登录方式进行接管，如果是物理机可配置IPMI信息，进行带外管理功能</font>

![instenceList](http://i.imgur.com/5Z70iS9.png)

### <font face="微软雅黑" size="2">导入实例</font>

<font face="微软雅黑" size="2">点击实例&服务器页面左上方导入实例按钮，您可以选择接入其他云环境下实例，点击进入下一步配置实例信息，配置完成后点击提交，完成导入。</font>

![](http://i.imgur.com/yNgBhSF.png)

![](http://i.imgur.com/8hl1a2u.png)


### <font face="微软雅黑" size="2">创建实例</font>

<font face="微软雅黑" size="2">点击实例&服务器页面左上方创建实例按钮，第一步首先在下拉菜单选择被创建实例的云环境</font>

![](http://i.imgur.com/4G7frZ4.png)


<font face="微软雅黑" size="2">第二步在弹出窗口选择您想创建的实例类型，点击创建进入实例信息编辑页面。可选择直接根据已有镜像创建一个实例或者根据服务器模板在部署组上创建一个服务器。利用服务器模板创建请参见设计-服务器模板中服务器创建的说明。此处选择直接创建实例进入镜像选择页面</font>

![](http://i.imgur.com/ZOd3LPJ.png)

![](http://i.imgur.com/rEoLvej.png)

选择镜像后点击进入实例配置页面

![](http://i.imgur.com/VqHDh40.png)

填写实例相关配置信息，点击下一步进入信息确认页面，确认无误后，点击完成，可以创建不启动的实例，点击创建，可以创建启动的实例。

![](http://i.imgur.com/u5HWDM7.png)


###<font face="微软雅黑" size="2">实例操作——创建、添加标签、启动、关机、重启、移动</font>

<font face="微软雅黑" size="2">点击实例&服务器页面左上方操作的下拉菜单，选择您想进行的操作。</font>

![](http://i.imgur.com/JAs7lV5.png)

###<font face="微软雅黑" size="2">实例详情配置</font>

点击实例列表中详情操作进入实例详情配置页面，实例详情页面可以显示已接入实例的详情，磁盘，脚本，参数配置，告警，任务，日志信息。在详情页面也可对脚本，脚本参数以及告警信息进行配置。

![](http://i.imgur.com/JHfF3xr.png)


###<font face="微软雅黑" size="2">删除实例</font>

在实例信息管理列表，点击删除操作即可删除实例。

![](http://i.imgur.com/YHU3kBD.png)

## <font face="微软雅黑" size="5">网络管理</font> ##

###<font face="微软雅黑" size="2">查看网络信息</font>

点击管理菜单下网络管理，即可查看各云环境下网络信息。

![](http://i.imgur.com/8R2EO0D.png)

###<font face="微软雅黑" size="2">添加vmware网络信息</font>

点击管理-网络管理，选中vmware云环境，查看对应网络信息，在网络列表上方点击创建网络，即可创建新的网络。

![](http://i.imgur.com/IkIGW6m.png)

###<font face="微软雅黑" size="2">编辑vmware网络信息</font>
点击管理-网络设置，对于vmware网络，可以点击编辑操作对其网络设置进行编辑。

![](http://i.imgur.com/gmHiTJ0.png)

###<font face="微软雅黑" size="2">查看vmware网络IP列表</font>

IP列表显示了网络找中所有的IP以及IP目前的占用状态信息。

![](http://i.imgur.com/XAsW2xi.png)

###<font face="微软雅黑" size="2">删除vmware网络</font>

对于vmware网络，可以点击删除操作删除网络。

![](http://i.imgur.com/rarDJUE.png)



