# SPAlertController

## 介绍
对[SPAlertController](https://github.com/SPStore/SPAlertController)库的封装

## 如何导入
```
pod 'SPAlertController', :git => 'https://github.com/xuzeyu/SPAlertController.git'
```

## 修改
```
4.0.1 1.设置按钮分割线可隐藏(setHeaderActionLineHidden:) 
       2.设置内容对齐方式messageAlignment和内容边距contentEdgeInsets
```
```
4.0.2 1.增加tapActionDismiss（action 单击后是否退出对话框,默认为YES）参数。
      2.增加addAction:，removeAction:,clearActions:方法，动态增删按钮
      3.action点击的回调（handler）修改在外部
```