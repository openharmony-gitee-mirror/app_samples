# 井字过三关

##### 简介

​        本sample由Java开发，可拉起身边小伙伴手机游戏加入到对局，过三关是非常经典的游戏，可通过时间来判断胜负。

##### 使用说明

1. ###### 拉起应用

   ​        通过点击首页开始游戏按钮可以查看同一组网内的设备，然后选择需要对战的设备，点击确定按钮就可以拉起对应设备中的FA进行游戏。

   

2. ###### 游戏玩法

   ​        点击九宫格中的任意一格未被填充的格子，会自动填充对应的○或者×，表示已经此格已下。

   ​        游戏左上角显示当前自己对应的是○还是×。

   ​        当轮到自己下的时候，左上角的图标会自动抖动且下方时间计时开始，否则的话非己方行动的时候，无法点击。

   

3. ###### 游戏结果显示

   ​        当一方先连三个格子(横竖以及对角线连三个都算)，则判定为胜利，或者行动方在规定时间内未动作，则判定行动方失败，对方获胜。胜利一方会弹出你已经赢了的对话框，而失败方则弹出你失败了的对话框。若九个格子都下完而没有一方获胜的话，则为平局，双方弹出平局的对话框。

   

4. 重新开始

   ​        游戏结束后，点击右下角复位按钮则重新开始议论游戏。

   

5. 返回

   ​        游戏结束后，点击左下角返回按钮，可以回到选择对战设备的首页面，可以重新选择拉起的设备。

   

##### 约束与限制

1. 编译约束

   设置DevEco Studio开发环境。

   具体环境搭建请[参考](https://developer.harmonyos.com/cn/docs/documentation/doc-guides/installation_process-0000001071425528) 。
  

2. 使用限制

   该应用必须要有两部同一组网内的手机，且只支持同时两部手机进行游戏

