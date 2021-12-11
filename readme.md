#  Doghead OS Readme file
version:0.0.0.1
------------------------------
# 系统函数
## putchar与printchar的本质区别
1. printchar正如其名所言 其本质是print函数所编写
2. 而putchar函数 则是从底层开始编写 直接写显存 然后才写成print函数
3. 所以这是个先有鸡还是先有蛋的问题
4. 我更推荐使用printchar函数 因为它可以避免一些匪夷所思的bug
5. 如果使用 putchar函数 那么大概率在屏幕最下方写满后不可换行 而 printchar函数则解决了这一问题
## 内核内建函数表
1. print
2. printchar
3. putstr
4. putchar
5. gotoxy
6. set_color
7. get_this_color
8. sleep
9. sleep_m
10. input
11. getch

+ 注意 内核代码中的实现逻辑 如不是确定 请勿删除或改动
  -
+ 因为 很多时候 我们并不知道这串代码是否是一个bug 来预防bug(包括我自己) 

# 输出如何实现?
请看https://blog.csdn.net/lv1474/article/details/121736416?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522163922380916780265456371%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=163922380916780265456371&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~rank_v31_ecpm-5-121736416.pc_search_insert_es_download&utm_term=%5B30%E5%A4%A9%E8%87%AA%E5%88%B6%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%5D+--print&spm=1018.2226.3001.4187


