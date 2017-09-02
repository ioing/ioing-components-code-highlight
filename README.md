# IOING - 代码高亮组件
	
<table>
 <thead>
  <tr>
   <td>指令</td>
   <td>值</td>
   <td>描述</td>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>type</td>
   <td>html/xml/mathml/svg/js/css/python/ruby/powershell/bash</td>
   <td>设定代码语言类型</td>
  </tr>
 </tbody>
</table>

```html
<code-highlight type="html">
    <ul>
        <li><span>1</span></li>
        <li><span>2</span></li>
        <li><span>3</span></li>
        <li><span>4</span></li>
        <li><span>5</span></li>
        <li><span>6</span></li>
    </ul>
</code-highlight>
```
```html
<code-highlight type="css">
    div {
        display: flex;
        transform: scale([s]);
        box-shadow: 0 0 5dp red;
        border-radius: 6dp;
    }
</code-highlight>
```
```html
<code-highlight type="js">
    function fn () {
        ...
    }
</code-highlight>
```

该插件使用 Rrism js 库实现语法高亮，如若添加更多语法支持，请访问这里：[http://prismjs.com/](http://prismjs.com/)
