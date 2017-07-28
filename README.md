## PC 端兼容问题汇总

### 约定
1. 用书面语，确保语句通顺，无歧义，尽可能简练
2. 清楚的描述问题场景，缺乏上下文信息会导致读者一头雾水
3. 给出解决方案或使用建议
4. 用 markdown 组织格式


### markdown 简介
- markdown 是一种用于生成格式化文本的标记语言，本质上就是 html 的一种 alias，因为 markdown 最终会被解析成 html，所以在 markdown 中可以直接使用 html
- 通常，我们只需要掌握这几种标记就够了：标题、列表、链接、代码块

#### 标题
```html
#一级标题，等于<h1>
##二级标题，等于<h2>
###三级标题，等于<h3>
####四级标题，等于<h4>
#####五级标题，等于<h5>
######六级标题，等于<h6>
```

#### 列表
-、+ 嵌套使用，就能构成多级列表
```html
- 列表项
- 列表项
- 列表项
  + 二级列表项
  + 二级列表项
  + 二级列表项
    - 三级列表项
    - 三级列表项
    - 三级列表项
```
- 列表项
- 列表项
- 列表项
  + 二级列表项
  + 二级列表项
  + 二级列表项
    - 三级列表项
    - 三级列表项
    - 三级列表项

```html
 1. 有序列表
 2. 有序列表
 3. 有序列表
```
1. 有序列表
2. 有序列表
3. 有序列表

#### 链接
```html
[百度](www.baidu.com)
```
[百度](www.baidu.com)

#### 代码块

``` 包起来的部分就是代码块
github 上，在起始位置的 ``` 紧跟语言名称，github 会应用相应的代码高亮，不加的话就只是没有高亮
比如一段 js 代码：
  ```js
    // 这是一段 js 代码
    console.log(1)
&nbsp; ``` 

```js
  // 这是一段 js 代码
  console.log(1)
```