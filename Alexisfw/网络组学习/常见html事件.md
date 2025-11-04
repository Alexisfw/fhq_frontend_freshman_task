事件			 描述



**页面：**

onchange	         HTML 元素改变

onload		 浏览器已完成页面的加载



**鼠标：**

onclick		 用户点击 HTML 元素

onmousemove   鼠标被移动

onwheel		 鼠标滚轮在元素上滚动时触发

onmousedown	 鼠标按钮被按下

onmouseup	 鼠标按键被松开

onmouseover	 鼠标指针移动到指定的元素上时发生（类似有onmouseenter）

onmouseout	 用户从一个 HTML 元素上移开鼠标时发生(类似有onmouseleave)

【over与enter区别详见html文件】



**键盘：**

onkeydown	 按下键盘按键

onkeyup		 松开键盘按键

onkeypress	 键盘按键被按下并松开



HTML语法:

<element onkeydown="SomeJavaScriptCode">

JavaScript语法:

object.onkeydown=function(){SomeJavaScriptCode};

(用event.key获取是哪个按键)



**表单：**

onblur		 元素失去焦点时触发

onfocus		 元素获取焦点时触发

onsubmit		 表单提交时触发

onselect		 用户选取文本时触发 ( <input> 和 <textarea>)



**剪贴板：**

oncopy		 该事件在用户拷贝元素内容时触发

oncut		 该事件在用户剪切元素内容时触发

onpaste		 该事件在用户粘贴元素内容时触发



**拖动：**

ondragstart	 该事件在用户开始拖动元素时触发

ondrag		 该事件在元素正在拖动时触发

ondragend	 该事件在用户完成元素的拖动时触发

ondrop		 该事件在拖动元素放置在目标区域时触发



**多媒体：**

onplay		 事件在视频/音频（audio/video）开始播放时触发。

onpause		 事件在视频/音频（audio/video）暂停时触发。

onended		   事件在视频/音频（audio/video）播放结束时触发。

onerror		 事件在视频/音频（audio/video）数据加载期间发生错误时触发。



**动画：**

animationstart	 该事件在 CSS 动画开始播放时触发

animationend	 该事件在 CSS 动画结束播放时触发

animationiteration	该事件在 CSS 动画重复播放时触发

transitionend	 该事件在 CSS 完成过渡后触发。







**鼠标/键盘事件对象：**

altKey		 返回当事件被触发时，"ALT" 是否被按下。（返回布尔值）

shiftKey		 返回当事件被触发时，"SHIFT" 键是否被按下。

ctrlKey		 返回当事件被触发时，"CTRL" 键是否被按下。

button		 返回当事件被触发时，哪个鼠标按钮被点击。

clientX		 返回当事件被触发时，鼠标指针的水平坐标。	（相对于浏览器页面）

clientY		 返回当事件被触发时，鼠标指针的垂直坐标。

screenX		 返回当某个事件被触发时，鼠标指针的水平坐标。	（相对于屏幕）

screenY		 返回当某个事件被触发时，鼠标指针的垂直坐标。

key			 在按下按键时返回按键的标识符。

Location		 返回按键在设备上的位置



 





 

