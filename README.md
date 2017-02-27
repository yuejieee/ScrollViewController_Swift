# ScrollViewController_Swift
##Description
类似一些新闻客户端的滚动视图，可实现顶部button和下方视图的联动切换
##Usage
首先创建一个新的类继承于此类
```
  // 设置顶部标题
  self.arrayTitle = ["全部", "待付款", "待取货", "已完成", "退款/售后"];
  // 添加子视图
  for _ in self.arrayTitle {
    let vc = UIViewController()
    self.addChildViewController(vc)
  }
```
