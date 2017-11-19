# vue-cms
### 20160927-20161010  后端CMS运营界面
[coding demo->后端CMS运营界面](http://rowboat.coding.me/cms)
或者：(原来是在coding，现转移到到github。)
[github demo->后端CMS运营界面](http://lxchuan12.github.io/vue-cms)

> 2017-11-18 使用Vue2.0重构

页面，拖拽，保存，上传图片。
vuejs，或者用jquery.
**参考：**

1、秀米：http://xiumi.us/studio/v5#/booklet/for/new

2、135编辑器：http://www.135editor.com/

3、i排版：http://www.ipaiban.com/#

4、参考qf-mobile首页，配置而来。

数据接口，自己写模拟json数据.
>1、页面简陋

>2、拖拽 Vue1.0采用的插件:
[vue-drag-and-drop](https://github.com/james2doyle/vue-drag-and-drop)
[vue-drag-and-drop DEMO](https://codepen.io/Lazyboy/pen/RRgRPb)
[vue-sortable](https://github.com/sagalbot/vue-sortable)

使用Vue2.0重写时，采用的是:
[Vue.Draggable](https://github.com/SortableJS/Vue.Draggable)

>3、上传图片和文件插件

>4、保存

>5、**目前问题：**多个添加图片，拖拽。

>6、如何点击生组件里的样子生成一个。

>7、单张图片跑通，拖拽有些问题。

>8、需要美化

>10、两个,多个跑通

>12、拖拽问题。找到最近的LI标签。作为拖拽的点和被替换的点。

>13、菜单栏优化,全部完成(20161010)

>14、添加注释(20161011)

>15、排序、删除按钮移到右侧，点击图片更换图片。

### 20161011 优化（APIS）
>1.左侧导航：模板图片替换；---5
>
>2.左侧导航样式；（参照后台）---4
>
>3.中间"点击添加图片"的背景颜色；---3
>
>4.拖拽按钮；---1
>
>5.当前编辑高亮；---6
>
>6.整体的保存按钮；---7(联调)
>
>7.删除按钮的confirm提示---2

### 20161013 抽离组件
>1、删除时，编辑栏隐藏；正在编辑，拖拽、排序后，依旧显示高亮；---1
>
>2、outline---红色，outline加padding---3
>
>3、侧栏样式区分----2
>
>4、抽离图片组件---抽离组件修改-无须再改(达到无法抽离效果，暂不抽离)