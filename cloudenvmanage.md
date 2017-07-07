# <div align="center" ><font face="微软雅黑" size="5">云环境管理</font></div> #

<font face="微软雅黑" size="2">

## <font face="微软雅黑" size="4">接入阿里云、AWS、腾讯云、微软云环境</font> ##
<font face="微软雅黑" size="2">

点击顶端导航栏云环境，下拉列表会显示所有云环境列表，点击底部云环境配置，进入云环境配置页面。

![](http://i.imgur.com/85NkkoY.png)

点击左上角添加云环境，在弹出窗口选择您需要接入的云环境类型，点击下一步

![](http://i.imgur.com/b6lwnC5.png)


填写云环境名称、描述、云账号ID、Access Key ID和Access Key Secret以及云环境同步周期。其中云环境名称是必填项目，云环境描述是对云环境的基本说明，Access Key ID，Access Key Secret得在您的阿里云或腾讯云账户里查看，请一定填写正确，云环境同步周期是rightcloud平台与您接入的云环境平台数据同步的周期，您可以根据需要设定周期时间。

![](http://i.imgur.com/jHO5xtG.png)


添加云环境完成后，平台会验证您输入的信息，如果云环境验证通过，您就可以在RightCloud平台查看并管理您的云环境了。如果验证不通过，请检查您输入的账户信息，确保账户信息准确无误。

![](http://i.imgur.com/4TtgqLB.png)


## <font face="微软雅黑" size="4">接入VMware、OpenStack、PowerVC环境</font> ##

<font face="微软雅黑" size="2">

同样的，在点击添加云环境后，选择私有云环境，填写管理员或租户的地址、用户名、密码等信息，点击提交，若信息填写无误，会在页面右下角绿色提示“云环境添加成功”，否则提示"云环境验证不通过"，然后在云环境列表会展示所添加的云环境。

选择私有云环境

![](http://i.imgur.com/L37ruOj.png)


+ 接入openstack环境

填写环境名称，根据需要填写云环境描述，填写用户身份验证地址，租户名称，租户用户名，租户用户密码，设定云环境同步周期，点击完成进行云环境验证。如果身份验证地址以及租户账户信息填写无误，云环境将会成功接入。

![](http://i.imgur.com/LvDMvwW.png)

+ 接入VMware云环境

首先在接入云环境时选择云环境类型为VMware，点击下一步进入云环境添加页面

![](http://i.imgur.com/1MahNw2.png)

在VMware云环境添加页面填写云环境名称，填写云环境描述，VMware管理地址，管理员账号以及密码，设定环境同步周期，确认账户信息准确无误后，点击完成，平台将会进行云环境验证操作，验证通过后，云环境将会成功接入。

![](http://i.imgur.com/4rvhfYo.png)



## <font face="微软雅黑" size="4">云环境管理</font> ##

+ <font face="微软雅黑" size="2">云资源查看</font>

<font face="微软雅黑" size="2">
云环境成功接入后，点击“云环境”下三级菜单，可查看各云环境资源统计概览信息展示，实例/虚拟机、镜像、实例类型、分区/数据中心、SSH密钥、安全组、弹性IP、硬盘、私有网络、宿主机、数据存储、网络信息查询，管理等信息。

![](http://i.imgur.com/h3KiHv3.png)

![](http://i.imgur.com/5diI8sR.png)

![](http://i.imgur.com/Xki6U0h.png)

+ <font face="微软雅黑" size="2">编辑云环境名称或描述</font>

<font face="微软雅黑" size="2">
在云环境配置页面，选中已接入云环境列表中需要编辑的云环境，点击操作中的编辑，即可对云环境的名称和描述进行修改与提交。

![](http://i.imgur.com/WsLneRC.png)

![](http://i.imgur.com/LqDOQZB.png)

+  <font face="微软雅黑" size="2">删除云环境</font>


<font face="微软雅黑" size="2">
您可以将已经接入RightCloud平台的云环境进行删除，首先进入云环境配置页面，选中云环境列表中需要删除的云环境，点击删除确认即可。删除后将会在平台上清除该云环境下所有的同步信息与关联关系。

![](http://i.imgur.com/h8QRK5M.png)



