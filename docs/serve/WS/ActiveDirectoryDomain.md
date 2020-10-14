# Active Directory 域配置
为什么要使用域？假设你是公司的系统管理员，你们公司有一千台电脑。如果你要为每台电脑设置登录帐户，设置权限(比如是否允许登录帐户安装软件)，那你要分别坐在这一千台电脑前工作。如果你要做一些改变，你也要分别在这一千台电脑上修改。相信没有哪个管理员想要用这种不吃不喝不睡觉的方式来工作，所以就应运而生了域的概念。
下面列出了域的几个主要概念：

**AD的全称是Active Directory**：活动目录
**域（Domain）**:
1)域是Windows网络中独立运行的单位，域之间相互访问则需要建立信任关系(即Trust Relation)。信任关系是连接在域与域之间的桥梁。当一个域与其他域建立了信任关系后
2)两个域之间不但可以按需要相互进行管理，还可以跨网分配文件和打印机等设备资源，使不同的域之间实现网络资源的共享与管理，以及相互通信和数据传输
**域控制器（DC）**：
域控制器就是一台服务器，负责每一台联入网络的电脑和用户的验证工作。
**组织单元（OU）**
**用户名服务器名（CN）**
## Active Directory 域（Domain）

## Active Directory 域控制器（DC）

## Active Directory 组织单元（OU）

## Active Directory 用户名服务器名（CN）