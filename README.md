# game2048
利用jquery.js+html+css编写的2048小游戏，文件结构比较简单，不做赘述。重点介绍一下，三个js文件中的函数

./js/main2048.js

newgame()初始化棋盘;
updateBoardView()更新棋盘的数据展示;
generateOneNumber(）根据键盘操作，随机生成一个数并展示;
moveLeft()  moveUp()  moveRight() moveDown() 定义了键盘上下左右操作时的数据展示处理;
监听点击开始touchstar和点击结束touchend行为;

./js/showanimation2048.js

设置更新数字、键盘移动的时候的动画;

./js/support2048.js

判断是否能够上下左右移动;
根据数字的大小设置背景颜色.
