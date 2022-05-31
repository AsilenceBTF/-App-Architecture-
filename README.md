# 《App Architecture》
读书笔记
## MVC
![/resource/MVC.jpg](https://github.com/AsilenceBTF/-App-Architecture-/blob/master/resource/MVC.png)
- **storyboard** 与框架和类高度集成，这使得cocoa下的MVC十分轻量，开销十分小
- **cocoa** 并没有为观察者模式提供检查机制，如果view和model同步处理的不好，会出现异常
- viewController需要处理view层，还要负责controller层，最后还要与model层交互，我们很容易在不经意间把大多数
  职责赋予viewController，这也导致viewController变得臃肿，程序变得难以管理
