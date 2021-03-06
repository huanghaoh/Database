## 什么是UML

UML（统一建模语言），它是一种由一整套图表组成的标准化建模语言。UML用于帮助系统开发人员阐明，展示，构建和记录软件系统的产出。UML代表了一系列在大型而复杂系统建模中被证明是成功的做法，是开发面向对象软件和软件开发过程中非常重要的一部分。这里介绍几种图的使用。

## UML概念模型

![image-20220305165351673](http://reujbch3s.hn-bkt.clouddn.com/img/202203051653733.png)

### 事物

#### 结构事物（Structural Thing）

模型的静态部分，用于描述概念元素或物理元素。例如类、接口、用例、工件、节点等。

#### 行为事物（Behavioral Thing）

模型的动态部分，代表跨越时间和空间的行为。例如交互、状态机、活动等。

#### 分组事物（Grouping Thing）

模型的组织部分。例如包，还有其他的诸如子系统、层等基于包的扩展事物。

#### 注释事物（Annotational Thing）

模型的解释部分，用于描述、说明和标注模型的任何元素。例如注解（Note）。

### 关系

#### 泛化（Generalization）

子类继承父类。使用实线加空心箭头，由子类指向父类。

![image-20220305165933015](http://reujbch3s.hn-bkt.clouddn.com/img/202203051659045.png)

#### 实现（Realization）

实现一个接口或者继承抽象类。使用虚线加空心箭头，由实现类指向接口。

![image-20220305170605115](http://reujbch3s.hn-bkt.clouddn.com/img/202203051706145.png)

#### 组合（Composition）

整体与部分的关系，部分不能脱离整体单独存在。使用实线加实心菱形，由部分指向整体。

![image-20220305170927548](http://reujbch3s.hn-bkt.clouddn.com/img/202203051709582.png)

#### 聚合（Aggregation）

整体与部分的关系，部分可以脱离整体单独存在。使用实线加空心菱形，由部分指向整体。

![image-20220305171140198](http://reujbch3s.hn-bkt.clouddn.com/img/202203051711226.png)

#### 关联（Association）

表示类与类之间的关系，通常将一个类作为另一个类的成员变量，组合和聚合是特殊的关联。双向关联，一条实线或一条实线加两个箭头；单向关联，一条实线加一个箭头。自关联，自己指向自己。

![image-20220305175629821](http://reujbch3s.hn-bkt.clouddn.com/img/202203051756864.png)

#### 依赖（dependency）

表示类与类之间的关系，通常是某个类的方法使用另一个类的对象做参数，耦合性比关联低。使用虚线加箭头，指向被依赖。

![image-20220305180257280](http://reujbch3s.hn-bkt.clouddn.com/img/202203051802314.png)