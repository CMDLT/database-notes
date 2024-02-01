

## 第2章

#### 预处理

问卷处理

是为了建立一个有结构的文件

#### 文件 纵向合并 和 横向合并

**纵向合并**

> 将一SPSS文件中的数据追加到另一个数据文件中。
>
> 两个SPSS数据文件应当有可以合并的内容，且最好有相同的变量名和变量类型。

合并文件 添加**个案**

**横向合并**

> 将一SPSS文件中的若干个变量增加到另一个数据文件中。
>
> 两个数据文件必须有一个共同的变量名为关键字。
>
> 两个数据文件应事先按关键字段升序排序。

合并文件 添加**变量**

---

#### 选择个案

> 目的：选择出一些符合一定条件的个案，分析时只对这些个案分析

**数据 -> 转置**

实验案例：休闲调查1.sav 

---

##### 按条件选

要求：选中年龄在50-60之间的，并过滤未选中的个案

步骤：1、菜单 数据 -> 选择个案

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/图2.jpg" alt="图2" style="zoom:50%;" />

2，选中....，点击如果。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/图3.jpg" alt="图3" style="zoom:50%;" />

3、设置好后，点击继续。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025202058.jpg" alt="微信图片_20221025202058" style="zoom:50%;" />

4，选中，然后点击继续，这个是为了只让我们保留选中的个案。被过滤的个案前面会打斜线，后面的分析这些数据将不会参与。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025202639.jpg" alt="微信图片_20221025202639" style="zoom:50%;" />

---

##### 随机选择

要求：从前100个个案中选30个，并把未选中的个案保存到新文件中。

首先：<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025203100.jpg" alt="微信图片_20221025203100" style="zoom:50%;" />

进行这一步可将上面操作过的文件恢复原来的状态。

步骤：1、菜单 数据 -> 选择个案

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025203100.jpg" alt="微信图片_20221025203100" style="zoom:50%;" />

2、选中大约10%的个案。点击继续

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025203204.jpg" alt="微信图片_20221025203204" style="zoom:50%;" />

3、选定个案保存到“new1”数据集中，点击确定。

结果：得到一个新的名为new1的数据集，里面有36条个案，是原数据大约10%的数据。如果要精确，则：

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025203704.jpg" alt="微信图片_20221025203704" style="zoom:50%;" />

> 精确的从前100个个案中选择30个。

---

##### 在设定范围内选择

要求：选择第3到第6个个案

步骤：1、菜单 数据 -> 选择个案

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025204227.jpg" alt="微信图片_20221025204227" style="zoom:50%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025204313.jpg" alt="微信图片_20221025204313" style="zoom:50%;" />

2、点击确定。

---

##### 过滤变量缺失值

要求：过滤“文化程度”缺失值

步骤：1、菜单 数据 -> 选择个案

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025204611.jpg" alt="微信图片_20221025204611" style="zoom:50%;" />

2、点击确定。

##### 补充 函数框

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025204859.jpg" alt="微信图片_20221025204859" style="zoom:50%;" />

如此，选中可用于求余。

![微信图片_20221025205026](https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025205026.jpg)

得问卷编号为偶数的个案。问卷编号除2余为0。

---

#### 数据文件的转置

> 目的：由于SPSS的数据分析都是对变量（列）进行的，当需要对个案（行）进行分析时，如“比赛成绩”，就需要把个案转换成变量。

案例：比赛成绩.sav

![微信图片_20221025205630](https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025205630.jpg)

要求：对“比赛成绩”转置，因为要每个选手的平均成绩，要对行变量进行计算，所以将行转化为列，用“选手编号”做变量名。

步骤：1、菜单 数据 -> 转置

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025210000.jpg" alt="微信图片_20221025210000" style="zoom:50%;" />

2、点击确定。

![微信图片_20221025210122](https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025210122.jpg)

> 成功转置

---

#### 分类汇总

> 目的：以指定的分类变量取值为依据，**将另一个或多个变量分成若干类**后再**在各类内部进行描述统计**，并把统计结果**生成新的数据文件**，如“考试成绩3”。

**数据 -> 分类汇总**

案例：考试成绩.sav

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113123119987.png" alt="image-20221113123119987" style="zoom:50%;" />

与“文件分隔”的区别：输出形式不同，前者输出数据文件，便于再次进行分析。

要求：按班级号分类，以各科成绩平均值分类汇总。

步骤：

①数据 -> 分类汇总；②<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113123205584.png" alt="image-20221113123205584" style="zoom:50%;" />

③点击确定。查看新建立的数据集new2。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113123321209.png" alt="image-20221113123321209" style="zoom:67%;" />

> 已按班级对每一科平均分求解。

**如何求每个班的及格率**

在考试成绩3中进行操作。

①<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113123625238.png" alt="image-20221113123625238" style="zoom: 50%;" />；②<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113123821147.png" alt="image-20221113123821147" style="zoom:50%;" />

③点击确定。查看new3.sav。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113124028101.png" alt="image-20221113124028101" style="zoom:67%;" />

> 包含了数学语文各班的及格率，1班共有53个个案。

拓展：<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113124721047.png" alt="image-20221113124721047" style="zoom:50%;" />和百分比的区别。<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113124821843.png" alt="image-20221113124821843" style="zoom:50%;" />

打开new4.sav。<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113124910637.png" alt="image-20221113124910637" style="zoom:67%;" />

---

#### 变量内容的重新编码

> 目的：在统计分析时，最初设定的变量的值可能不符合统计分析的要求，这就需要对录入的变量的值进行重新设定。

修改变量值时，旧值与新值可以是“一对一”，也可以是“一对多”。

修改后的变量名可以与原来相同，也可以起新的变量名。

**转换 -> 重新编码**

案例：休闲调查.sav

要求：“休闲调查1”中的“年龄”—“年龄段”，“文化程度（缺失）”—0

年龄段

①<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113130022488.png" alt="image-20221113130022488" style="zoom:50%;" />

②<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113130319175.png" alt="image-20221113130319175" style="zoom:50%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113135117603.png" alt="image-20221113135117603" style="zoom:50%;" />

③点击确定

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113135214316.png" alt="image-20221113135214316" style="zoom:80%;" />

文化程度缺失值

①<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113135316549.png" alt="image-20221113135316549" style="zoom:50%;" />；②<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113135434630.png" alt="image-20221113135434630" style="zoom:50%;" />

---

#### 变量运算

> 目的：需要在变量之间进行运算

**转换 -> 计算变量**

案例：贫困调查

要求：用“出生年份”计算“年龄”。计算恩格尔系数。

步骤：

①<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113135826159.png" alt="image-20221113135826159" style="zoom:50%;" />；②<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113140002565.png" alt="image-20221113140002565" style="zoom:50%;" />；③点击确定

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113141724103.png" alt="image-20221113141724103" style="zoom: 80%;" />

> 缺失值是因为四个变量至少有一个是没有的。

---

## 第3章

#### 3.5 描述分析的SPSS过程



#### 3.6 数据探索的SPSS过程

- 【探索】模块的功能实际上
- 目的



案例3-6：对本章数据“股票

---

## 第6章 交叉列表与等级相关分析

> 对不同类型的变量，采用不同的分析方法，分析其相关性，如：对尺度型数据用person系数分析，对名义、顺序型数据，用kendall、spearman系数分析。

---

#### 对名义、顺序型数据

##### 交叉列表分析

> 分析**两个变量**之间的关系，被分析的变量可以是名义变量，也可以是顺序变量，生成交叉表，输出卡方检验结果。

**分析 -> 描述统计 -> 交叉表**

案例：休闲调查1.sav

要求：对“性别”和“对闲暇生活的满意度2”进行交叉表分析。（卡方检验，显示百分比）

步骤：1、分析 -> 描述统计 -> 交叉表

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025212502.jpg" alt="微信图片_20221025212502" style="zoom:50%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025212628.jpg" alt="微信图片_20221025212628" style="zoom:50%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025212731.jpg" alt="微信图片_20221025212731" style="zoom:50%;" />

2、点击确定。

结果：

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025213003.jpg" alt="微信图片_20221025213003" style="zoom:80%;" />

> 共有283个个案被处理

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025213051.jpg" alt="微信图片_20221025213051" style="zoom:50%;" />

> 女性满意的有30%，男性满意的有35%，可见女性满意度低于男性
>
> 用总计的2.5%乘男性的总计的143.0，得到男性很不满意的期望计数为3.5，
>
> 再用2.5%乘女性的140.0得到女性很不满意的期望计数同样为3.5。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/微信图片_20221025213054.jpg" alt="微信图片_20221025213054" style="zoom: 80%;" />

> 卡方检验表，关注两个值，一个皮尔逊卡方值，一个渐进显著性(Sig)
>
> 首先 12.558 怎么算的<img src="E:\SPSS练习\notephoto\微信图片_20221025231902.jpg" alt="微信图片_20221025231902" style="zoom:50%;" />，fo是观测数，fe是期望计数。
>
> （fo就是上面那个表格中的数字2、19、72之类的，计数的行）
>
> 有方程式的，fo与fe相差越小，实际观测数也就越接近期望的计数，则x²也就越小；若果x²越大，说明fo与fe差异就越大，就说明不同性别对闲暇满意度是不同的，两个变量是有相关性的。
>
> 那么这里的 12.558 是比较大的值，就说明性别对满意度是有影响的
>
> 而sig值 0.014 是拒绝原假设，这里的原假设就是性别对满意度没有影响。
>
> 这里的结果说明女性比男性更渴望闲暇时光。

---

##### 等级相关分析

> 目的：分析两个顺序变量或名义变量之间的关系，描述变量之间相关的大小和方向。

**分析 -> 描述统计 -> 交叉表**

案例：休闲调查.sav

要求：

1、对“文化程度”和“对居住环境的满意度”进行等级相关分析。（Gamma相关系数：<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113143808042.png" alt="image-20221113143808042" style="zoom: 33%;" />）；

> “文化程度”和“满意度”都是顺序类型的变量。同序对：小学不满意，高中满意，是一个同序对，小学<高中，不满意<满意；逆序对：小学满意，高中不满意，是一个逆序对，小学<高中，满意>不满意。

> 原假设：没有相关性。

步骤：

①<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113144814304.png" alt="image-20221113144814304" style="zoom:50%;" />；

②<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113145342582.png" alt="image-20221113145342582" style="zoom:50%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113145322497.png" alt="image-20221113145322497" style="zoom:50%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113150702958.png" alt="image-20221113150702958" style="zoom:50%;" />;

③点击确定。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113154427602.png" alt="image-20221113154427602" style="zoom: 67%;" />

> 由表可知，文化越高对环境越挑剔。（初步印象）

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113154910634.png" alt="image-20221113154910634" style="zoom:80%;" />

> 负相关，文化程度越高，文化程度越低，影响较弱。

2、对“性别”和“就业情况”进行相关分析。（相依系数：<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113143858574.png" alt="image-20221113143858574" style="zoom:33%;" />；phi

：<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113144048649.png" alt="image-20221113144048649" style="zoom:33%;" />；cramer：<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113144032086.png" alt="image-20221113144032086" style="zoom:33%;" />）

> 都是名义类型的变量

步骤：

①<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113155318849.png" alt="image-20221113155318849" style="zoom:50%;" />

②<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113155511432.png" alt="image-20221113155511432" style="zoom:50%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113155525973.png" alt="image-20221113155525973" style="zoom:50%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113155621593.png" alt="image-20221113155621593" style="zoom:50%;" />

③点击确定。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113155755154.png" alt="image-20221113155755154" style="zoom:80%;" />

> 个案处理。

![image-20221113155822286](https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113155822286.png)

> 初步印象，性别不同就业情况不同。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113155850378.png" alt="image-20221113155850378" style="zoom:80%;" />

> 有显著影响，性别对就业，男性多余女性，退休和无业的女性多于男性。

---

## 第7章 多选变量分析

> 用多选变量生成新变量
>
> 多选变量的频数分析
>
> 多选变量的交叉分析

> **目的**：分析多项选择题中变量的频数分布。、

**分析 -> 多重响应**

案例：休闲调查1.sav

要求：对“娱乐目的”进行频数分析，进而分析男女对“娱乐目的”有无差异。

原假设：没有差异。

**首先对娱乐目的进行频数分析**

步骤：

①用多个多选变量生成一个新变量；用“娱乐1”、“娱乐2”、“娱乐3”生成一个新变量“娱乐”。

- 分析 -> 多重响应；

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113165542356.png" alt="image-20221113165542356" style="zoom:50%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113165804222.png" alt="image-20221113165804222" style="zoom:50%;" />

范围填1到6是因为娱乐的值标签：<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113165416373.png" alt="image-20221113165416373" style="zoom: 33%;" />。

②添加完后点击关闭即可。

> 操作完后暂时看不到表格有变化，但在下一步的分析中会看到这个新的变量“娱乐”

③多选变量的频数分析；对新变量“娱乐”进行频数分析。

- 分析 -> 多重响应 -> 频率

  <img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113172127236.png" alt="image-20221113172127236" style="zoom:50%;" />

④点击确定。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113172156232.png" alt="image-20221113172156232" style="zoom:80%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113172214373.png" alt="image-20221113172214373" style="zoom:80%;" />

> 因为有的值是0，所以总计为681，了解了大多数人对娱乐目的的看法，前三位是松弛身心、愉悦精神和结交朋友。

**分析男女对娱乐目的**

步骤：

①分析 -> 多重响应 -> 交叉表

②<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113174445081.png" alt="image-20221113174445081" style="zoom:50%;" />

③点击确定。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113174927730.png" alt="image-20221113174927730" style="zoom: 80%;" />

![image-20221113174953826](https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113174953826.png)

> 可看到男性和女性的娱乐目的，总体的印象是两性对娱乐目的的看法是不同的。男性主要是为了松弛身心，结交朋友和更好地工作，女性是为了愉悦精神，松弛身心和消磨时间。

---

## 第8章 平均数分析与T检验

---

#### 单个样本的T检验

> **目的**：通过样本均值来估计**总体均值是否为某个值**

方法：<img src="E:\SPSS练习\notephoto\微信图片_20221028141515.jpg" alt="微信图片_20221028141515" style="zoom: 25%;" />

> 用t统计量，样本均值 - 减去估计的总体均值 / 样本的标本差 / 个案数的开方

**提出两种假设：**

- H0：μ=μ0 样本均值与总体均值的差异完全是由抽样误差造成的
- H1：μ≠μ0 样本均值与总体均值的差异除了由抽样误差造成，也反映了两个总体均值的确存在差异

##### H0

接受H0：统计值t的相伴概率P值大于α

> H0成立，样本均值与总体均值接近，t 值就应该是0附近的一个值，属于正常值，t的相伴概率P值大于显著性水平α，α一般取0.05

拒绝H0：统计值t的相伴概率P值小于α

> H0不成立，样本均值与总体均值相差比较多，t 值离0较远，这对t值来说是一个异常值，t的相伴概率P小于α

**分析 -> 比较均值 -> 单样本T检验**

案例：休闲调查.asv

要求：对 “休闲调查” 中的 “住房面积” 进行单样本T检验，原假设：户均面积为45平米。

> 原假设即为 μ0=45

步骤：检验一下住房面积的均值是不是等于45

①分析 -> 比较均值 -> 单样本T检验

<img src="E:\SPSS练习\notephoto\屏幕截图 2022-10-28 145309.jpg" alt="屏幕截图 2022-10-28 145309" style="zoom:50%;" />

②点击确定

<img src="E:\SPSS练习\notephoto\微信图片_20221028141516.jpg" alt="微信图片_20221028141516" style="zoom: 80%;" />

> 883个样本的均值是43.981，标准差21.33

<img src="E:\SPSS练习\notephoto\微信图片_20221028141517.jpg" alt="微信图片_20221028141517" style="zoom: 80%;" />

> 单样本检验，检验值是45，t值为-1.419，在0的附近，sig值（显著性）大于阿尔法值0.05，说明不能拒绝原假设，就是接收原假设。

---

#### 独立样本的T检验

> **目的：**通过比较**两个样本**均值差的大小来确定两个总体均值是否相等
>
> H0：μ1=μ2，H1：μ1≠μ2

**分析 -> 比较均值 -> 独立样本T检验** 

**思想：**先进行方差齐性检验 <img src="E:\SPSS练习\notephoto\微信图片_20221028215211.jpg" alt="微信图片_20221028215211" style="zoom: 25%;" />

方差相等和方差不等的方法不同

案例：贫困调查.sav，休闲调查.sav

要求：

- 例1：分析 ”贫困调查“ 中哈尔滨和沈阳两个城市贫困家庭的住房面积是否有差异

> 用城市分成两个整体计算均值是否相等<img src="E:\SPSS练习\notephoto\微信截图_20221028220703.png" alt="微信截图_20221028220703" style="zoom:60%;" />

步骤：

①分析 -> 比较均值 -> 独立样本T检验

<img src="E:\SPSS练习\notephoto\微信截图_20221028220453.png" alt="微信截图_20221028220453" style="zoom:60%;" /><img src="E:\SPSS练习\notephoto\微信截图_20221028220614.png" alt="微信截图_20221028220614" style="zoom:60%;" />

②点击确定

<img src="E:\SPSS练习\notephoto\微信截图_20221028220753.png" alt="微信截图_20221028220753" style="zoom: 80%;" />

> 哈尔滨的样本均值是29.9525，沈阳是29.8119，差不多相等

<img src="E:\SPSS练习\notephoto\微信截图_20221028220840.png" alt="微信截图_20221028220840" style="zoom:80%;" />

> 首先检验两个总体的方差用F检验，原假设是两个总体方差相等，F值为0.000，属于正常值，sig值为0.999大于0.05的显著水平，所以不拒绝原假设，就是说两个的总体方差相等。既然方差相等，我们就用第一行的t值来看均值检验的结果。t值是0.180，在0附近，是正常值，再看sig值是0.857，大于0.05，不拒绝原假设，就是接受H0：μ1=μ2。
>
> 两个总体的均值是相等的，看差值95%置信区间也就是均值之差的置信区间，上下限之间是包含0的，说明两个均值的差是可以等于0的，及两个均值是相等的。
>
> 结论：两个城市的居民租房面积相等。

- 例2：分析 “休闲调查” 中初中与高中学历的人住房面积是否有差异

> 学历：<img src="E:\SPSS练习\notephoto\微信图片_20221029233712.jpg" alt="微信图片_20221029233712" style="zoom: 50%;" />

步骤：

①分析 -> 比较平均值 -> 独立样本T检验

②<img src="E:\SPSS练习\notephoto\微信图片_20221029233944.jpg" alt="微信图片_20221029233944" style="zoom:50%;" /><img src="E:\SPSS练习\notephoto\微信图片_20221029233947.jpg" alt="微信图片_20221029233947" style="zoom:50%;" />

③点击确定。

​										<img src="E:\SPSS练习\notephoto\微信图片_20221029234335.jpg" alt="微信图片_20221029234335" style="zoom: 80%;" />   

> 两种文化程度的租房面积均值是相等的。

![微信图片_20221029234337](E:\SPSS练习\notephoto\微信图片_20221029234337.jpg)

> F=0.285，sig值=0.594大于0.05，所以不拒绝原假设，那么就看假定等方差这列的数值进行分析。
>
> 两个总体的均值是相等的，看“差值95%置信区间”也就是均值之差的置信区间，上下限之间是包含0的，说明两个均值的差是可以等于0的，及两个均值是相等的。

- 例3：分析 “休闲调查” 中40岁以上和40岁以下的人住房面积是否有差异

> 年纪40作为一个分割点

步骤：

①分析 -> 比较平均值 -> 独立样本T检验

②<img src="E:\SPSS练习\notephoto\微信图片_20221029235901.jpg" alt="微信图片_20221029235901" style="zoom:50%;" /><img src="E:\SPSS练习\notephoto\微信图片_20221029235904.jpg" alt="微信图片_20221029235904" style="zoom:50%;" />

③点击确定。

<img src="E:\SPSS练习\notephoto\微信图片_20221030000032.jpg" alt="微信图片_20221030000032" style="zoom:80%;" />

> 两个年龄段的租房面积均值相差较大，40岁以下的大于40岁及以上的，说明年轻人更懂得享受。

![微信图片_20221030000035](E:\SPSS练习\notephoto\微信图片_20221030000035.jpg)

> F值是异常值，sig值小于0.05，拒绝原假设，选择H0：μ1≠μ2，方差不等，选择第二行“不假定等方差”作为均值检验的依据。
>
> t值为-3.916，异常值，sig是0.000，拒绝原假设，两个独立整体的均值是不等的，40岁以下的人租房面积大于40岁及以上的，最后两列“差值...置信区间”，区间不包含0，也就是说这两个整体的均值的差是不等于0的，所以这两个均值是不等的。

---

#### 配对样本的T检验

同一样本的某个变量前后两次测试所得的两组数据，如：贫困人口在获得低保前后的生活满意度。

> **目的：**比较的**两组均值**是否有显著差异

**分析 -> 比较均值 -> 成对样本T检验**

案例：贫困调查.sav

要求：比较收到低保前后对生活的满意度1和满意度2

步骤：

①分析 -> 比较均值 -> 配对样本T检验

②<img src="E:\SPSS练习\notephoto\微信图片_20221030001840.jpg" alt="微信图片_20221030001840" style="zoom:50%;" /><img src="E:\SPSS练习\notephoto\微信图片_20221030001933.jpg" alt="微信图片_20221030001933" style="zoom:50%;" />

③点击确定。

<img src="E:\SPSS练习\notephoto\微信图片_20221030002047.jpg" alt="微信图片_20221030002047" style="zoom: 67%;" />

> 可以看到满意度2高于满意度1。

<img src="E:\SPSS练习\notephoto\微信图片_20221030002049.jpg" alt="微信图片_20221030002049" style="zoom:80%;" />

> 两个满意度的相关系数，是0.882，sig是0.000，拒绝原假设，这里的原假设是两个满意度不相关，而且是高度相关，是正相关。

![微信图片_20221030002052](E:\SPSS练习\notephoto\微信图片_20221030002052.jpg)

> 从差值的均值-7.979可以看到，满意度1是低于满意度2的，“差值...区间”不包含0，也说明满意度1小于满意度2，t值是远离0的异常值，sig值是0.000，小于0.05的显著性水平，说明拒绝原假设，这里的原假设是满意度1等于满意度2。
>
> 说明领取低保后，人们对生活的满意度有较大的的提高，

---

#### 平均数分析过程

> 目的：**多个均值**的比较与检验，确定分类变量与分析变量是否独立（是否相关），如：不同文化程度的人收入是否有显著差异。

**分析 -> 比较均值 -> 平均值**

案例：休闲调查.sav

要求：对不同文化程度的人户均租房面积进行平均值分析。

步骤：

①分析 -> 比较均值 -> 平均值

②<img src="E:\SPSS练习\notephoto\微信图片_20221030003121.jpg" alt="微信图片_20221030003121" style="zoom:50%;" /><img src="E:\SPSS练习\notephoto\微信图片_20221030003123.jpg" alt="微信图片_20221030003123" style="zoom:50%;" />

③点击确定。

<img src="E:\SPSS练习\notephoto\微信图片_20221030003234.jpg" alt="微信图片_20221030003234" style="zoom:80%;" />

> 所有的个案都被用到。

<img src="E:\SPSS练习\notephoto\微信图片_20221030003236.jpg" alt="微信图片_20221030003236" style="zoom:80%;" />

> 可以看出，文化程度越高，住房面积越大，所以文化程度是影响住房面积的。
>
> 要理论上的均值差异需要用到方差分析。

---

## 第9章 一元方差分析

> **任务：**研究名义变量或顺序变量与尺度变量之间的关系。
>
> 尺度变量：因变量；
>
> 名义变量或顺序变量：自变量。
>
> **目的：**想知道当自变量去不同水平时因变量是否有显著差异。

方法：

- 简单方差分析（F检验）
- 平均数多重比较的方差分析（T检验）

---

#### 简单方差分析（一元方差分析）

> 方法，F检验：通过比较组内差异和组间差异的大小来确定变量之间是否相关。若组内差异大而组间差异小，则说明两个变量不相关；若组内差异小而组间差异大，则说明两个变量相关。

前提条件：因变量在影响因素的各个水平服从正态分布且具有等方差性。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221113205349101.png" alt="image-20221113205349101" style="zoom: 33%;" />

> 差异的比值是F，它是服从F分布的一个统计量。
>
> 若组间差异大组内差异小，说明比值的分子大分母小，则F值大，此时两个变量相关；
>
> 若组间差异小组内差异大，说明比值的分母大分子小，则F值小，是一个正常的值，此时两个变量无关

原假设：各组均值是相等的，F值是正常值，偏小

**分析 -> 比较均值 -> 单因素方差分析**

---

案例1：休闲调查1

要求：以“文化程度”为影响因素，对“家月收入”进行方差分析。

步骤：

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120215143158.png" alt="image-20221120215143158" style="zoom:50%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120220628735.png" alt="image-20221120220628735" style="zoom:50%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120220644051.png" alt="image-20221120220644051" style="zoom:50%;" />

点击确定。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120220823526.png" alt="image-20221120220823526" style="zoom:80%;" />

> 关注均值的一列，文化程度越高，家庭月收入越大，初步判断两个变量相关。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120220854584.png" alt="image-20221120220854584" style="zoom:80%;" />

> 原假设是各组方差没有显著差异，这里的显著性（P值）大于0.05，说明不拒绝原假设，说明各组家庭月收入的方差具有齐性

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120220909486.png" alt="image-20221120220909486" style="zoom:80%;" />

> F值检验的表，用组间差异除自由度得到平均的组间差异，同理，用组内差异....的平均的组内差异，最后两者相除得到F值，可以看到F值是较大的一个异常值，并且显著性小于0,05，故拒绝原假设（因为概率很小），认为不同文化程度的家庭月收入有显著的差异。

---

案例2：休闲调查

要求：以“文化程度”为影响因素，对“家月收入”进行方差分析（**方差齐性不满足时**用Brown-forsythe和welch检验，近似F检验）。

步骤：

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120222152694.png" alt="image-20221120222152694" style="zoom:50%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120222231304.png" alt="image-20221120222231304" style="zoom:50%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120222252559.png" alt="image-20221120222252559" style="zoom:50%;" />

点击确定。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120222451232.png" alt="image-20221120222451232" style="zoom:80%;" />

> 可以看出文化程度越高，家庭月收入的平均值越大，初步说明两者有关系

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120222512218.png" alt="image-20221120222512218" style="zoom:80%;" />

> 拒绝原假设，说明各组的方差不等。各组的家庭月收入不具有方差齐性。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120222529778.png" alt="image-20221120222529778" style="zoom:80%;" />

> 因为方差不具有齐性，故不能用此表判断。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120222554970.png" alt="image-20221120222554970" style="zoom:80%;" />

> 都是0.000，拒绝原假设，说明各组的家庭月收入的均值不等，有显著差异。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221120223349461.png" alt="image-20221120223349461" style="zoom:80%;" />

> 可以看到随着文化程度的增高，月收入的平均值是随之增高的。

---

#### 平均数多重比较的方差分析

- **分析 -> 比较均值 -> 单因素方差分析**
- **“两两比较”——”LSD“**（能达到显著性水平的最小差异），用T检验的方法完成各组均值的比较。

案例：休闲调查1

要求：以“休闲调查1”中以“文化程度”为影响因素，对“家月收入”进行多重比较的方差分析。

步骤：

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221121234858361.png" alt="image-20221121234858361" style="zoom:50%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221121235554150.png" alt="image-20221121235554150" style="zoom:50%;" />

> 此处的事后比较就是两两比较

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221121235615014.png" alt="image-20221121235615014" style="zoom:50%;" />

点击继续，回到“单因素 ANOVA 检验”窗，点击选项。<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221121235732105.png" alt="image-20221121235732105" style="zoom:50%;" />

点击继续，点击确定。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221121235813001.png" alt="image-20221121235813001" style="zoom:80%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221121235827805.png" alt="image-20221121235827805" style="zoom:80%;" />

> 0.692，大于0.05，认为不拒绝方差假设。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221121235845772.png" alt="image-20221121235845772" style="zoom:80%;" />

> F检验的结果，根据F值和P值，应该拒绝原假设。认为各组均值有显著差异。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221121235924043.png" alt="image-20221121235924043" style="zoom:80%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122000004163.png" alt="image-20221122000004163" style="zoom:80%;" />

> 在显著性里找小于0.05的数字，例如“大专”和“大学本科及以上”，就说明“没读过书”和这两组的家庭月收入是有显著差异的。可以看到这两组的平均值差值在右上角有*号，这个符号就说明对应的这两组人与对比组有显著差异。
>
> 小学没有。
>
> “初中”与“大专”和“大学本科及以上”的两组人的家庭月收入的均值有显著差异。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122000029056.png" alt="image-20221122000029056" style="zoom:80%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122000042931.png" alt="image-20221122000042931" style="zoom:80%;" />

> “高中”与“大专”和“大学本科及以上”的两组人的家庭月收入的均值有显著差异。
>
> ”大专“与“初中”和“高中”的两组人的家庭月收入的均值有显著差异。
>
> “大学本科及以上”与“初中”和“高中”的两组人的家庭月收入的均值有显著差异。

---

#### 二因素的方差分析

> 目的：分析两个因素（自变量）对观测变量（因变量）的影响。

**分析 -> 一般线性模型 -> 单变量**

案例：休闲调查.sav

要求：以“文化程度、就业情况”为影响因素，对“月收入”进行多重比较的方差分析（包含交互效应）。

步骤：

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122002626039.png" alt="image-20221122002626039" style="zoom: 67%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122002755862.png" alt="image-20221122002755862" style="zoom: 67%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122002810252.png" alt="image-20221122002810252" style="zoom: 67%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122003113338.png" alt="image-20221122003113338" style="zoom:67%;" />

> 全因子，包含3个自变量，文化程度，就业情况，以及它们两者的交互效应。
>
> 定制的话可以自己选择因子，类型可选交互、主效应，所有二阶的意思是：除了文化程度和就业情况，还包括这两个因素的平方。
>
> 我们此题选择全因子模型。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122003438285.png" alt="image-20221122003438285" style="zoom:67%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122003459150.png" alt="image-20221122003459150" style="zoom:67%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122003822227.png" alt="image-20221122003822227" style="zoom:67%;" />

点击继续，点击确定。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122003854542.png" alt="image-20221122003854542" style="zoom:80%;" />

> 首先按文化程度分类，每一个类人的个案数，可以看到初中的人最多，没读过书的这一类人最少。
>
> 若按就业情况分类，可以看到在职在岗的人最多，内退的人最少

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122003959173.png" alt="image-20221122003959173" style="zoom:80%;" />

> 没读过书且离退休的月收入均值是665元

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122004141054.png" alt="image-20221122004141054" style="zoom:80%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122004208545.png" alt="image-20221122004208545" style="zoom:80%;" />

> 总体看下来，发现文化程度是大学本科及以上，就业情况是再就业，这类人群的月收入均值是最高的，2400元。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122010018272.png" alt="image-20221122010018272" style="zoom:80%;" />

> 重要的表之一，根据要求自变量是 文化程度、就业情况 和 文化程度与就业情况的交互效应。
>
> 可以看到这三个自变量结合F值和显著性的值构成的表。看出 文化程度 的显著性是0.042，小于0.05，说明它对月收入的影响是显著的，而其他量因素的影响是不显著的。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122010034804.png" alt="image-20221122010034804" style="zoom:80%;" />

![image-20221122010056396](https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122010056396.png)

> 总的均值是1039.907。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122004223344.png" alt="image-20221122004223344" style="zoom:80%;" />

> 随文化程度的增到，月收入均值呈上升趋势。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122004236993.png" alt="image-20221122004236993" style="zoom:80%;" />

> 可以看到再就业的人月收入均值是最高的，最低的是病伤休。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122004300586.png" alt="image-20221122004300586" style="zoom:80%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122004334141.png" alt="image-20221122004334141" style="zoom:80%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122004408517.png" alt="image-20221122004408517" style="zoom:80%;" />

> 和描述性统计的图类似。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122010850627.png" alt="image-20221122010850627" style="zoom:80%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122010900158.png" alt="image-20221122010900158" style="zoom:80%;" />

> 文化程度是等级类型的自变量，可以看到，随着文化等级的升高，月收入的平均值是呈现升高的变化趋势。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221122010912378.png" alt="image-20221122010912378" style="zoom:80%;" />

> 可以直观的看到再就业这一类人的月收入均值最高。

---

#### 协方差分析

> **目的：**在因素中包含连续型变量（协变量），对观测变量（因变量）进行更准确的分析。

事实上，自变量有时候会包括想年龄这样的连续性变量，如果做方差分析的时候没有考虑连续性变量，那么这种方差分析是不够准确的，所以我们需要把这种连续性变量包括进来做方差分析，这就是协方差分析。

**分析 -> 一般线性模型 -> 单变量**

案例：休闲调查1.sav

要求：以“文化程度、就业情况”为影响因素，以“年龄”为协变量，对“月收入”进行方差分析（增加参数估计）

> 年龄使连续变量

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207125647142.png" alt="image-20221207125647142" style="zoom:50%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207125647142.png" alt="image-20221207125647142" style="zoom:50%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207125852366.png" alt="image-20221207125852366" style="zoom:50%;" />

结果：

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207125941597.png" alt="image-20221207125941597" style="zoom: 67%;" />

可以看到在文化程度的分类上，初中这一类人最多，就业情况在职在岗使最多的。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207130050103.png" alt="image-20221207130050103" style="zoom:67%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207130111987.png" alt="image-20221207130111987" style="zoom: 67%;" />![image-20221207130128447](https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207130128447.png)

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207130111987.png" alt="image-20221207130111987" style="zoom: 67%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207130128447.png" alt="image-20221207130128447" style="zoom:67%;" />

> 可以看到总体时随着……升高而升高

![image-20221207130942401](https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207130942401.png)

> 只有文化程度和月收入的影响是显著的

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207131804996.png" alt="image-20221207131804996" style="zoom:67%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207131837632.png" alt="image-20221207131837632" style="zoom:67%;" />

> 看B值，先找一个类比值，文化程度是7，就业情况是11的时候B值都为0，我们吧这两种情况作为一个标准情况，也就是说这两种情况的人的月收入是最高的，也就是1649.259.作为一个标准，在此标准上，如果其他情况不变。把文化程度换成1，那个月收入就会减少883。
>
> 年龄的B值为-4.146，就是说年龄增加一岁就会减少4.146.

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207132803362.png" alt="image-20221207132803362" style="zoom:67%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207132824991.png" alt="image-20221207132824991" style="zoom:67%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207132842738.png" alt="image-20221207132842738" style="zoom:67%;" />

---

### 第10章 相关与回归分析

名义类型，尺度类型

如何进行尺度类型和尺度类型的变量比较

**分析->相关**

皮尔孙

先做散点图，看两个变量之间是否有线性相关分析

休闲调查1

“住房面积”和“家月收入”作相关分析

住房面积为x轴，家月收入为y轴

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207133333958.png" alt="image-20221207133333958" style="zoom:50%;" />

选择简单散点

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207133444570.png" alt="image-20221207133444570" style="zoom:50%;" />

![image-20221207133517238](https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221207133517238.png)

正相关

---

## 第11章 非参数检验

**参数检验**是通过对样本的参数计算去推断总体的参数，比如均值、方差，在做参数检验时，我们通常对分布以及方差具有一些**假定**，比如假定分布式正态分布或者方差具有齐性，但是在很多情况下条件是不满足或者未知的，name这个时候参数检验就显得很不方便收到了限制，这时我们做**非参数检验**就很方便。

> **目的：**通过样本的分布对总体的分布进行检验。

因为不涉及对参数的推断所以叫非参数检验。

**内容：**

- 卡方检验（比如检验某个变量的观测频次是否与理论频次一致）

- 二项分布检验（是二项分布当中的比例）
- 游程检验（检验数据的随机性）
- 单个样本的分布特征检验（检验发单个样本的分布是否是某种分布，比如是否是正态分布、均匀分布之类的）
- 两个独立样本的检验（是检验两个独立样本的分布是否相同）
- 多个独立样本的检验（是通过样本去推断多个总体的分布是否相同）
- 两个相关样本的检验（通过样本对两个相关样本去检验它们的分布是否相同，或者是否有差异）
- 多个相关样本的检验（是通过样本去检验多个相关样本的分布是否有差异）

---

#### 卡方检验

> **目的：**通过样本检验总体中**单个变量**的观测频次与期望频次是否一致

**分析 -> 非参数检验 -> 旧对话框 -> 卡方**

案例：贫困调查.sav

要求：用数据中的 “身体状况” 的数据的分布来检验目前贫困人口的身体状况与下述比例是否一致。

> 可知，贫苦人口被分为下面的五类，

<img src="E:\SPSS练习\notephoto\微信图片_20221030021340.jpg" alt="微信图片_20221030021340" style="zoom: 25%;" />

表中的频次我们叫做 “理论频次” 也就是 “希望比例”，我们观测它是否与 “观测比例” 相同。

先看身体状况<img src="E:\SPSS练习\notephoto\微信图片_20221030021927.jpg" alt="微信图片_20221030021927" style="zoom: 67%;" />（用数字代表五种情况）

步骤：

①分析 -> 非参数检验 -> 旧对话框 -> 卡方<img src="E:\SPSS练习\notephoto\微信图片_20221030022124.jpg" alt="微信图片_20221030022124" style="zoom: 33%;" />

②<img src="E:\SPSS练习\notephoto\微信图片_20221030022617.jpg" alt="微信图片_20221030022617" style="zoom:50%;" />

> 期望值的值，使用总样本数443分别乘以期望频次所得。

③点击确定。

<img src="E:\SPSS练习\notephoto\微信图片_20221030022912.jpg" alt="微信图片_20221030022912" style="zoom:80%;" />

> 可以看到“观测频次”和“期望频次”差异较大，观测频次远小于理论频次。

<img src="E:\SPSS练习\notephoto\微信图片_20221030022915.png" alt="微信图片_20221030022915" style="zoom: 80%;" />

> 卡方值越大越应该拒绝原假设，原假设是说“观测频次”和“期望频次”是没有显著差异的，而现在我们所得的卡方值是一个较大的值，且渐进显著性是0.000，说明我们应该拒绝原假设，就是说“观测频次”和“期望频次”有显著的差异，实际上身体健康这类人的观测人数是远远小于期望人数的。
>
> 图下方的标注，是做卡方检验时的要求，可以看到期望频率不能低于5，二我们的期望的最低单元格时22.0，所以得到的卡方检验是有效的。

---

#### 二项分布检验

在二项分布中对关心的是两类的概率，可以通过对样本当中两类的频率来推断总体当中两类的额概率

> **目的：**通过样本推断总体中两类的概率是否为给定值

方法：近似**Z**检验 <img src="E:\SPSS练习\notephoto\微信图片_20221030102236.jpg" alt="微信图片_20221030102236" style="zoom: 25%;" />

> p：样本当中的两类的比例
>
> π：总体当中的两类比例
>
> 在这个假设之下，π 近似的服从正态分布，把 p 标准化，就可以得到一个标准化的正态变量，然后通过 p 这个统计量的值以及显著性水平的值就可以决定是接收原假设还是拒绝原假设。

**分析 -> 非参数检验 -> 旧对话框 -> 二项分布**

案例：贫困调查.sav

要求：前期调查表名，贫困人口中绝大多数是无业者，在职人员不到10%，用“贫困调查”中“人员类别”来检验总体是否为上述比例。

> 本着拒绝的原则，本题我们提出的原假设H0是p≥0.1

先看人员类别的分类 <img src="E:\SPSS练习\notephoto\微信图片_20221030105301.jpg" alt="微信图片_20221030105301" style="zoom:67%;" />

> 我们可以将人员类别分为两类，1作为一个分割点，在职的值≤1，第二类没有工作的的＞1

步骤：

①分析 -> 非参数检验 -> 旧对话框 -> 二项分布

②<img src="E:\SPSS练习\notephoto\微信图片_20221030110233.png" alt="微信图片_20221030110233" style="zoom: 50%;" />

③点击确定。

<img src="E:\SPSS练习\notephoto\微信图片_20221030110236.jpg" alt="微信图片_20221030110236" style="zoom:80%;" />

> 表格中给出了第一类在职个案数是29个，而个案总数是442，29/442得到实测比例0.062，四舍五入得0.1，检验比例是0.1，显著性为0.007小于0.05，应该拒绝原假设，所以在职人员的比例远远小于0.1，事实上样本中的比例是0.063.

---

#### 游程检验

> **目的：**分析一个二分名义变量Y与尺度变量X的关系，检验样本的随机性。

**分析 -> 非参数检验 -> 旧对话框 -> 游程**

案例：休闲调查.sav

要求：检验大专以下文化水平0和以上1的被调查者的住房面积是否有显著差异。

方法：先将尺幅变量X排序，用名义变量Y的取值作为标志将数据分为两类，Y的每个标志的一个持续是一个**游程**，对游程数据进行Z检验。

> **游程数是一个近似的服从正态分布随机变量。**
>
> 游程：下图中前三个0表示大专以下的文化水平，这就是一个游程。第四个数字1表示大专以上的，这是第二个游程。47、56、58代表的是大专以下的，这是第三个游程。...
>
> <img src="E:\SPSS练习\notephoto\微信图片_20221030111908.jpg" alt="微信图片_20221030111908" style="zoom: 33%;" />
>
> 可得目前学历有六个游程

如果学历与住房面积相关，假设学历越高，住房面积越大，那么游程表前面应该都是0后面都是1，游程数为2

如果学历与住房面积无关，那么它应该是一个随机序列，此时游程数不确定

原假设：序列是随机的，则游程数U不应太少也不应太多，近似服从正态分布。<img src="E:\SPSS练习\notephoto\微信图片_20221030124121.jpg" alt="微信图片_20221030124121" style="zoom:25%;" />

> 具体的来说，游程数U是按照上面那样的公式计算它的均值和方差，m、n是名义变量中两类的个数，此题中就是大专以下和大专以上这两类人的个数。
>
> 在游程检验的时候首先对尺度变量按照升序排列，然后假设名义变量是一个随机的序列，也就是意味着这两个变量是不相关的，然后计算游程数，根据游程数的多少以及显著性水平的值判断接受原假设或拒绝原假设

步骤： 

> 打开表格，可知住房面积是尺度类型的变量，文化程度是名义类型的变量。
>
> 目的：分析这两个变量之间的相关性

> 注意：首先要把尺度变量排序

> <img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221031213847197.png" alt="image-20221031213847197" style="zoom: 67%;" />可以看到文化程度的值标签，按升序排序，数值越大学历越高，本实验以6（大专）作为分割点将数据分为两类

①数据 -> 个案排序

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221031214234431.png" alt="image-20221031214234431" style="zoom:50%;" />

②分析 -> 非参数检验 -> 旧对话框 -> 游程。

③<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221031214556581.png" alt="image-20221031214556581" style="zoom:50%;" />

④点击确定。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221031214619560.png" alt="image-20221031214619560" style="zoom:80%;" />

> 可以看到，检验值（割点）是6，个案总数是883，游程数是169，这就属于优，说明这个结果是近似服从正态分布的，标准化以后就是标准的正态变量，这个正态变量就是 Z 为-13.537，对一个正态分布的变量来说，Z 值是一个异常值，结合渐进显著性的值为0.000，故应拒绝原假设（此题的原假设是当学历按升序排序后，住房面积是一个随机序列，就是说学历与住房面积无关），认为学历与住房面积是相关的

---

#### 单个样本的分布特征检验（重点）

> **目的：**根据样本的分布检验总体是否服从某种分布

方法：柯尔莫哥洛夫·斯米诺夫检验（K-S）

**分析 -> 非参数检验 -> 旧对话框 -> 单样本K-S**

案例：休闲调查.sav

要求：检验住房面积是否服从正态分布

统计量：Z

**检验原理：**

H0：对所有x值 Fn(x)=F0(x )成立

H1：至少有一个x值使 Fn(x)≠F0(x) 成立

> Fn(x) 是随机样本 x1，x2，...，xn 的经验分布函数
>
> <img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221031221531385.png" alt="image-20221031221531385" style="zoom:25%;" />
>
> 经验分布函数其实就是 xi ≤ x 的频率
>
> 事件 xi 小于等于 x 发生的次数除以 n，n是样本的观测数，得到发生次数的频率
>
> 分布函数实际上就是 xi ≤ x 发生的概率
>
> 经验分布函数其实就是 xi ≤ x 的频率去近似的来代替这个事件发生的概率
>
> **经验分布函数Fn(x)**是**总体分布函数F0(x)**的一个估计，就是说**这个频率是概率的一个估计**
>
> <img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221031235358035.png" alt="image-20221031235358035" style="zoom: 33%;" />
>
> **若样本服从理论分布，则D不应太大，否则拒绝H0**
>
> 这个D是渐进的服从正态分布的：<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101000013865.png" alt="image-20221101000013865" style="zoom: 25%;" />

步骤：

①分析 -> 非参数检验 -> 旧对话框 -> 单样本K-S

②<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101000226900.png" alt="image-20221101000226900" style="zoom:50%;" />

③点击确定

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101000312995.png" alt="image-20221101000312995" style="zoom:80%;" />

> （*标准差表示的就是样本数据的离散程度。*）
>
> 正态分布的检验结果。
>
> 最极端差值的绝对值，就是经验分布函数和总体分布函数的差值的最大值的绝对值
>
> 标准统计量 Z 值是0.120，显著水平小于0.05，所以拒绝原假设，这个租房面积不是正态分布。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101000336269.png" alt="image-20221101000336269" style="zoom:80%;" />

> 均匀分布的检验结果。
>
> D值是0.465，Z值是13.804，显著性小于0.05，拒绝原假设，租房面积不是均匀分布。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101000350320.png" alt="image-20221101000350320" style="zoom:80%;" />

> 泊松分布的检验结果。
>
> 泊松分布是离散型的，而我们要检验的是连续的，所以无法执行，此检验没有意义。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101000416777.png" alt="image-20221101000416777" style="zoom:80%;" />

> 指数分布的检验结果。
>
> D值为0.295
>
> Z值为8.771，异常值，显著性0.000，不是指数分布。

总结，租房面积不是正态分布，不是均匀分布，也不是指数分布。

---

#### 两个独立样本的分布特征的检验

> **目的：**检验两个独立样本是否有相同的分布

方法：mann-whitney u秩和检验，Z统计量、

- 检验两样本在某些位置上是否值相同。首先合并两样本，按升序排列，得出每个数据的秩，然后对两样本求平均秩，若差距过大，则认为两总体分布不同。

  > 求秩：例如两男两女按数学等级排序，第一和第四是女，第二和第三是男，则女生的秩是(1+4)/2=2.5，男生的秩是(2+3)/2=2.5，所以男女的秩相同。则若秩相差较大，则两总体的分布不同。

**分析 -> 非参数检验 -> 旧对话框 -> 2独立样本**

案例：休闲调查.sav

要求：检验不同性别的被调查者的“文化程度”是否有差异。

步骤：

①分析 -> 非参数检验 -> 旧对话框 -> 2独立样本

②<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101003206402.png" alt="image-20221101003206402" style="zoom:50%;" />

③点击确定。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101003303013.png" alt="image-20221101003303013" style="zoom: 67%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101003254726.png" alt="image-20221101003254726" style="zoom:80%;" />

> 可以看到男女文化程度的平均值相差较大。男性的平均秩大于女性的平均秩，说明男性排在后面的比较多，因为数字越大说明学历越高，所以高学历中男性多一些。
>
> *秩的总和/个案数=秩平均值*

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101003313141.png" alt="image-20221101003313141" style="zoom:80%;" />

> Z 值是一个异常值，显著性水平是0.001，拒绝原假设，认为男女两性文化差异是有显著差异的。

---

#### 多个独立样本的分布特征的检验

> **目的：**检验多个独立样本是否分布相同，可起到方差分析的作用，但对总体分布没有要求，如不要求等方差性、正态性。

方法：mann-whitney的拓展，看各组的平均秩是否相差很大，卡方统计量

**分析 -> 非参数检验 -> 旧对话框 -> k独立样本**

案例：休闲调查.sav

要求：检验不同文化程度的被调查者的“住房面积”是否有差异。

> 会将文化程度分成多个独立样本组，对比每一组的不同文化程度的住房面积是否有显著差异

步骤：

①分析 -> 非参数检验 -> 旧对话框 -> k独立样本

②<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101004830405.png" alt="image-20221101004830405" style="zoom:50%;" />

③点击确定

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101004913671.png" alt="image-20221101004913671" style="zoom: 80%;" />

> 按升序排列，后面的秩也就越大，说明学历越高租房面积越大。
>
> 初步印象，不同学历的人租房面积是有显著差异的。
>
> 卡方值为267.932，用各组的秩的平均值减去总的秩的平均值然后求平方和，渐进显著性是0.000，故拒绝原假设，认为各组的租房面积是有显著差异的。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101004948630.png" alt="image-20221101004948630" style="zoom:80%;" />

> 两行七列的交叉列表。可以看到，租房面积大于中位数的这组，学历高的人数比较多；租房面积小于中位数的这组，初中和高中的人数比较多，高学历的人较少，初步说明学历高的人租房面积越大。
>
> 看检验统计表，卡方值234.345，很大，用列表中的每一个单元格的观测值减去期望值然后再除以期望值后求平均和，且渐进显著性小于0.05，同样说明拒绝原假设。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221101005025139.png" alt="image-20221101005025139" style="zoom:80%;" />

> J-T的检验结果。分组变量是顺序变量的检验方法，这里的文化程度就是一个顺序变量。
>
> 标准的J-T统计量的14.804，渐进显著性小于0.05，同样表明拒绝原假设。说明不同学历的租房面积是不一样的。

---

#### 两个相关样本的分布特征的检验

> **目的：**检验两个配对样本是否分布相同

方法：

- 符号检验，第2组样本观测值减去第1组对应值，看差值的符号，若正数个数与负数个数差距较大，则两样本差异显著；
- 符号秩检验，是符号检验的扩展，若没有差异，不但正数个数与负数个数大致相等，而且正负秩和也大致相等。

**分析 -> 非参数检验 -> 旧对话框 -> 2相关样本**

案例：贫困调查.sav

要求：检验获得低保前后生活满意度是否与变化。

统计量：Z

步骤：

①分析 -> 非参数检验 -> 旧对话框 -> 2相关样本

②<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221108175120617.png" alt="image-20221108175120617" style="zoom:50%;" />

> “检验类型”中的前两种方法适合连续类型的变量；第三种适合于二元数据的检验，比如这个数据是二分的名义变量；第四种用于多分类数据

③点击确定。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221108175242995.png" alt="image-20221108175242995" style="zoom:80%;" />

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221108175306930.png" alt="image-20221108175306930" style="zoom: 80%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221108175439097.png" alt="image-20221108175439097" style="zoom: 80%;" />

> 负秩少于正秩，说明满意度2普遍大于满意度1，差值都是正的。秩平均值是秩的总和除以秩的个数，充分说明领取低保前后满意度是有显著差异的。
>
> Z是 -18.075，不是一个正常值，显著性水平小于0.05，故拒绝原假设，认为分布特征不同。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221108175504377.png" alt="image-20221108175504377" style="zoom: 80%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221108175517167.png" alt="image-20221108175517167" style="zoom: 80%;" />

> 和上面哪个方法完全一致。负差值和正差值差别很大，两个满意度有显著差异。

---

#### 多个相关样本的分布特征检验

> 目的：检验多个相关样本是否有相同分布

方法：Friedman秩分析，合并样本按升序排列，求每个观测值在各自行中的秩和，若相差很大，则认为有显著差异。卡方统计量。Kendal's W秩分析，先用通过秩分析的方法计算出肯德尔和谐系数，再做卡方检验，同样是卡方统计量。

**分析 -> 非参数检验 -> 旧对话框 -> k相关样本**

案例：比赛成绩.sav

要求：检验10个裁判对20名选手的评分有无差异。

统计量：卡方统计量

步骤：

①分析 -> 非参数检验 -> 旧对话框 -> k相关样本

②<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221108181653088.png" alt="image-20221108181653088" style="zoom:50%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221108181707278.png" alt="image-20221108181707278" style="zoom: 67%;" />

③点击确定。

<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221108181808499.png" alt="image-20221108181808499" style="zoom:80%;" />

**傅莱德曼检验**<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221108181916928.png" alt="image-20221108181916928" style="zoom:80%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221108181941113.png" alt="image-20221108181941113" style="zoom:80%;" />

> 每个裁判打的分数都和别的相比较得出一个秩，裁判2的平均秩是1.28，说明他打的分数排的比较前，若按升序排的，说明裁判2打的分数较低。
>
> 可以看到裁判打分之间的秩平均值差异是比较大的，最小1.28，最大8.45，卡方值是85.526，很大，显著性是0.000小于0.05，拒绝原假设

**肯德尔 W 检验**<img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221108182032299.png" alt="image-20221108182032299" style="zoom:80%;" /><img src="https://tty79-1314711180.cos.ap-nanjing.myqcloud.com/images/image-20221108182049797.png" alt="image-20221108182049797" style="zoom:80%;" />

> 结论与上一个检验方法差不多。

---
