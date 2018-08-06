# A web page game based on JS, HTML and CSS
#### The player controls a boy to cross the river, and try to avoid insects.

![alt text](https://s3-ap-southeast-2.amazonaws.com/test-avatar/AG.png)

前端纳米学位街机游戏克隆项目作业
author：ulajiang

=============== 游戏功能 =================

1.在此游戏中有玩家和敌人 (小虫)
2.玩家的目标是抵达水域，并且不会撞到任何其他敌人
3.玩家可以上下左右移动
4.敌人在场景中的道路上移动速度变化不一
5.一旦玩家撞到敌人，游戏就会重置，并且玩家返回起始方框
6.玩家抵达水域后，游戏胜利。


=============== 组成部分 ==================

1. app.js实现了游戏的角色的主要功能，如玩家位置的移动，敌人位置的移动，游戏输赢的判断等
2. engine.js提供了游戏循环玩耍的功能，如更新敌人和不断绘制整个游戏屏幕
3. resource.js提供了图片加载工具


================ 开始游戏 ==================

双击index.html即可打开游戏界面，键盘的上下左右键用于控制玩家的位置


================ 项目资源 ==================

engine.js, resource.js, index.html, style.css由优达学院提供
app.js由我实现
