# node
### HTML accesskey 属性
```
<a href="http://www.w3school.com.cn/html/" accesskey="h">HTML 教程</a><br />
<a href="http://www.w3school.com.cn/css/" accesskey="c">CSS 教程</a>

<p><b>注释：</b>请使用Alt + <i>accessKey</i> (或者 Shift + Alt + <i>accessKey</i>) 来访问带有指定快捷键的元素。</p>
```

### 页面的跳转,自动刷新
- 5秒之后刷新本页面:
```<meta http-equiv="refresh" content="5" />```
- 5秒之后转到梦之都首页:
```<meta http-equiv="refresh" content="5; url=http://www.dreamdu.com/" /> ```

###  HTML tabindex 属性
```<p><a href="http://www.dreamdu.com/xhtml/" tabindex="1">1</a>      
		<a href="http://www.dreamdu.com/css/" tabindex="3">3</a>      
		<a href="http://www.dreamdu.com/javascript/" tabindex="2">2</a></p>
		<p>连续按 "Tab",可以改变焦点的位置.遍历的顺序是1-2-3.</p>
```
