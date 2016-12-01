#使用淘宝的flexible.js插件制作的家乐宝首页。
以前在公司用MUI框架做项目的时候，高度没有做适配，比如一个列表里的cell在手机端和平板端显示的高度是一样，<br />
显然这样是不合适的，特别是cell里面的图片就显的更加小了。后来接触到了淘宝的flexible.js插件，具体介绍可以<br />
查看[使用Flexible实现手淘H5页面的终端适配](https://github.com/amfe/article/issues/17)<br />
这个里面还有一个sublime的插件把px转换为rem。由于我的这个小的Demo使用的Hbuilder开发的，我就给个HBuilder<br />
里面是怎么设置的：[Hublider中如何将px转换为rem](http://ask.dcloud.net.cn/article/1013)<br />
MUI框架使用的px。<br />
选中项目->鼠标右键->属性->进入如下视图：<br />
![设置图](https://github.com/zhuming3834/jialebao/blob/master/images/5.jpg)
<br />
有几点要说明的：
1.导航栏高度44px，不需要转换为rem；<br />
2.底部tabbar的高度49px，不需要转换为rem；<br />


