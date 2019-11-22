# element-checkbox-group-issue

复现步骤：

1、使用 element cdn 方式引入组件库。

```html
<script src="https://unpkg.com/vue/dist/vue.js"></script>
<script src="https://unpkg.com/element-ui/lib/index.js"></script>
```

2、使用官方文档中的 checkbox-group 组件进行渲染。

```html
<el-checkbox-group>
  <el-checkbox label="复选框 A"></el-checkbox>
  <el-checkbox label="复选框 B"></el-checkbox>
  <el-checkbox label="复选框 C"></el-checkbox>
  <el-checkbox label="禁用" disabled></el-checkbox>
  <el-checkbox label="选中且禁用" disabled></el-checkbox>
</el-checkbox-group>
```

3、页面报错，无法正常渲染。
