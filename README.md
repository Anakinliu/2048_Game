# 2048_Game

**[在线体验](https://kouder.cn/game/2048/)**

## 啰嗦

用了一天时间，原生JS写的逻辑，部分游戏逻辑参考了[这个开源仓库](https://github.com/nnngu/js_game_2048)

- JS没有使用任何第三库。
- JS尽量将每个功能拆分成函数。
- JS尽量写了更多更详细的注释。
- CSS没有使用任何样式库。

## 功能与玩法

- 游戏得分没有按照2048游戏来，只是记录了最大数。历史最大数使用`localStorage`保存。
- 使用键盘方向键进行上下左右操作。
- 某个方向不能继续操作，弹出提示框。
- 所有方向不能继续操作，弹出游戏结束提示框。


## 截图

游戏主界面：

![image](https://user-images.githubusercontent.com/16507329/129556603-42ced8f4-c462-4b1e-b490-5849c7ad56c7.png)

判断游戏结束：

![image](https://user-images.githubusercontent.com/16507329/129556654-b1b74e75-e7a7-44ba-8935-5f86933701e1.png)

有问题欢迎发issue😀
