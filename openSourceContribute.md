# 开源贡献流程

## monorepo 目录结构

<!-- ![](./img/2.png) -->
<img src='./img/2.png' width='150'/>

- 在 apps 下是按照不同技术栈划分的小程序工程 wechat 是原生小程序的工程，将来补充 uniapp 的工程。
- miniprogram 是原生小程序的主体。
- components 中存放一些工程的公共组件，assets 存放静态资源
- domains 作为管理工程下所有子包的主包。
- domains 下用不同的行业划分子包，tour（旅游业）就是一个子包。
- mw001（景区列表）是子包 tour 中的一个业务场景
