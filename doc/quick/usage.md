# 快速上手
 ------------

 在完成了[安装](/install/install.html)之后，就可以快速调取数据。方法很简单，只需要两行代码:

    import dtshare as dt

    #获取股票当日的实时tick
    df = dt.get_tick_data('600000')

通过打印，可以看到以下数据效果：


            time  price  vol type
	0     091503  21.64   29    -
	1     091509  21.65   93    -
	2     091536  21.64  129    -
	3     092427  21.63  295    -
	4     092442  21.62  295    -
	...      ...    ...  ...  ...
	2105  145652  21.46   16   buy
	2106  145655  21.46   52   buy
	2107  145658  21.46    3   buy
	2108  145702  21.47    2   sale
	2109  150059  21.46  415   buy