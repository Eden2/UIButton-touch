# UIButton-touch
button防暴力点击
1. UIButton+touch防止单个按钮连续点击 默认0.5s
2. UIButton+Delay  连续点击 只执行最后一次操作

程序中大量按钮没有做连续响应的校验，测试人员连续点击出现了很多不必要的问题，所以只能利用运行时特性，进行hook一下
