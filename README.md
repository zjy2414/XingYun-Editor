![行云](https://7463-tcb-nkd87viq9wheg653bca0d-a8621b-1304207482.tcb.qcloud.la/XingYun/行云截图.png)

# 行云（XingYun）- Serverless函数工作流可视化编辑器

<p align="center" class="flex justify-center">
    <a href="https://www.serverless-devs.com" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=start-xingyun&type=packageType">
  </a>
  <a href="http://www.devsapp.cn/details.html?name=start-xingyun" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=start-xingyun&type=packageVersion">
  </a>
  <a href="http://www.devsapp.cn/details.html?name=start-xingyun" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=start-xingyun&type=packageDownload">
  </a>
</p>

-> [立即体验](https://xingyun.doyi.online) <-

<description>

> Serverless工作流在未来拥有巨大的潜力，主流云厂商都已上线了相关Serverless产品，但在行云出现之前，用户只能以DSL的方式编排函数工作流，行云（XingYun）为解决该问题而诞生。

</description>

<table>

## 前期准备
使用该项目，推荐您拥有以下的产品权限 / 策略：

| 服务/业务 | 函数计算            |
| --------- | ------------------- |
| 权限/策略 | AliyunFCFullAccess  |
| 权限/策略 | AliyunOSSFullAccess |


</table>

<codepre id="codepre">

# 代码 & 预览

- [:smiley_cat: 源代码](https://github.com/zjy2414/start-xingyun)

- [:rocket: 预览](https://xingyun.doyi.online)

</codepre>

<deploy>

## 部署 & 体验

<appcenter>

- :fire: 通过 [Serverless 应用中心](https://fcnext.console.aliyun.com/applications/create?template=start-xingyun) ，
[![Deploy with Severless Devs](https://img.alicdn.com/imgextra/i1/O1CN01w5RFbX1v45s8TIXPz_!!6000000006118-55-tps-95-28.svg)](https://fcnext.console.aliyun.com/applications/create?template=start-xingyun)  该应用。 

</appcenter>

- 通过 [Serverless Devs Cli](https://www.serverless-devs.com/serverless-devs/install) 进行部署：
    - [安装 Serverless Devs Cli 开发者工具](https://www.serverless-devs.com/serverless-devs/install) ，并进行[授权信息配置](https://www.serverless-devs.com/fc/config) ；
    - 初始化项目：`s init start-xingyun -d start-xingyun`   
    - 进入项目，并进行项目部署：`cd start-xingyun && s deploy -y`

</deploy>

<appdetail id="flushContent">

## 简介（Introduction）

Serverless工作流在未来拥有巨大的潜力，主流云厂商都已上线了相关Serverless产品，但在行云出现之前，用户只能以DSL的方式编排函数工作流，行云（XingYun）为解决该问题而诞生。

目前，行云已经支持阿里云函数工作流可视化元素[包括pass, task, wait, parallel, choice(condition, default), foreach, succeed, fail]与FDL（工作流流程定义语言）的双向转换，即同时支持可视化拖拽方式创建和编辑FDL。

可能还存在潜在bug，欢迎前来修复或贡献新功能～

## 功能介绍（Features）

* 可视化创建工作流： <br/>
    全程可视化操作，只需拖拽即可定义流程，连线即可定义执行顺序。
* 可视化编辑已有的工作流： <br/>
    因为行云已经支持FDL与可视化元素间的双向转换，用户能够以与创建工作流相同的体验来编辑工作流。
* 一键部署： <br/>
    流程定义/修改完成后可以直接一键部署至阿里云函数工作流服务。

## 未来（Todo）

* 支持每个步骤的入参和出参设置
* 支持腾讯云、华为云的函数工作流可视化编辑

</appdetail>

<devgroup>

## 技术支持

微信(Wechat): zjy2414

邮箱(E-Mail): zjy2414@outlook.com

</devgroup>