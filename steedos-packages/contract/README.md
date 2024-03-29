
<p align="center">
  <a href="https://www.steedos.com/cn">
    <img alt="华炎合同管理系统" src="https://steedos.github.io/assets/logo.png" width="120" />
  </a>
</p>
<h1 align="center">
  华炎合同管理系统
</h1>

<p align="center">
<a href="./README_en.md">English</a>
<a href="https://www.steedos.cn/docs/"> · 文档</a>
<a href="https://www.steedos.cn/videos/"> · 视频</a>
<a href="https://demo.steedos.cn"> · 试用</a>
</p>

<p align="center" style="border-top: solid 1px #cccccc">
  合同管理是落实企业风险管理和内部控制的一项核心的管理业务，合同管理的好坏直接影响企业的经营绩效。借助华炎合同管理系统，你能够集中进行合同存储，提高合规性，自动化和加快整个合同生命周期，并获得更多其他业务优势。

</p>

<h3 align="center">
 🤖 🎨 🚀
</h3>

![合同界面图](https://steedos.github.io/assets/github/contract/cn/contract.png)

- [视频演示](https://www-steedos-com.oss-cn-beijing.aliyuncs.com/videos/creator/contracts-demo.mp4)
- [文档](https://www.steedos.cn/docs)


### ✨规范和控制合同审批流程

华炎魔方内置专业的流程引擎，对于合同管理中的各种事项，只需简单配置，就能实现电子化审批。

- 合同签署
可以在电脑端和手机端发起合同审批并处理。审批过程中，会保存合同文本的所有版本。合同审批发起后，合同信息自动进入合同台账

- 付款申请
基于付款计划发起付款申请流程。付款申请完成后，系统自动更新合同台账信息、付款计划执行信息，同时也可以自动将付款单的详细信息通过接口传入财务管理系统。

- 供应商资质审查
可以设定供应商准入流程。在系统里发起审查，填写信息、上传资质文件，相关人员和各级领导查验信息后核准资质。

### ✨合同范本管理

在一个中央数据库中集中维护整个企业的标准条款、合同模板和政策规则。

- 范本新增与修订
合同范本新增或修订时，必须严格按照公司规章制度进行审批，审批通过自动存入范本库。

- 范本编辑控制
引用合同范本时，合同中不可修订条款在合同编辑过程中是只读的，用户只能修改合同中允许编辑的指定位置。

- 范本使用权限
限制范本的可用部门、可用人员，也可以限制调用接口生成范本的第三方应用程序。

- 自动化处理
范本中可设定变量，第三方业务系统可以通过标准API，传入参数，从范本自动生成带水印的PDF文件。

### ✨支持电子签名，节约成本

通过添加电子签名功能，你可以省去邮寄和签署多份合同副本的步骤，节约时间和成本。

- 证书管理
统一管理公司所有员工、供应商、客户以及合作伙伴的电子签名证书。

- 电子签章
对合同加盖电子印章，并使用电子证书对文件进行签名和加密。

- 签章验证
可随时查看和校验电子签名的有效性。合同如果被篡改，签名自动失效。

### ✨PC、移动一体化
合同管理的各项功能，包括对流程发起、审批和监控都可以扩展到移动端，即时领导出差，一部手机，即可实现随时随地管理合同、使用签章、监控执行、预警风险。签署更高效，管理更便捷。

- 消息推送
有新的待处理事项时，华炎魔方手机客户端会自动弹出推送提醒。

- 个性化手机界面
只需简单配置，就能定制你的专属手机客户端。

### ✨收付款管理
收付款管理功能可以帮您确保数据安全，减少繁琐的手动审批环节

- 收款计划
合同审批单中收款计划信息会同步进入台账信息中，如审批单中没有填写收款计划，执行人也可以在台账的收款计划中进行补录，也可以随时更新计划。可以对收款节点设置提醒功能。

- 收款记录
收款成功后，数据自动同步到台账中，点击收款说明，进入详细数据页，就能查看相关信息。

- 付款计划
审批单中付款计划信息会同步进入台账信息中，如审批单中没有填写付款计划，执行人也可以在台账的付款计划中进行补录。

- 付款记录
付款成功后，相关数据会自动同步到台账信息中，点击合同名称，就能看到付款记录的详细信息。

### ✨发票管理
可以将业务系统和财务系统生成的各种电子发票进行统一合规的管理，完成电子发票的采集，保存，查询，归档等一系列的操作。并且严格按照国家的政策的规定，帮您预警风险。

- 合规监测
入账发票相关数据真实可靠，查验速度快

- 风险预警
对不合规以及重复报销等及时提醒

- 数据与凭证关联
在发票检索方面只要知道发票某一个参数就可以查看到已经归档的发票，方便后续在税务稽查中快速应对。

### 源码解析

每个企业因行业不同、规模不同、业务不同，合同管理的要素和侧重点也不一样。华炎合同管理系统基于Creator“低代码”平台开发，在提供强大功能的同时，按需定制也非常方便。开发人员无需编写代码，只需调整配置文件，即可快速满足业务部门的需求。


# 快速向导

## 配置环境变量

创建 .env.local，[配置系统环境变量](https://docs.steedos.cn/zh-CN/deploy/steedos-config/) 。 

```bash
ROOT_URL=
```

## 启动华炎魔方平台

开发软件包之前，先启动华炎魔方服务。

1. 使用 docker 启动华炎魔方平台。

推荐使用 docker 启动华炎魔方平台，会自动启动所有依赖服务。

```bash
docker-compose up
```

2. 使用 nodejs 启动华炎魔方平台。

也可以使用 nodejs 启动华炎魔方，需在本地先安装 mongodb, redis 和 nats，或使用 docker 启动相关依赖服务。

```bash
yarn start:db
yarn start:platform
```

## 访问华炎魔方

打开浏览器，访问 http://127.0.0.1:5000，进入华炎魔方。

进入设置应用，可以：
- 创建自定义对象
- 创建应用
- 创建微页面

## 启动合同管理软件包

可以使用微服务的方式扩展华炎魔方。例如本项目基于华炎魔方开发了合同管理解决方案。

可以参考 steedos-packages 文件夹下的例子。

```bash
yarn
yarn start
```

### 了解更多

[关于 Steedos 低代码开发平台](http://docs.steedos.com/)

### 保持联系

如果您有任何疑问或想与其他华炎魔方用户交谈，请[点击进入讨论](https://github.com/steedos/steedos-app-contract/discussions)或扫码添加以下联系方式与我们联系！

### 开发人员微信群


如果您有任何疑问或想与其他华炎魔方用户交谈，请扫码添加以下联系方式与我们联系。

| ![开发者微信交流群](https://steedos.github.io/assets/github/platform/cn/QR_wechat_developers.jpg) | ![商务咨询](https://steedos.github.io/assets/github/platform/cn/business_consulting.jpg)        | ![微信公众号](https://steedos.github.io/assets/github/platform/cn/public_number.jpg)|
| :-----: | :-----: | :-----: |
| 开发人员微信群  | 商务咨询  | 微信公众号 |
