##### 5.2.3.1 任务设置

首先为新建的 HR模板添加对应的任务类型，在【任务设置】中点击【添加任务类型】选取对应的任务类型；

# ![](/assets/2任务设置-添加任务类型.png)

# ![](/assets/2任务设置-添加任务类型2.png)

然后对添加的几个任务类型依次进行详细的设置，设置方法参考下面得步骤；

# ![](/assets/2任务设置-任务类型设置.png)


**1）权限设置**

一个角色模式至少对应一个权限模式，所以在创建任务类型时，一旦选定角色模式，该任务类型就会有该角色模式下的权限模式；

若一个角色模式有多个权限模式，在对项目模板中的任务类型进行设置的时候，可以通过【设置权限模式】选择该角色模式下不同的权限模式；

# ![](/assets/2任务设置-设置权限模式-正确.png)

**2）安全设置**

* 创建安全模式

在项目模板中对任务类型进行【安全设置】前，需要先在【配置中心】→【安全】→【安全管理】中创建“HR角色模式”下的安全模式即“HR安全模式”；一个角色模式可以有多个安全模式。

# ![](/assets/2.2任务设置-安全设置-创建安全模式1.png)

# ![](/assets/2.2任务设置-安全设置-创建安全模式2.png)

# ![](/assets/2.2任务设置-安全设置-创建安全模式3.png)


新建安全模式之后，需要对新创建的安全模式进行配置，每个安全模式中包含若干安全级别，一个角色对应一个安全级别（包括系统角色和自定义角色），一个任务可以设置多个安全级别（即可对多个角色可见）。

# ![](/assets/2.2任务设置-安全模式配置.png)

# ![](/assets/2.2任务设置-安全模式配置-新建安全级别.png)

# ![](/assets/2.2任务设置-安全模式配置-新建安全级别2.png)

* 安全设置

在【安全管理】中设置该该任务类型的角色模式下的安全模式后，就可以在项目模板-【任务类型设置】-【安全设置】中选择安全模式（若有多个安全模式可在创建的安全模式中备注说明不同之处。

# ![](/assets/2.2任务设置-安全设置.png)

# ![](/assets/2.2任务设置-安全设置2.png)


3）**提醒设置**

* 创建提醒模式

在项目模板中对任务类型进行【提醒设置】前，需要先在【配置中心】→【高级】→【提醒管理】中创建“HR角色模式”下的提醒模式即“HR提醒模式”；一个角色模式可以有多个提醒模式。

# ![](/assets/2.3提醒设置-创建提醒模式1.png)

# ![](/assets/2.3提醒设置-创建提醒模式2.png)

# ![](/assets/2.3提醒设置-创建提醒模式3.png)

新建提醒模式之后，需要对新创建的提醒模式进行配置，首先要【新建提醒】，创建的提醒可以是任务中任何有关时间的属性（即任务属性中的日期属性）。

# ![](/assets/2.3提醒设置-提醒模式配置.png)

# ![](/assets/2.3提醒设置-新建提醒1.png)

创建提醒后，再为提醒设置【提醒对象】，提醒对象可以有多个（提醒对象可以是自定义角色也可以是系统角色）。

# ![](/assets/2.3提醒设置-设置提醒对象.png)

* 提醒设置

在【提醒管理】中设置提醒模式后，就可以在项目模板-【任务类型设置】-【提醒设置】中选择提醒模式（若有多个提醒模式可在创建的提醒模式中备注说明不同之处）。

# ![](/assets/2.3提醒设置-设置提醒1.png)

# ![](/assets/2.3提醒设置-设置提醒2.png)

4) **通知设置**

在项目模板中对任务类型进行【提醒设置】前，需要先在【配置中心】→【高级】→【通知管理】中创建“HR角色模式”下的提醒模式即“HR通知模式”；一个角色模式可以有多个通知模式。

* 创建通知模式

# ![](/assets/2.4通知设置-新建通知模式.png)

# ![](/assets/2.4通知设置-新建通知模式2.png)

* 通知【事件管理】

新建通知模式之后，需要对新创建的通知模式进行配置，首先将需要通知的事件【添加事件通知】

# ![](/assets/2.4通知设置-新建通知模式-配置.png)

# ![](/assets/2.4通知设置-新建通知模式-添加事件通知.png)

# ![](/assets/2.4通知设置-新建通知模式-添加事件通知2.png)

如果需要通知的事件在“事件库”中没有，则需要在【高级】→【事件管理】中【新建事件】

# ![](/assets/2.4通知设置-高级-事件管理-新建事件1.png)

# ![](/assets/2.4通知设置-高级-事件管理-新建事件2.png)


再为事件通知设置【通知对象】，通知对象可以有多个（通知对象可以是自定义角色也可以是系统角色。

# ![](/assets/2.4通知设置-设置通知对象.png)

* 设置通知

在【通知管理】中设置通知模式后，就可以在项目模板-【任务类型设置】-【通知设置】中选择通知模式（若有多个通知模式可在创建的通知模式中备注说明不同之处）；

# ![](/assets/2.4通知设置-设置通知模式1.png)

# ![](/assets/2.4通知设置-设置通知模式2.png)

5) **标签设置**

标签模式与角色模式之间没有对应关系，标签模式在【配置中心】→【任务】→【标签管理】中统一管理，可以创建多个标签模式，每个标签模式中可以设置多个标签；

* 新建标签模式

# ![](/assets/2.5标签管理-新建标签.png)

# ![](/assets/2.5标签管理-新建标签2.png)

为标签模式【HR标签管理模式】配置合理的任务标签

# ![](/assets/2.5标签管理-标签模式管理.png)

* 设置标签模式

标签设置与其他项的设置不同，标签属于任务属性，因此，如果要为任务类型设置标签模式，需要在任务类型配置时，在【属性设置】→【设计任务】→【任务设计器】中添加“标签”控件，然后在对项目模板中的任务类型设置时选择该任务类型需要的标签模式；

# ![](/assets/2.5标签管理-任务设计器.png)


# ![](/assets/2.5标签管理-设置标签模式1.png)

# ![](/assets/2.5标签管理-设置标签模式2.png)

# ![](/assets/2.5标签管理-设置标签模式3.png)






