#### 0.设计背景

① 用一个 ***220V@50Hz / 110RPM*** 的`永磁同步电机`作为发电机，将其`转子轴体`与`摩擦轮`固定后通过与自行车后轮摩擦来带动发电机发电。

> 几何参数如下：
>
> > 摩擦轮轮径：**r** mm
> > 自行车轮径：26英寸(约660mm)
> > 最高骑行速度：30km/h(8.33m/s)
>
> 则在最高骑行速度下：
>
> > 自行车轮转1周，摩擦轮转660/r周
> > 自行车轮每秒转8330/（660 * 2 * 3.14 ）=4.0195周
> > 即摩擦轮每秒转(660/r)*4.0195≈(2652.87/r)周

② 用一个`有刷直流电机`驱动该`永磁同步电机`（如下图），并以示波器等仪器仪表搭建实验平台（如[视频](Pics\1.mp4)所示）

![](Pics\0.jpg)

> 实验数据记录如下
>
> <img src="Pics\2.1.jpg" alt="1" style="zoom:11%;" /><img src="Pics\2.2.jpg" alt="1" style="zoom:11%;" /><img src="Pics\2.3.jpg" alt="1" style="zoom:11%;" /><img src="Pics\2.4.jpg" alt="1" style="zoom:11%;" /><img src="Pics\2.5.jpg" alt="1" style="zoom:11%;" /><img src="Pics\2.6.jpg" alt="1" style="zoom:11%;" /><img src="Pics\2.7.jpg" alt="1" style="zoom:11%;" /><img src="Pics\2.8.jpg" alt="1" style="zoom:11%;" /><img src="Pics\2.9.jpg" alt="1" style="zoom:11%;" /><img src="Pics\2.10.jpg" alt="1" style="zoom:11%;" />
>
> 建立[频率-电压曲线表](Freq-Volt.xlsx)，其中后5个数据点万用表测量值可能有误差，采用示波器读数可发现所得交流电的频率与电压（有效值）基本成正比，如下图。
> ***注：示波器探头采用10x挡位，读数乘以10为实际的电压有效值***
>
> ![](Pics\3.png)

