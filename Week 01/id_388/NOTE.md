# NOTE

### 第一周总结
    这周主要讲了两大块，第一块是数组链表和跳表，第二块是栈和队列。

#### 1、数组、链表和跳表
    数组的读取操作时间复杂度是1，但是插入和删除操作时间复杂度较高。然后分析了java的arrayList。
    为了解决删除和插入的问题，引入了linklist。但是linklist查询效率不高，因此引入了调表，时间复杂度是logn
    
    实战中
    
#### 2、栈和队列
    栈的特点是先入后出，队列是先进先出。
    
    java源码查找方式：google输入java queue source code download.这样可以查找到源码，或者下载到idea查看。
     
     java的队列和栈有多种实现方式。这次学习优先级队列，默认最小的在队首，可以自定义比较函数。
     
    课后作业接雨水问题有种方案用到了栈这个数据结构。
    用栈记录左边界，直到新入的高度大于栈顶元素，则通过距离和高度差计算面积，直到栈为空。

