需求：冒泡排序。
理论：1.比较轮数n-1。  2.比较次数n-1。  3.符合某个条件交换位置。
核心：双重for循环。
步骤：
     1.双重for循环。
     2.指定轮数和次数
     3.判断是否符合标准。如果符合标准交换位置。# Bubble-Sort
     
开闭原则。（写在第一个for循环里，是为了，每轮比较初始化bool变量变为true。）
bool这个变量默认值为true;如果本轮比较有一对元素相互交换位置，那么也不能跳出循环。
        但是，如果本轮比较没有任何元素相互交换位置，那么说明已经比较完成，可以跳出循环。
    
