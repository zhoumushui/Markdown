
# 一级标题
`#`
## 二级标题
`##`
### 三级标题
`###`
#### 四级标题
`####`
#####五级标题
`#####`
######六级标题
`######`


##横线##
`***` `---` `___`
***
---
___

##字型##
*斜体:`* *`*

**粗体:`** **`**

***斜粗体`*** ***`***

<em>HTML斜体:`<em></em>`</em>

<strong>HTML粗体:`<strong></strong>`</strong>

<em><strong>HTML粗斜体:`<em><strong></strong></em>`</strong></em>


##引用##
`> >> >>> ...`
> 
> 时间过得好快。
> > Time flies--zms
> > > Android Developer
> > > > 莫忘初衷。



正文内容
***

##清单##
`- - -` `1.2.3.` `* * *` `+ + +`

- 清单1.1
- 清单1.2
- 清单1.3

1. 清单2.1
2. 清单2.2
3. 清单2.3

* a
* b
* c

+ aaaaa
+ bbbbb
+ ccccc

###HTML清单###
`<ol> <li></li> </ol>`
<ol>
<li>HTML清单1</li>
<li>HTML清单2</li>
<li>HTML清单3</li>
</ol>

##超链接：##
`[ZMS](http://www.zms.com)`

- [周木水的**CSDN**](http://blog.csdn.net/zhoumushui)

- [周木水的**GitHub**](https://github.com/zhoumushui)

`[ZMS][id]`	
`[id]:http://www.zms.com "title"`

[周木水的微博][1]
[1]: http://weibo.com/zhoumushui "周木水"



##代码块##

`MarkDown``Android`

###HTML 代码块###
`<code></code>`
<code>

public class Hello{}
</code>

##图片##
`![zms](http://www.zms.com/test.jpg)`

![zhoumushui](http://avatar.csdn.net/A/6/4/1_zhoumushui.jpg)

###HTML图片###
`<img src="http:www.zms.com/test.jpg" style="width:200px; height:200px"/>`
<img src="http://avatar.csdn.net/A/6/4/1_zhoumushui.jpg" style="width:200px; height:200px"/>


##特殊符号##
`<div>&copy ZMS 2015</div>`
<div>&copy ZMS 2015</div>


以下这些符号前面加上反斜杠可插入普通的符号：
<pre><code>\   反斜线
`   反引号
*   星号
_   底线
{}  花括号
[]  方括号
()  括弧
#   井字号
+   加号
-   减号
.   英文句点
!   惊叹号
</code></pre>

###iframe框架###
`<iframe src="http://www.zms.com" style="width:100%; height:700px"/>`


##表格##

| 项目        | 价格   |  数量  |
| --------   | -----:  | :----:  |
| 计算机     | $1600 |   5     |
| 手机        |   $12   |   12   |
| 管线        |    $1    |  234  |


###HTML表格###

`<table><tr> <td></td> </tr></table>`
<table>
	<tr>
		<td>A</td>
		<td>L</td>
		<td>E</td>
		<td>X</td>
		<td></td>
		<td></td>
		<td>Z</td>
		<td>H</td>
		<td>O</td>
		<td>U</td>
	</tr>
	<tr>
		<td>Z</td>
		<td>H</td>
		<td>O</td>
		<td>U</td>
		<td>M</td>
		<td>U</td>
		<td>S</td>
		<td>H</td>
		<td>U</td>
		<td>I</td>
	</tr>
</table>


##代码##
<pre name="code" class="java"><code>
 private void exitAction() {
        try {
            Intent intent = new Intent();
            ComponentName componentName = new ComponentName(&quot;com.android.settings&quot;,
                    &quot;com.android.settings.Settings&quot;);
            intent.setComponent(componentName);
            startActivity(intent);
        } catch (Exception e) {
            e.printStackTrace();
        }
    }
</code></pre>

##换行

>- 四个及以上空格加回车。
- Tab加回车也行。
- 两个回车也行。

##删除线
`<del></del>`	

<del>不要删除我</del>

##复选框&单选框

- [x] Be awesome
- [ ] Prepare dinner
  - [x] Research recipe
  - [ ] Buy ingredients
  - [ ] Cook recipe
- [ ] Sleep

###HTML复选框
<input name="Company" type="checkbox" value="1" checked>百度</input>
<input name="Company" type="checkbox" value="2">腾讯</input>
<input name="Company" type="checkbox" value="3">阿里巴巴</input>

###HTML单选框
<input type="radio" name="city" value="beijing" checked>北京</input>
<input type="radio" name="city" value="shanghai">深圳</input>
<input type="radio" name="city" value="nanjing">杭州</input>


##书写公式

$$E=mc^2$$

##流程图
```flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op
```