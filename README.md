
# coupon-collector-problem
卡片收集问题

安装依赖包：
```shell
pip install pandas numpy sympy jupyter xlrd openpyxl matplotlib
```

### 解决问题1：理论计算P(n, m)
设卡片有m张，抽取机会有n次，n次及n次之前就能集齐的概率。

### 解决问题2：理论计算Em
集齐所有m卡片的期望抽卡次数

### 模拟统计
给定人数（1000000）抽m张卡，最多抽n次，集卡情况统计（m-n次都可能集齐）


备注：不是一定到n次才集齐，到了n次不一定能集齐。




#### 参考资料：
https://blog.csdn.net/wenrr89/article/details/54688469  
https://en.wikipedia.org/wiki/Coupon_collector%27s_problem  
https://blog.csdn.net/qq_32028759/article/details/100580328
