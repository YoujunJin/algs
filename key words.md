第一章
Java的语言编程模型，继承，泛型，接口，内存回收机制，引用，参数传值传递，静态类方法，成员，5类基本输入输出，可迭代集合类型及重写接口
抽象数据类型，API，背包，队列，栈，链表
算法分析，增长数量级，成本模型，
Union-find算法：quik-find（id[]保存同一个分量相同值），quick-union（森林表示，根节点相同为连通），加权的quick-union（额外空间记录树大小，小树连到大树上），最优的算法，压缩路径的加权quick-union（find时额外循环把每个触点都直接链接到根节点）。

第二章 排序
原地排序算法及需要额外空间存储数组副本的其他排序方法，定义compareTo方法
初级：选择排序（On方）、插入排序（On到On方）、希尔排序（首选，不到On2）、
高级：归并排序（任何情况都是Onlgn，空间On)，快速排序（Onlgn，辅助空间很小，应用广泛，最坏On2）
哨兵，把一个最值元素放在头或尾用来避免数组边界检测
优先队列，堆，二叉堆（数组，完全二叉树），堆算法（swim，sink），堆排序（最坏Onlgn，下沉排序，先下沉再上浮排序）

第三章 查找
符号表（字典，索引，键对应值）
