# check_show_status
对MySQL show status中的重点状态值进行查看
### check_show_status.sh
检查一些指标,打印说明
### qps.sh
```
----------|---------|--- MySQL Command Status --|----- Innodb row operation ----|-- Buffer Pool Read --
---Time---|---QPS---|select insert update delete|  read inserted updated deleted|   logical    physical
 22:21:48 |     1461|     0   1460      0      0|     0     1458       0       0|      8788           0
 22:21:49 |      406|     0    405      0      0|     0      407       0       0|      2429           0
 22:21:50 |     2010|     0   2009      0      0|     0     2007       0       0|     12132           0
 22:21:51 |     1806|     0   1805      0      0|     0     1807       0       0|     10908           0
 22:21:52 |     2457|     0   2456      0      0|     0     2456       0       0|     14849           0
 22:21:53 |     2498|     0   2497      0      0|     0     2495       0       0|     14754           0
 22:21:54 |      825|     0    824      0      0|     0      825       0       0|      4892           0
 22:21:55 |     2773|     0   2772      0      0|     0     2773       0       0|     16325           0
 22:21:56 |     2644|     0   2643      0      0|     0     2642       0       0|     15629           0
 22:21:57 |     2592|     0   2590      0      0|     0     2591       0       0|     15322           0
 22:21:58 |     2898|     0   2898      0      0|     0     2898       0       0|     17485           0
 22:21:59 |     3584|     0   3583      0      0|     0     3583       0       0|     21279           0
 22:22:00 |     2678|     0   2677      0      0|     0     2677       0       0|     15829           0
 22:22:01 |     2437|     0   2435      0      0|     0     2435       0       0|     14442           0
 22:22:02 |     2531|     0   2530      0      0|     0     2530       0       0|     15551           0
 22:22:03 |     2763|     0   2762      0      0|     0     2762       0       0|     16854           0
 22:22:04 |     2844|     0   2843      0      0|     0     2843       0       0|     17216           0
 22:22:05 |     2797|     0   2796      0      0|     0     2796       0       0|     16818           0
 22:22:06 |     2588|     0   2587      0      0|     0     2585       0       0|     15285           0
 22:22:07 |     2668|     0   2667      0      0|     0     2669       0       0|     15908           0
 ```
 
 ### qps2.sh
 ![image](https://github.com/Fanduzi/MySQL-Monitor-Toolkit/blob/master/image/Snip20170626_35.png)
