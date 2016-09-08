# 桌面前端插件库

## 版本记录
* v1.5.1
	* 重构表格和分页组件，合理化代码
* v1.5
	* 重构表格的三个功能
		1. 排序
		1. 列显示/隐藏
		1. 列筛选
	* 自动补全组件添加选项minKeywordLength(最小关键字长度，小于该长度时不发送请求)
* v1.4.1
	* 重构uiSelect组件
	* 调整组件中不合理的地方
* v1.4
	* 修改组件为兼容AMD方式
	* 添加基于原生input[type="file"]标签的上传组件，用于在支持FormData的浏览器上代替flash上传组件
* v1.3.2
	* 为表格、分页组件添加destroy()方法，并且在init时自动调用
	* 修复自动补全组件几次请求卡在一起显示到列表中的问题
* v1.3.1
	* 调整正则表单验证组件的使用方式，支持多条规则校验
* v1.3
	* 重整表格结构
	* 为表格添加两个功能：
		1. 列显示隐藏
		1. 表格值过滤
	* 将组件集用IIEF包装，独立命名空间
* v1.2.2
	* 修改tlayer的拖动bug，仅在windown对象上拖动
	* 修改选择器的职位为部门职位
* v1.2.1
	* 去掉按钮的重写样式，改用bootstrap.theme样式文件来扩展
	* 修改分页样式
* v1.2 (2016-06-28)
	* 增加正则表单验证提示组件
	* 增加输入框enter键与按钮事件关联组件
	* 修复自动补全组件请求未被终止掉的问题
	* 修复选择器选择多人时自动勾选的问题
* v1.1 (2016-06-20)
	* 修复表格组件拖拽问题
	* 修复选择器组件问题，将top修改为window
	* 修复自动补全组件的问题，后续请求abort掉前面请求
	* 优化选择器使用
	* 修复util工具集数组操作bug
* v1.0 (2016-05-17)
	* 正式发布前端组件