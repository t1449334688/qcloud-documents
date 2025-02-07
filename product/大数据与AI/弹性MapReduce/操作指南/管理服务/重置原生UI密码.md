## 功能介绍
软件 WebUI 入口功能是 EMR 提供的组件 WebUI 访问能力，访问地址需要进行身份验证，用户名为 root，默认密码为创建集群时输入的密码。EMR 支持用户在遗忘 WebUI 密码时，在控制台重置 WebUI 密码。本文为您介绍通过控制台重置 WebUI 密码的操作。
## 操作步骤
1. 登录 [EMR 控制台](https://console.cloud.tencent.com/emr)，在集群列表中单击对应的集群 **ID/名称**进入集群详情页。
2. 在集群详情页中单击**集群服务**，然后单击左上角**重置 WebUI 密码**进行密码重置。
>!
>- 密码要求：8-16个字符，至少包含大写字母、小写字母、数字和特殊字符（!@#%^*）中的三种，其中第一个字符不能为特殊字符。
>- 已安装 OpenLDAP 的集群（EMR-V2.6.0 和 EMR-V3.2.1 以后产品版本），密码调整只能在用户管理页面进行管理。如需重置 WebUI 密码，请在用户管理页面，使用新建用户功能进行操作。

![](https://qcloudimg.tencent-cloud.cn/raw/4a2b6aecc83d19df2571760dbea9db93.png)
