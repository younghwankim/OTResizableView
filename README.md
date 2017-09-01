# OTResizableView

## Description
OTResizableView is a UIView library that can be resized with fingers.

## Features
Resize and move your UIView.
Change OTResizableView's grip point and outline color.

## Demo
![OTResizableVIewDemo.gif](https://qiita-image-store.s3.amazonaws.com/0/152335/4247576c-8532-e632-c335-6445634904b7.gif "OTResizableVIewDemo.gif")
 
## Usage

```swift:Swift

import OTResizableView

let resizableView = OTResizableView.init(contentView: yourView)
resizableView.delegate = self;
        
// If you want to change resizableView colors, you can customize here.

self.view.addSubview(resizableView)


```

## Install

**CocoaPods**  
Add this to your Podfile.

```PodFile
pod 'OTResizableView'
```

**Carthage**  
Add this to your Cartfile.

```Cartfile
github "PKPK-Carnage/OTResizableView"
```

## Licence

[MIT](https://github.com/PKPK-Carnage/OTGanttChartKit/blob/master/LICENSE)

## Author

[PKPK-Carnage](https://github.com/PKPK-Carnage)
