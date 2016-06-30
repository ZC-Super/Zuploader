# Zuploader

## 更新日志

v0.4.0  2016 年 06 月 28 日更新
	增加内部弹出提示信息函数，自定义弹出提示信息。

v0.3.5  2016 年 06 月 28 日更新
	修改部分CSS样式，优化页面

v0.3.4  2016 年 06 月 28 日更新
	增加限制附件总大小功能
	
v0.3.3  2016 年 06 月 28 日更新
	修复单个文件大小限制不准确问题
	修改提示信息内容，优化体验

v0.3.1  2016 年 06 月 27 日更新
	修复当有初始化数据时上传队列处理不准确bug
	修复初始化数据删除异常问题
	上传完成后移出上传按钮，避免重复上传
	
v0.3.0  2016 年 06 月 27 日更新
	增加initData参数，用于初始化时回填曾经上传过的附件

v0.2.9  2016 年 06 月 27 日更新
	修复上传中文文件名文件，存储后文件名乱码问题

v0.2.8  2016 年 06 月 27 日更新
	修复uploads目录不存在的情况上无法存储的问题。后台接收到文件后，判断uploads目录是否存在，若不存在则创建uploads目录

v0.2.5  2016 年 06 月 27 日更新
	增加增加后台存储功能(php),默认存储上传文件到根目录下uploads目录中
	
v0.2.4  2016 年 06 月 27 日更新
	增加最大上传文件个数限制功能
	增加removeTimeout参数，控制进度条在上传完成后移除功能
	
v0.2.1  2016 年 06 月 26 日更新
	修改上传队列html模板
	修改插件中按钮样式以及进度条样式

v0.1.9  2016 年 06 月 25 日更新
	修改formatFileSize函数，增加isKB参数，若isKB参数指定为true，则永远转换为KB
	插件初始化时抛出onInit()函数

v0.1.8  2016 年 06 月 25 日更新
	增加formData参数，可在提交时发送给服务端参数
	增加multi参数，配置是否允许选择多个文件

v0.1.5  2016 年 06 月 25 日更新
	增加上传方式参数参数配置，可手动上传
	增加上传文件大小限制
	增加上传文件类型限制

v0.1.3  2016 年 06 月 24 日更新
	修改onSelect函数参数，传入当前队列数据参数

v0.1.2  2016 年 06 月 24 日更新
	增加显示上传进度条功能

v0.1.1  2016 年 06 月 24 日更新
	构建默认参数及回调函数等

v0.1.0  2016 年 06 月 24 日更新
	创建jquery.Zuploader.js插件

