# 简单说明

文档可参见： [我的博客](http://www.hudi.site/)。

## chapter2.1对应vbapi二次开发-2.会话操作实例

+ 连接现有会话
+ 打开一个新会话

## chapter2.2对应vbapi二次开发-2.运行宏实例

+ 运行一个刷新窗口并重生的宏

## chapter2.3对应vbapi二次开发-2-选择对象实例

+ 运行一个选择特征并显示其ID的实例

## chapter2.4对应vbapi二次开发-2-文件操作实例

+ 打开一个模型
+ 保存当前打开的模型
+ 枚举工作目录下所有prt

## chapter3.1对应vbapi二次开发-3-参数操作实例

+ 添加一个参数
+ 修改参数值
+ 删除一个参数

## chapter3.2对应vbapi二次开发-3-关系操作实例

+ 清空当前打开模型的关系
+ 对当前打开模型添加关系

## chapter4.1对应vbapi二次开发-4-文件导出实例

+ drw导出dwg
+ drw导出pdf
+ prt导出step
+ prt导出iges

## chapter5.1对应vbapi二次开发-5-特征操作实例

+ 列出零件包含的所有特征
+ 选中一个特征并删除
+ 选中一个特征并隐含
+ 导入step特征

## chapter6.1对应vbapi二次开发-6-零件装配

+ 插入一个零件
+ 添加一个约束

## chapter6.2对应vbapi二次开发-6-干涉检测

+ 列出所有干涉零件及其干涉量
+ 选择两个零件并查看其干涉量

## chapter6.3对应vbapi二次开发-6-装配树信息

+ 获取装配树结构

## chapter7.1对应vbapi二次开发-7-尺寸修饰

+ 添加尺寸前缀
+ 添加尺寸后缀
+ 添加尺寸线下方文字

## chapter7.2对应vbapi二次开发-7-公差标注

+ 对称公差标注
+ 正负公差标注
+ 基轴制/基孔制公差标注
+ 基轴制/基孔制配合公差标注

## chapter7.3对应vbapi二次开发-7-插入注解

+ 插入自由放置的注解
+ 插入有引线的注解

## chapter7.4对应vbapi二次开发-7-插入符号

+ 插入自由放置的符号
+ 插入有引线的符号
+ 插入垂直于图元的符号

## chapter7.5对应vbapi二次开发-7-层管理

+ 枚举现有层
+ 添加层
+ 删除层
+ 向层内添加对应的元素

## chapter7.6对应vbapi二次开发-7-表格操作

+ 枚举表格
+ 读取表格指定单元格内容
+ 修改表格指定单元格内容

## chapter7.7对应vbapi二次开发-7-BOM操作

+ 国标球标
+ 垂直对齐选中国标球标
+ 水平对齐选中国标球标

## chapter7.8对应vbapi二次开发-7-设定图框

+ 设定图框

## chapter7.9对应vbapi二次开发-7-草绘

+ 创建直线草绘

## chapter7.10对应vbapi二次开发-7-国标倒角

+ 国标倒角标注

## chapter8.1对应vbapi二次开发-8-事件操作

+ 侦听所有Session相关事件
+ 取消ModelErase事件

## chapter8.2对应vbapi二次开发-8-UI操作

+ 添加菜单
+ 添加右键菜单
+ 添加导航器栏

## chapter8.3对应vbapi二次开发-8-调用Protoolkit程序

+ 加载Dll
+ 运行Dll定义的函数

## chapter9.1对应vbapi二次开发-9-文件预览

+ 调用CreoView OCX插件预览文件

## chapter10.1对应vbapi二次开发-10-外部数据

+ 读取外部数据
+ 写入外部数据

## chapter10.2对应vbapi二次开发-10-族表

+ 读取族表信息

## chapter10.3对应vbapi二次开发-10-材料

+ 设定当前零件材料
+ 读取当前零件材料信息

## TkDllEample

+ Toolkit程序，供chapter8.3调用

## CreoFileExportTools对应开发的批量格式导出小工具

+ 批量将选定目录下的drw文件导出到指定目录下的dwg文件
+ 批量将选定目录下的drw文件导出到指定目录下的pdf文件
+ 批量将选定目录下的prt文件导出到指定目录下的stp文件
+ 批量将选定目录下的prt文件导出到指定目录下的igs文件

## 参数的批处理.xls对应开发的批量参数操作小工具

+ 批量为选定目录下的所有prt文件增加指定参数
+ 批量为选定目录下的所有prt文件参数打勾
+ 批量删除选定目录下的所有prt文件指定参数

## CreoRelationTools对应开发的批量关系操作小工具

+ 批量为选定目录下的所有prt文件增加指定text文件包含的关系
+ 批量清空选定目录下的所有prt文件包含的关系

## 零件参数化设计系统对应开发的零件参数化设计小工具

+ 零件的参数化设计
+ 零件库的维护

## vb6creo对应VB6调用VBAPI开发简单实例

## CreoCSharp对应C#调用vbapi接口二次开发实例

## Familyexport对应开发的族表文件批量导出小工具

+ 命令行工具，注意命令行参数

## BatOperation

+ Creo二次开发的批处理小工具，可以实现批量参数处理、批量关系处理、批量格式导出、批量单位转换、批量旧版本删除、批量导出族表实例以及批量转换图框等7大功能。
