# 张妈计算器说明
> [点击进入张妈计算器](https://evenwrong.github.io/SGS/张妈计算器.html)
> + 点击按钮或键盘来输入点数，计算器会自动计算
> + 也可以按A、0、J、Q、K来输入1、10、J（10）、Q（12）、K（13）

## 更新日志
> ### 21.09.09
> + 若超过一分钟没有按键，下次按键时会自动清除之前的所有数字，以避免上次计算后忘记清除的情况

> ### 21.07.28
> + 修正了小键盘数字错位的问题

> ### 21.07.14
> + 创建了README
> + 更新了算法，修复了诸如6、9、6、J无法计算的问题。
>   + 原本将数字分入0、1、2共3堆中，匹配0、1这两堆，现在修改为匹配0、2这两堆，暴力枚举次数改为n^3/2-1，不会再有漏解的情况发生了。
> + 现在双击Backspace（退格键）或者Enter（回车）可以直接清除所有点数

> ### 21.07.08
> + 现在小键盘上的数字也可以来输入点数了
> + 现在修改为计算出10个结果后停止计算，数量大于10的时候不再由自动切换为手动

> ### 21.07.05
> + 加了个是否自动计算的按钮，数量大于10的时候自动切换为手动
> + 现在可以使用键盘来输入点数了
