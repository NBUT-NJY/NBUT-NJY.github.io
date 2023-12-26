# 文件夹架构

## CSS
### framework
    我决定在这个目录中存放scss文件以共享到整个项目页面，框架子文件将以下面的方式组织
### plugins
    CSS文件包含于该文件夹中是使JavaScript插件工作的必备风格
### libs
    即使是对CSS文件，我也会区分库和插件，这里有些CSS库例子

## js
### controllers
    存放angular控制器，每一个控制器都有一个与对应视图相同的名字。比如，如果home.html需要一个angular控制器，你可以创建一个像这样的文件
### libs
    用于存放JavaScript库，当然这里不包含插件
### plugins
    插件需要依赖关系来工作，而库不需要，这也就是为什么这里创建两个文件夹的原因
### views
    存放所有表象的东西，每个文件都与对应的视图名称相同。例如，如果home.html需要一些效果、材料以及插件初始值

## html
    存放除去index.html的其他页面文件

## imgs
    存放所有的图片文件夹：png、jpg、jpeg、壁纸等文件