# 定制化 {docsify-ignore}

你可以个性定制你的文档，具体配置请详见下文配置项。

## 配置项

你可以配置在 `window.$docsify` 里。

```html
<script>
  window.$docsify = {
    repo: 'docsifyjs/docsify',
    maxLevel: 3,
    coverpage: true
  }
</script>
```

### el

- 类型：`String`
- 默认值：`#app`

docsify 初始化的挂载元素，可以是一个 CSS 选择器，默认为 `#app` 如果不存在就直接绑定在 `body` 上。

```JS
window.$docsify = {
  el: '#app'
};
```

### repo

- 类型：`string`
- 默认值：`null`

配置仓库地址或者 `username/repo` 的字符串，会在页面右上角渲染一个 * [GitHub Corner](http://tholman.com/github-corners/) 挂件。

```JS
window.$docsify = {
  repo: 'docsifyjs/docsify',
  // or
  repo: 'https://github.com/docsifyjs/docsify/'
};
```

### maxLevel

- 类型：`Number`
- 默认值：`6`

默认情况下会抓取文档中所有标题渲染成目录，可配置最大支持渲染的标题层级。

```JS
window.$docsify = {
  maxLevel: 4
};
```
