# 百度echarts地图三种地图下钻方式

##第一种——双击
>是在一个`div`元素上展示地图，通过单机的方式对可选的区域进行展开，如（江苏-南京-各个区），到区，县停止；双击返回上一层，返回到中国地图停止；注意点：因为有双击事件，所以要设置鼠标双击之间的延迟时间。

##第二种——右键
>跟第一种方式类似，用鼠标右键的方式代替双击；注意点：禁止鼠标右键的默认功能。

##第三种——两个区域
>采用两个`div`区域分别进行展示，左边显示中国地图，右边显示选中区域的地图。
