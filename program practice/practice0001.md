# 笔试题（编程题0001） 

----------

1、买帽子（[百度2017年春招](https://www.nowcoder.com/test/4998655/summary)）  
 度度熊想去商场买一顶帽子，商场里有N顶帽子，有些帽子的价格可能相同。度度熊想买一顶价格第三便宜的帽子，问第三便宜的帽子价格是多少？  
 **输入描述**:首先输入一个正整数N（N <= 50），接下来输入N个数表示每顶帽子的价格（价格均是正整数，且小于等于1000）  
**输出描述**:如果存在第三便宜的帽子，请输出这个价格是多少，否则输出-1   
**输入例子:**    

    10  
    10 10 10 10 20 20 30 30 40 40
**输出例子:**    
	  
		30

----------

2、度度熊回家（[百度2017年春招](https://www.nowcoder.com/test/4998655/summary)））  

时间限制：1秒  
空间限制：32768K  
一个数轴上共有N个点，第一个点的坐标是度度熊现在位置，第N-1个点是度度熊的家。现在他需要依次的从0号坐标走到N-1号坐标。
但是除了0号坐标和N-1号坐标，他可以在其余的N-2个坐标中选出一个点，并直接将这个点忽略掉，问度度熊回家至少走多少距离？  
**输入描述:**  输入一个正整数N, N <= 50。
接下来N个整数表示坐标，正数表示X轴的正方向，负数表示X轴的负方向。绝对值小于等于100  
**输出描述:**输出一个整数表示度度熊最少需要走的距离。  
**输入例子:**  

	4   
	1 4 -1 3
**输出例子**： 
 
	4	

	
----------
3、寻找三角形（[百度2017年春招](https://www.nowcoder.com/test/4998655/summary)）  
时间限制：1秒  
空间限制：32768K  
三维空间中有N个点，每个点可能是三种颜色的其中之一，三种颜色分别是红绿蓝，分别用'R', 'G', 'B'表示。 
现在要找出三个点，并组成一个三角形，使得这个三角形的面积最大。
但是三角形必须满足：三个点的颜色要么全部相同，要么全部不同。  
 **输入描述:**首先输入一个正整数N三维坐标系内的点的个数.(N <= 50) 
接下来N行，每一行输入 c x y z，c为'R', 'G', 'B' 的其中一个。x，y，z是该点的坐标。(坐标均是0到999之间的整数)  
**输出描述:**输出一个数表示最大的三角形面积，保留5位小数。  
**输入例子:**  
	
    5   
	R 0 0 0  
	R 0 4 0  
	R 0 0 3   
	G 92 14 7  
	G 12 16 8   
**输出例子:** 
 
	  6.00000

----------
4、有趣的排序（[百度2017年春招](https://www.nowcoder.com/test/4998655/summary)）  
时间限制：1秒  
空间限制：32768K  
度度熊有一个N个数的数组，他想将数组从大到小排好序，但是萌萌的度度熊只会下面这个操作：
任取数组中的一个数然后将它放置在数组的最后一个位置。
问最少操作多少次可以使得数组从小到大有序？  
 **输入描述:**首先输入一个正整数N，接下来的一行输入N个整数。(N <= 50, 每个数的绝对值小于等于1000)  
**输出描述:**输出一个整数表示最少的操作次数。  
**输入例子:**  
      
       4   
	   19 7 8 25  
**输出例子:**  

	  2

----------
5、 不等式数列（[百度2017年春招](https://www.nowcoder.com/test/4998655/summary)）  
 时间限制：1秒  
空间限制：32768K  
度度熊最近对全排列特别感兴趣,对于1到n的一个排列,度度熊发现可以在中间根据大小关系插入合适的大于和小于符号(即 '>' 和 '<' )使其成为一个合法的不等式数列。但是现在度度熊手中只有k个小于符号即('<'')和n-k-1个大于符号(即'>'),度度熊想知道对于1至n任意的排列中有多少个排列可以使用这些符号使其为合法的不等式数列。   
**输入描述:**输入包括一行,包含两个整数n和k(k < n ≤ 1000)  
**输出描述:**输出满足条件的排列数,答案对2017取模。  
**输入例子:**  

	5 2  

**输出例子:**  

	66

----------
6、双核处理（[网易2017春招](https://www.nowcoder.com/test/4575457/summary)）  
时间限制：1秒  
空间限制：32768K  
一种双核CPU的两个核能够同时的处理任务，现在有n个已知数据量的任务需要交给CPU处理，假设已知CPU的每个核1秒可以处理1kb，每个核同时只能处理一项任务。n个任务可以按照任意顺序放入CPU进行处理，现在需要设计一个方案让CPU处理完这批任务所需的时间最少，求这个最小的时间。   
**输入描述:**输入包括两行： 第一行为整数n(1 ≤ n ≤ 50) 第二行为n个整数length[i](1024 ≤ length[i] ≤ 4194304)，表示每个任务的长度为length[i]kb，每个数均为1024的倍数。  
**输出描述:**输出一个整数，表示最少需要处理的时间  
**输入例子:** 

	5 
	 
	3072 3072 7168 3072 1024   

输出例子:  

	9216

----------
7、赶去公司（[网易2017春招](https://www.nowcoder.com/test/4575457/summary)）  
时间限制：1秒  
空间限制：32768K  
终于到周末啦！小易走在市区的街道上准备找朋友聚会，突然服务器发来警报,小易需要立即回公司修复这个紧急bug。假设市区是一个无限大的区域，每条街道假设坐标是(X，Y)，小易当前在(0，0)街道，办公室在(gx,gy)街道上。小易周围有多个出租车打车点，小易赶去办公室有两种选择，一种就是走路去公司，另外一种就是走到一个出租车打车点，然后从打车点的位置坐出租车去公司。每次移动到相邻的街道(横向或者纵向)走路将会花费walkTime时间，打车将花费taxiTime时间。小易需要尽快赶到公司去，现在小易想知道他最快需要花费多少时间去公司。  
**输入描述:**输入数据包括五行:
第一行为周围出租车打车点的个数n(1 ≤ n ≤ 50)
第二行为每个出租车打车点的横坐标tX[i] (-10000 ≤ tX[i] ≤ 10000)
第三行为每个出租车打车点的纵坐标tY[i] (-10000 ≤ tY[i] ≤ 10000)
第四行为办公室坐标gx,gy(-10000 ≤ gx,gy ≤ 10000),以空格分隔
第五行为走路时间walkTime(1 ≤ walkTime ≤ 1000)和taxiTime(1 ≤ taxiTime ≤ 1000),以空格分隔  
**输出描述:**输出一个整数表示，小易最快能赶到办公室的时间  
**输入例子:** 
 
     2   
     -2 -2  
	 0 -2   
	 -4 -2  
	15 3  

**输出例子: ** 

	42

----------
8、调整队形（[网易2017春招](https://www.nowcoder.com/test/4575457/summary)）  
时间限制：1秒  
空间限制：32768K  
在幼儿园有n个小朋友排列为一个队伍，从左到右一个挨着一个编号为(0~n-1)。其中有一些是男生，有一些是女生，男生用'B'表示，女生用'G'表示。小朋友们都很顽皮，当一个男生挨着的是女生的时候就会发生矛盾。作为幼儿园的老师，你需要让男生挨着女生或者女生挨着男生的情况最少。你只能在原队形上进行调整，每次调整只能让相邻的两个小朋友交换位置，现在需要尽快完成队伍调整，你需要计算出最少需要调整多少次可以让上述情况最少。例如：
GGBBG -> GGBGB -> GGGBB 
这样就使之前的两处男女相邻变为一处相邻，需要调整队形2次   
**输入描述:**输入数据包括一个长度为n且只包含G和B的字符串.n不超过50.  
**输出描述:**输出一个整数，表示最少需要的调整队伍的次数  
**输入例子:** 
 
	GGBBG   
**输出例子:** 

	2

----------
9、消除重复元素（[网易2017春招](https://www.nowcoder.com/test/4575457/summary)）  
时间限制：1秒  
空间限制：32768K  
小易有一个长度为n序列，小易想移除掉里面的重复元素，但是小易想是对于每种元素保留最后出现的那个。小易遇到了困难,希望你来帮助他。  
**输入描述:**输入包括两行： 第一行为序列长度n(1 ≤ n ≤ 50) 第二行为n个数sequence[i](1 ≤ sequence[i] ≤ 1000)，以空格分隔  
**输出描述:**输出消除重复元素之后的序列，以空格分隔，行末无空格  
**输入例子:**  

	9   

	100 100 100 99 99 99 100 100 100  
 
**输出例子:** 

	99 100

----------
10、魔力手环（[网易2017春招](https://www.nowcoder.com/test/4575457/summary)） 
时间限制：1秒  
空间限制：32768K  
小易拥有一个拥有魔力的手环上面有n个数字(构成一个环),当这个魔力手环每次使用魔力的时候就会发生一种奇特的变化：每个数字会变成自己跟后面一个数字的和(最后一个数字的后面一个数字是第一个),一旦某个位置的数字大于等于100就马上对100取模(比如某个位置变为103,就会自动变为3).现在给出这个魔力手环的构成，请你计算出使用k次魔力之后魔力手环的状态。   
**输入描述:**输入数据包括两行： 第一行为两个整数n(2 ≤ n ≤ 50)和k(1 ≤ k ≤ 2000000000),以空格分隔 第二行为魔力手环初始的n个数，以空格分隔。范围都在0至99.  
**输出描述:**输出魔力手环使用k次之后的状态，以空格分隔，行末无空格。  
**输入例子:**  

	3 2   
	
	1 2 3   

**输出例子:**  

	8 9 7