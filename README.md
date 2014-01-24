## zo-less

简单的 less 工具。主要集成了常用 mixin, IE 兼容性策略。可免费修改使用。

### 代码压缩

	npm install

	gulp

使用 `gulp` 压缩代码。

#### 使用

将 `zo.less` 引入即可将所有的 `mixin` 引入。也可以以 `mixins/variables.less` 的形式引入使用。

### 关于 IE 兼容

更多 IE 兼容性请参考：[CSS PIE](http://css3pie.com/)。

#### 启用 IE 兼容性

```less
@support-ie7: true;
@support-ie8: true;
@support-pie: true;
```

使用 CSS3 Pie 时需要下载对应的 `.htc` 文件。

### 示例

```less
@import "mixins/clearfix.less";
@support-ie7: true;

.clearfix();
```

### 兼容性

- Chrome 32
- 其他浏览器未测试...

### change log

- 2014-01-23 整理目录，将拆分为单独的 `.less` 文件
- 2014-01-21 添加 mixin 文件