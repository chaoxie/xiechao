# DrawerViewController

[![CI Status](http://img.shields.io/travis/蔡成汉/DrawerViewController.svg?style=flat)](https://travis-ci.org/蔡成汉/DrawerViewController)
[![Version](https://img.shields.io/cocoapods/v/DrawerViewController.svg?style=flat)](http://cocoapods.org/pods/DrawerViewController)
[![License](https://img.shields.io/cocoapods/l/DrawerViewController.svg?style=flat)](http://cocoapods.org/pods/DrawerViewController)
[![Platform](https://img.shields.io/cocoapods/p/DrawerViewController.svg?style=flat)](http://cocoapods.org/pods/DrawerViewController)

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

DrawerViewController is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'DrawerViewController', '~>0.0.1'
```

## Author

蔡成汉, 1178752402@qq.com

## License

DrawerViewController is available under the MIT license. See the LICENSE file for more info.

## 抽屉使用

抽屉用法非常简单，可参考Example。主要用法代码在AppDelegate里，需要注意的是侧边栏控制器需要继承SideViewController，否则无法通过侧边栏来进行页面push。其他控制器则不需要此继承。
侧边栏控制器在进行页面push的时候，需要通过方法 侧边控制器.drawerViewController exchangeContentViewController:目标控制器 来进行侧边到目标控制器的切换，否则无法进行页面push。

# xiechao
