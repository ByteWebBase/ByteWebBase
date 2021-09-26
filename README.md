# ByteWebBase

![](https://moonstarimg.oss-cn-hangzhou.aliyuncs.com/picgo_img/20210925224505.png)

为了最大程度的让组员参与进来，我们选择了 ByteWebBase 面向 Web 前端研发的基础设施作为项目的方向，包含 ByteDBDocs、ByteApiCLI、ByteApiTestTool、ByteVitePressCLI、ByteGitStat、ByteWebMonitor 六大部分。

(以下仓库将在 9 月 26 日 12:00 对外开放~)

[1. ByteDBDocs 管善鑫 张群清 xxx ](https://github.com/ByteWebBase/ByteDBDocs)

[2. ByteApiCLI 胡文兴 xxx xxx](https://github.com/ByteWebBase/ByteDBDocs)

[3. ByteApiTestTool 司徒永聪 xxx xxx](https://github.com/ByteWebBase/ByteApiTestTool)

[4. ByteVitePressCLI 杨嘉兴 xxx xxx](https://github.com/ByteWebBase/ByteVitePressCLI)

[5. ByteGitStat 陈池轩 xxx xxx](https://github.com/ByteWebBase/ByteGitStat)

[6. ByteWebMonitor](https://byte-web-monitor.vansin.top/)

[答辩 PPT 地址](https://fyctfmijjr.feishu.cn/file/boxcnLU57KRENXh2W9WuDVe4Npb)

## 平台架构

![](https://moonstarimg.oss-cn-hangzhou.aliyuncs.com/picgo_img/20210925231237.png)

## [1. ByteDBDocs](https://github.com/ByteWebBase/ByteDBDocs)

dbml 数据库表格配置文件生成数据库可视化表格

### 开发流程思路

1. 通过包读取.dbml 文件并得到 db 对象
2. 根据 db 对象生成`mock.ts`
3. 将`mock.ts`加入模板中，并使用`antv x6`进行可视化渲染

### 实现效果

编译
![](./source/image1.gif)

启动服务
![](./source/image2.gif)

打开界面
![](./source/image3.gif)

### 参考资料

[antv x6](https://x6.antv.vision/zh/docs/tutorial/about)

[DBML api](https://www.dbml.org/js-module/#api)

## [2. ByteApiCLI](https://github.com/ByteWebBase/ByteApiCLI)

dbml 配置文件生成 Restful 接口 Koa 工程

### Github OAuth 登录

Github OAuth 登录后才能使用脚手架的其他功能，便于自动收集脚手架用户的使用情况

### pre-commit 代码审查

![](https://moonstarimg.oss-cn-hangzhou.aliyuncs.com/picgo_img/husky_lint.gif)

## [3. ByteApiTestTool](https://github.com/ByteWebBase/ByteApiTestTool)

Api 测试工具——用注释包围关键代码即可调试 免去频繁复制粘贴所带来的麻烦

[![4ymWUP.gif](https://z3.ax1x.com/2021/09/26/4ymWUP.gif)](https://imgtu.com/i/4ymWUP)

## [4. ByteVitePressCLI](https://github.com/ByteWebBase/ByteVitePressCLI)

基于 vitepress 的文档脚手架，支持约定路由

## [5. ByteGitStat](https://github.com/ByteWebBase/ByteGitStat)

Git 相关数据统计工具

## [6. ByteWebMonitor](https://byte-web-monitor.vansin.top/)

Web 前端监控一站式解决方案

<!-- ![](https://moonstarimg.oss-cn-hangzhou.aliyuncs.com/picgo_img/b8.gif) -->

![](https://moonstarimg.oss-cn-hangzhou.aliyuncs.com/picgo_img/bbbb9.gif)
