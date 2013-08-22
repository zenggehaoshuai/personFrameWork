personFrameWork
===============

personFrameWork
根据自己以前公司的项目，自己写的一个库，集合了常用的dom选择和处理，事件处理，常用工具处理,简化ajax操作，易于扩展和新增自己的模块

 新增了对话框组件、验证组件

 本库改变了在常用的页面引用js的方式(script),借鉴node.js的require函数，在引用当前文件所注册的模块的时候用同步方式，当引用自己存为js文件写模块的时候,使用require(name,callback)异步方式。