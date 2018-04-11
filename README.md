# <%= name %>

一句话介绍项目摘要。


#### demo（demo仍然走unpkg服务）
<a href="http://unpkg.smfe.sina.cn/<%= name %>/dist/demo/index.html" target="blank">http://unpkg.smfe.sina.cn/<%= name %>/dist/demo/index.html</a>

#### umd 路径（如果不提供umd，请手动删除）
说明：自spkg2.0版本之后将支持多出口js 上传umd到mjs服务中，请维护好如下umd路径，以及调用方法，供大家使用

## umd 调用方式：
```
<script src="mjs.sinaimg.cn/cnpm/@mfelibs/xxxx@1.0.0/main.all.js"></script>

```

## cmd 调用方式：

### 安装

```bash
yarn add  @mfelibs/Foo --save
```

通过 `imort` 导入
```javascript
import Foo from '@mfelibs/Foo'
```

### 使用

调用 `Foo` 构造函数，实例化组件对象:
```javascript
const foo = Foo({
  param1: 'test',
  param2: true
})
```

### 配置

#### param1

`String` 类型，用于 xxx，默认值为 `'default'`

#### param2

`Boolean` 类型，用于 xxx，默认值为 `false`


### 属性

#### prop1

属性描述

#### prop2

属性描述

### 方法

#### someMethod

接受几参数，参数类型，表现

示例：
```javascript
foo.someMethod('xxx', 'xxx')
```

