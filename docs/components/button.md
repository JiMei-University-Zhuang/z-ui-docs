# Button 按钮

常用的操作按钮。

## 基础用法

基础的按钮用法。

:::demo

```vue
<template>
<z-button>默认按钮</z-button>
<z-button type="primary">主要按钮</z-button>
<z-button type="success">成功按钮</z-button>
<z-button type="warning">警告按钮</z-button>
<z-button type="danger">危险按钮</z-button>
</template>
```
:::

## 按钮属性

| 属性名  | 说明     | 类型    | 可选值                                      | 默认值 |
|---------|----------|---------|---------------------------------------------|--------|
| size    | 尺寸     | string  | large / default / small                     | default|
| type    | 类型     | string  | primary / success / warning / danger / info | —      |
| plain   | 是否朴素 | boolean | —                                           | false  |
| round   | 是否圆角 | boolean | —                                           | false  |
| loading | 加载状态 | boolean | —   