# Mini-Pomodoro
A mini Pomodoro timer for WIN7/WIN10.
一款专为 WIN7/WIN10 设计的迷你番茄计时器。

时光飞逝，一转眼坚持使用番茄工作法已经快3年了！能坚持这么长时间，主要还是得益于它的简单。但是令人纠结的是，这么长时间以来，换了7款不同的番茄计时器，仍然没有找到非常满意的：
　　■ 机械的噪音太大，会妨碍身边的同事，只能家里用。但是家里又太安静了，一旦响铃就跟晴天霹雳似的，把自己吓一跳。
　　■ 手机上的计时器 app 种类繁多，有偏重视觉效果的，有偏重任务管理的，有主打简单易用的,但是它们都有一个共同的缺点：不能保持屏幕常亮（太费电），时常会把它给忘了。另外怕影响同事一般都会把铃声关掉，只靠震动的话又常常感觉不到。
　　■ 电脑上的计时器都好丑。最小化到托盘上看不到，完全没有存在感；放到任务栏上不小心点到又会分散注意力，感觉碍手碍脚的。
　　■ app 和 pc 软件另外一个缺点是不能实时看到剩余时间和进度条，没有时间流逝的感觉。当计时结束时又会突然弹出对话框吓人一跳。

　　其实我想要的就是这么个东西：
  
   ![](http://images.cnitblog.com/blog/25284/201410/152200445292458.png)

　　■ 当你想看到它时，它就在那里，不需要额外的操作；当你想忽略它时，也不需要额外的操作。
　　■ 没有窗体，不会突然出现在工作区上面耽误事儿，还得去点那个小小的最小化按钮。
　　■ 即使不小心误点到计时器图标上面也不会发生什么，不用担心它会给你增加麻烦。
　　■ 实时显示剩余时间和进度条。
　　■ 计时结束时不会突然弹出一个对话框吓人一跳，也不会发出声音影响他人。它会自动切换到5分钟休息模式，并持续闪烁黄色进度条，比较温和，并且也能确保被注意到。
　　■ 休息结束时会弹出对话框，用户确认后再开始新的番茄时间。
  
   ![](http://images.cnitblog.com/blog/25284/201410/152214019517507.png)

　　在网上遍寻未果后，我决定自己实现它。其实实现这么个简单的东东就是分分钟的事儿~（我不会告诉你搞图标花了我5个小时 T T）
　　那么要想中途重新开始新的番茄时间怎么办呢？关闭程序再重新运行它↖(^ω^)↗ 建议将程序锁定到任务栏并拖拽到任务栏最左侧，这样想要关闭或启动它就比较方便了。
