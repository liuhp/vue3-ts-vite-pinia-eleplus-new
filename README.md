# Me-admin template
## 简介
vue3、vite4、 pinia、 elment-plus

## 特性
 - **基于vue3、vite4、pinia、elment-plus、vue-request@next**
 - **基于typescript** 应用级JavaScript 的语言
 - **可配置主题** 可配置主题色及主题模式
 - **友好的国际化方案** 基于vue-i18n 支持按组件异步加载语言包。
 - **自定义keepAlive缓存** 可根据key进行vue keep-alive,解决不同路由使用同一组件不能独立刷新缓存问题
 - **权限** 内置完善的动态路由权限生成方案，按钮级权限。支持前端菜单和接口动态获取菜单两种模式
 - **Mock 数据** 内置mock数据方案便于测试
 - **组件自动引入** 自动按需引入components下的组件定义，可以自定义引入模式和模板，真正的按需引入
 - **便捷的类型自动生成** 自动生成ts type 最大程度减少工作量
 - **友好的request封装** 基于vue-request+axios的request api封装和vue3响应式语法糖深度耦合。

## 快速开始

 nodejs版本建议>=16.15.1

- clone 代码
```
git clone https://github.com/liuhp/vue3-ts-vite-pinia-eleplus-new.git
```
- 安装依赖
```
    cd vue3-ts-vite-pinia-eleplus-new
    npm install
```
- 本地运行
```
    npm run dev
```
- 打包
```
    npm run build
```

## Git 贡献提交规范
- 需符合 [commitlint](https://commitlint.js.org/#/concepts-commit-conventions)规范，建议安装`vscode`的`Conventional Commits`扩展
  - `feat`  新功能
  - `fix`  Bug 修复
  - `chore` 杂物处理
  - `docs` 文档更改
  - `style` 样式更改
  - `refactor` 重构
  - `perf` 性能改进
  - `test` 测试添加/更正
  - `revert` 还原提交
  - `ignore` 临时暂存可忽略
  - `ci` CI发版
