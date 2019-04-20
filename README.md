# Figure-bed
markdown 图片上传解决方案---GitHub 图床

基于PicGo 和 github 的免费图床搭建
1. PicGo       [图床上传软件](https://github.com/Molunerfinn/PicGo)
2. GitHub仓库  [创建及设置tokens过程](https://picgo.github.io/PicGo-Doc/zh/guide/config.html#github%E5%9B%BE%E5%BA%8A)

问题:
`在使用中出现每次上传图片都被github理解为你的一次commit，导致github活跃表异常的绿`   
解决方案：自己新建一个分支，提交图片时不要使用 master 和 gh-pages 这两个分支就行了

参考：https://github.com/uasier/imgBed
