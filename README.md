### 01 首行缩进
```git
  - 半方大的空白&ensp;或&#8194;
  - 全方大的空白&emsp;或&#8195;
  - 不断行的空白格&nbsp;或&#160;
```
### 02 换行
&emsp;&emsp;两种实现方案：<br/>
   + &emsp;&emsp; 使用br标签，就像使用html一样，使用br标签`<br/>`    
   + &emsp;&emsp; 敲击两个以上空白，然后回车:在末尾敲击两个以上空白，然后回车,需要注意的是，有些IDE会自动去掉行末尾的空格<br>  

### 03 字体强调
&emsp;&emsp;Markdown是一种可以使用普通文本编辑器编写的标记语言，通过类似HTML的标记语法，它可以使普通文本内容具有一定的格式。但是<font face="黑体" color=#ff0000 size=4>它本身是不支持修改字体、字号与颜色等功能的！</font><br/>
```git
<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=#0099ff size=7 face="黑体">color=#0099ff size=72 face="黑体"</font>
<font color=#00ffff size=72>color=#00ffff</font>
<font color=gray size=72>color=gray</font>

Size：规定文本的尺寸大小。可能的值：从 1 到 7 的数字。浏览器默认值是 3
```

### 04 上下标
   - 下标： H<sub>2</sub>
   - 上标： CO<sup>2</sup>
```git
下标：H<sub>2</sub>O  CO<sub>2</sub>
上标：X<sup>2</sup>
```

