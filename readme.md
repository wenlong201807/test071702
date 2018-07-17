我是测试使用的
我是中国人，我的代码暂时没有丢失
如何创建分支管理
有了分支，就可以区分哪些是我们的，哪些是公共的了
现在我已经切换到了 devzhu 的分支里面来了，项在这里搞点事情，提交，备案，然后试着把这一段 devzhu 中的内容合并到 master 中去，这样就可以在 master 分支中看到我了，当然，在 devzhu 中是看不到 master 的内容的
第一步先要创建分支
git branch devzhu
第二步 多个分支之间相互切换
git checkout devzhu
或者 git checkout master
git branch 查看有哪些分支
git merge devzhu 当前分支与这份分支和 ving
功能五来了，开始功能。。。。
功能五已经写了一部分了， 000 我来坐个标注
今天很有状态，功能五已经完成了

## ssh 方式上传代码

- 令人神魂调到的神操作
  ssh-keygen -t rsa -C '1573511441@qq.com'
  - 变量声明
    git remote add origin git@github.com:wenlong201807/test071702.git master
- git push origin -u master
  > git push

## gulp 的 5 个核心方法

- gulp.task('任务名',function(){})//创建任务
- gulp.src('./\*.css')// 指定想要处理的文件
- gulp.dest()// 指定最终处理后的文件的存放路径
- gulp.watch()// 自动的监视文件的变化，然后执行相应任务
- gulp.run('任务名')// 直接执行相应的任务
