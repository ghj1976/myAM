# 幂等

幂等（idempotent、idempotence）是一个数学与计算机学概念。

在编程中.一个幂等操作的特点是其任意多次执行所产生的影响均与一次执行的影响相同。

幂等函数，或幂等方法，是指可以使用相同参数重复执行，并能获得相同结果的函数。这些函数不会影响系统状态，也不用担心重复执行会对系统造成改变。

例如，“setTrue()”函数就是一个幂等函数,无论多次执行，其结果都是一样的.更复杂的操作幂等保证是利用唯一交易号(流水号)实现.

<http://baike.baidu.com/item/%E5%B9%82%E7%AD%89>

[理解HTTP幂等性](http://www.cnblogs.com/weidagang2046/archive/2011/06/04/idempotence.html)

