﻿# starlingswf_yfqian_egret

starlingswf对starlingswf flash 开发者来说，你更熟悉界面编辑和快速开发h5流程。




项目演示地址：


中型游戏（30%完成度）：http://kungfu.sinaapp.com/html5/sg_GL_V06/

小游戏（100%）：http://17wgj.com/game/rg/09/

小游戏（4%）：http://17wgj.com/game/sq/15/


======

-----------------------------------------------------------


目前版本：v1.00 正式版(支持egret版本：1.70以上)

-----------------------------------------------------------

v1.02 更新内容：

1、修复部分电脑ie9以上无法运行访问。

2、资源加载速度提升。

3、框架代码修改为一个demo案例，并修复部分类调用的错误。

4、增加一个结构图。

5、增加随机名字库和随机方法，多大千万种组合。

（由于字库行数太多，打包可能变慢，如果不使用名字，可在src\starlingswf\Yfqian\Yfqian_NameList\Yfqian_Name.ts下，把ts文件删除）


调用方法：

Yfqian.Yfqian_RandomName.Name()//获得一个名字结果。


-----------------------------------------------------------

v1.01 更新内容：

1、框架支持ie9以上核心的ie浏览器运行

2、增加附级对象类的调用。

3、增加btn_ 按钮组件。


-----------------------------------------------------------

v1.00 更新内容：

1、完全修复加载卡资源问题。

2、优化加载队列内容。


-----------------------------------------------------------

v0.01a 更新内容：


1.修复加载错误奔溃问题

2.增加框架结构接在提示

-----------------------------------------------------------

v0.01 主要内容：

1、修复加载错误奔溃问题

2、增加框架结构接在提示

3、修复log后一瞬间黑屏

4、优化初次加载游戏失败的问题


-----------------------------------------------------------




UI资源：


  —— 下载地址：http://yunpan.cn/cmTIQkcV6nXvN
  

  —— 访问密码：1f29
  
  
  —— UI使用学习：http://xyliu.sinaapp.com/?p=17
  

注意：更新进度页面时，请减少图片大小，否则会出现长时间黑屏。



独立控件使用说明：


1、	对某个控件加入或去除 鼠标点击事件

	加入事件： Yfqian.TuchEvent.On(this.Sprshp); 

	去除事件： Yfqian.TuchEvent.Off(this.Sprshp);



2、	鼠标事件写法：

元件名.addEventListener(egret.TouchEvent.TOUCH_BEGIN,function() {

trace.log("点击成功");

},this);



3、	加载网络图片

new Yfqian.Img("图片地址",显示容器)


=======

4、	舞台窗口弹射效果：

new Yfqian.Sprite(窗口OBject);

=======


5、	点击动画事件

if(Yfqian.AnNiu.retNum(this.Cj_qd) == true) {    
 

trace.log("点击成功");

}


=======


6、	关闭窗口动画事件

if(Yfqian.Sprite.Sprite_Off(this.CreateRole_id_qr, this.Sprshp) == true) {

trace.log("点击成功");

}


