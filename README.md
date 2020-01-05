# 📣 技术文档之总结说明
* [代码GitHub的URL](https://github.com/He1mo/Gunattack)
* [Pythonanywhere URL](http://forgunsmatter.pythonanywhere.com/)

***
###  🤏 页面的介绍
①编写了十五个htmlURL文档，分别传输不同的由枪击事件叙述的可视化故事

②文档里都写有导航栏（li组件与a标签组合实现此功能）和翻页按钮（button组件与a标签组合实现此功能）

***
### 🔍功能实现
实现数据的Python——>HTML页面可视化交互。

*** 

### 💻 HTML档描述
①编写了十五个htmlURL文档，分别传输不同的由枪击事件叙述的可视化故事

②文档里都写有导航栏（li组件与a标签组合实现此功能）和翻页按钮（button组件与a标签组合实现此功能）

③引入基于boostrap前端开发框架的CSS让界面更加美观了
### 🔌 PYTHON档描述
①导入了需要用到的模块

②对数据进行清洗处理过程中使用数据循环与数据结构
/map_01_details.html"将每个枪击案件添加到事件特性组

③写了不同的路径URL跳转

①py文件中为第一个页面设立路径为"/"
   通过"return render_template"将封装好的"over_line_sactter"函数的数据和"page_01_Number_of_guns.html页面到"/"

②py文件为第二个页面设定路径为"/page_02_shooting.html"用过"returnrender_template"传输了"/page_02_shooting.html"函数

③py文件为第三个页面设定路径为"/page_03_details.html"，通过"return render_template"传输了
  "page_03_details.html",为传输做准备特地处理的数据"data_str"和"region_available"

④py文件为第四个页面设定路径为"/map_details"，需要通过第三个页面提交表单才可以触发跳转，通过return render_template传输"page_03_details.html",为数据传输准备的"plot_all","data_str""regions_available"

### 🎥 Webapp的动作描述
   * 封面的cover与前后页面的跳转按钮
   * 在顶部导航栏设置了超链接跳转至不同的可视化界面。
   * 在最后总结页面设置了下拉选择框可以选择3个故事过程的总结。


