# magnify
## 作用
基于html2canvas的可对网页实现放大镜效果的插件

## 使用
- 将html2canvas.min.js和magnify.js放到要引入的html文件相同路径下
- 在html文件最后引入如下脚本

		<script src="html2canvas.min.js"></script>
		<script src="magnify.js"></script>

## 目前发现的存在问题
- 仅支持静止网页，无法响应动态网页
- 有些网页报如下错误，

> Uncaught DOMException: Failed to execute 'toDataURL' on 'HTMLCanvasElement': Tainted canvases may not be exported. 
