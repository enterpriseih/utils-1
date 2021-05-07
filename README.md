# utils




JavaScript常用函数库

项目中常用到的函数集合，如文本截取等


## 安装

### 直接用  <code style='color: #d63200'>&lt;script&gt;</code>  引入

直接下载并用 `<script>` 标签引入，`jutils` 会被注册为一个全局变量。

``` html
<script src="jutils.min.js"></script>
<script>
  var browser = jutils.getBrowserInfo()
</script>
```

#### CDN

你也可以这样使用最新版本：

```html
<script src="https://cdn.jsdelivr.net/npm/@wangxiaoxiao45/utils"></script>
```



### NPM

在 jutils 应用于大型项目时推荐使用 NPM 安装。NPM 能很好地和 webpack 模块打包器配合使用。

``` bash
# 最新稳定版
$ npm install @wangxiaoxiao45/utils
```
