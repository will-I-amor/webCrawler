### Matrix Operation
##### 矩阵相除。得出的结果很多小数，可以用numpy的round函数整理一下
###### 矩阵FieldGoals和Games相除

![](https://i.imgur.com/3uP1AUI.png)

### 加一个numpy.round(),把数字round
![](https://i.imgur.com/o6x5FJW.png)

## matplot, pyplot
### %matplotlib inline  (put the pics all in one page, not in seperate windows)
![](https://i.imgur.com/NjbvkG5.png)


#### 编辑图表颜色，line shape等
![](https://i.imgur.com/wqbteWd.png)
#### 设置图表大小
![](https://i.imgur.com/GwvLZYe.png)
#### 把横坐标改成年份。
    
    
    plt.xticks(list(range(0,10)),Seasons)
    其中Seasons是含有10个年份的list，list(range(0,10))是取10个数，把他们变成list，意为10个年份，10个横坐标
    
![](https://i.imgur.com/S5HDS2i.png)

#### 改一改其他参数，比如竖过来
![](https://i.imgur.com/9vyJps7.png)

    plt.plot(Salary[0],c="Black",ls = '--',marker='s',ms=7,label=Players[0])
    plt.xticks(list(range(0,len(Seasons))),Seasons,rotation='vertical')
    #add tickmark
    plt.show()

### 给图标加legend，比例尺
![](https://i.imgur.com/PqOjU4e.png)

### 把legend放在右上角
![](https://i.imgur.com/17hs5Vp.png)
