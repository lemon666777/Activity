# Activity
Android组件Activity
本次实验主要通过重写Activity的七个方法（在MainActivity.java文件中）：onCreate()、onStart()、onResume()、onPause()、onStop()、onDestroy()、onRestart() 
理解Activity的生命周期
![](https://i.imgur.com/wZeDwGK.png)
Activity启动运行onCreate() onStart() onResume()
![](https://i.imgur.com/r7N5jD1.png)
点击Home键回到主界面onPause()–>onStop()依次被调用
![](https://i.imgur.com/VJRU4H4.png)
当我们再次回到Activity时–>onRestart() onStart() onResume()
![](https://i.imgur.com/DWR2dOu.png)
退出当前Activity时–>onPause()–>onStop()–>onDestroy()
