# snakk
我很久之前第一次学习python 时写的贪吃蛇小程序。

代码非常初级，不简洁。
采用面向对象的方法实现的：
1.首先有一个方向class，记录蛇的每一块body的方向；同时有指引下一步行动的方法：left、right、up、down、前进、死亡、判断前进or死亡
2.在方向class的基础上定义snake对象，继承自方向class，主要方法是show、food等方法
之后只需要调用 pygame就可以轻松实现贪吃蛇小游戏了
