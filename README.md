## Wepy Demo

wepy 让小程序支持组件化开发的框架，一个最受欢迎的小程序框架。

### 为什么要选择WePY？
目前已有超过 5000 位开发者使用或了解本框架, 拥有众多的开发特性和优化方案.

#### 开发风格
接近于 Vue.js，支持组件 Props 传值，自定义事件、组件分布式复用Mixin、计算属性函数computed、模板内容分发slot等等

#### 组件化
组件化开发，完美解决组件隔离，组件嵌套，组件通信等问题

#### NPM
支持使用第三方 npm 资源，自动处理 npm 资源之间的依赖关系，完美兼容所有无平台依赖的 npm 资源包

#### Promise
通过 polyfill 让小程序完美支持 Promise，解决回调烦恼

#### ES2015
可使用 Generator Function / Class / Async Function 等特性，大大提升开发效率

#### 优化
对小程序本身的优化，如请求列对处理，优雅的事件处理，生命周期的补充，性能的优化等等

#### 编译器
支持样式编译器：Less/Sass/Styus，模板编译器：wx-ml/Pug，代码编译器：Babel/Typescript。

#### 插件
支持多种插件处理，如文件压缩，图片压缩，内容替换等，扩展简单,使用方便

#### 框架大小
压缩后 24.3KB 即可拥有所有框架功能，额外增加 8.9 KB后即可使用 Promise 和 Async Function

### 安装使用

``` sh
# install cli
npm install @wepy/cli -g
# init
wepy init standard myproject
# 
cd myproject
# install
npm install
```

``` sh
# clone
git clone https://github.com/LishiJ/wepy_example.git
# install
yarn / npm install
# run
yarn dev
# check
# 在微信开发者工具中打开 dist 目录即可
```