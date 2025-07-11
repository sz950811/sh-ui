## Sh-UI

ShUI 组件库用于统一项目开发而存在，基于 element-ui 二次定制开发。

目前项目集成了`element-ui@2.15.14`,`vxe-table@2.11.0`,`xe-utels@3.5.31`,`防抖节流函数`,`常用校验规则`等,后续会陆陆续续集成一些通用工具和通用组件。

## 使用方法

```js
// 安装
npm install sh-ui-v2

// main.js中引入
import ShUIV2 from 'sh-ui-v2'

const { ShUI }  = ShUIV2

Vue.use(ShUI)

```

## 组件使用

```html
<template>
  <div>
    <sh-card>卡片</sh-card>
  </div>
</template>

<script>
  export default {
    name: 'App'
  }
</script>
```



