# 使用说明

## 安装依赖

pnpm install

## 启动

pnpm run dev

## 创建新组件

pnpm run new

## 编写文档

## git 提交

首先将要提交的文件进行 add 操作再于终端中输入此指令： pnpm run commit

图快，也可以直接输入以下格式进行提交提交格式为： 关键字: 提交内容  
注意，中间为冒号后接空格关键字参考如下：

- chore：构建配置相关。
- docs：文档相关。
- feat：添加新功能。
- fix：修复 bug。
- pref：性能相关。
- refactor：代码重构，一般如果不是其他类型的 commit，都可以归为重构。
- revert：分支回溯。
- style：样式相关。
- test：测试相关。

参考文档

- https://juejin.cn/post/6844903710112350221

# 以下内容为原项目参考信息

## React 组件库搭建指南

- [React 组件库搭建指南（一）：项目初始化](https://github.com/worldzhao/blog/issues/3)
- [React 组件库搭建指南（二）：开发调试](https://github.com/worldzhao/blog/issues/4)
- [React 组件库搭建指南（三）：编译打包](https://github.com/worldzhao/blog/issues/5)
- [React 组件库搭建指南（四）：单元测试](https://github.com/worldzhao/blog/issues/6)
- [React 组件库搭建指南（五）：标准化发布流程](https://github.com/worldzhao/blog/issues/7)

[🚀 在线预览](https://worldzhao.github.io/react-ui-library-tutorial)

🚆 本地预览

```bash
git clone git@github.com:worldzhao/react-ui-library-tutorial.git
cd react-ui-library-tutorial
pnpm install
pnpm start
```

按顺序执行完命令后，即可在 localhost:8000 端口看到以下内容：

![preview](https://raw.githubusercontent.com/worldzhao/blog/master/images/rc-lib-v1-1.jpg)

## 概览

本系列文章主要包含以下内容：

- 项目初始化: 组件库前期开发准备工作。`eslint`/`commit lint`/`typescript`等等；
- 开发阶段: 使用 [dumi](https://d.umijs.org/zh-CN) 进行开发调试以及文档编写；
- 打包阶段: 输出~~`umd`~~/`cjs`/`esm`产物并支持按需加载；
- 组件测试: 使用`@testing-library/react`及其相关生态进行组件测试；
- 发布 npm: 编写脚本完成发布或直接使用 [np](https://www.npmjs.com/package/np) 发布；
- 部署文档站点: 使用 Github Pages 以及 Github Actions 完成文档站点自动部署。
