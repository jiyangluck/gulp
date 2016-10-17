## 《从零开始》系列教程之《从零开始学gulp》

#### 简介
* 本课程讲解gulp常用功能。
* 课程配套电子书、案例代码、视频
* 关注微信，第一时间过去前端开发课程

![二维码](https://github.com/jiyangluck/front-end/blob/master/example/images/weixin.jpg?raw=true)

#### 课程包括以下gulp插件
* 压缩css gulp-clean-css
* 混淆js  gulp-uglify
* 压缩图片 gulp-imagemin
* 文件合并 gulp-concat
* 编译less gulp-less
* 代码规范 gulp-eslint

#### gulp API
* gulp.src(globs[, options]) 返回符合匹配规则的虚拟文件对象流(Vinyl files)。
* gulp.dest(path[, options]) 用来指定要生成的文件的目录，目录路径为path。
* gulp.task(name[, deps], fn) 定义一个流任务，任务名为name。
* gulp.watch(glob[, opts], tasks) 监视文件的变化，执行操作。

