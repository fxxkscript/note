Underscore.js 源码阅读笔记
========================


1. `obj.length === +obj.length` vs `typeof obj.length === 'number'`

	判断length是否为数字。
	
	一元运算符+将操作数转换成数字。严格比较===判断length是否真的是数字
	
	<http://stackoverflow.com/questions/9188998/obj-length-obj-length-in-javascript>

