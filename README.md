# KWGradientView

![Screen Cast](ScreenShots/screencast.gif)

[![Build Status](https://www.bitrise.io/app/d54da2ec7c9a0496.svg?token=kBv75DKdduTDchGW4zK06g&branch=master)](https://www.bitrise.io/app/d54da2ec7c9a0496)
[![Version](https://img.shields.io/cocoapods/v/KWGradientView.svg?style=flat)](http://cocoapods.org/pods/KWGradientView)
[![License](https://img.shields.io/cocoapods/l/KWGradientView.svg?style=flat)](http://cocoapods.org/pods/KWGradientView)
[![Platform](https://img.shields.io/cocoapods/p/KWGradientView.svg?style=flat)](http://cocoapods.org/pods/KWGradientView)

## Features

- [x] Horizontal, vertical & diagonal gradients
- [x] Animate gradients by changing colors 

## Requirements

- iOS 8.0 or later
- Swift 3.0

## Installation

KWGradientView is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "KWGradientView"
```

## How to use

#### Add the class KWGradientView to View on storyboard

![Adding KWGradientView](ScreenShots/addingKWGradientView.png)

#### Modifying color and gradient style using storyboard

![Modify in storyboard](ScreenShots/modifyByStoryboard.png)

#### Or Modify Programmatically: Example with Horizontal Gradient

```swift
@IBOutlet weak var gradientView: KWGradientView!

gradientView.addGradientLayerAlongXAxis(colors: [UIColor.red, UIColor.green, UIColor.blue])
```

Also we can add any number of colors by adding them to the array of colors.

All the methods in the pod are implemented in [`GradientsViewController.swift`](https://github.com/keepworks/KWGradientView/blob/master/KWGradientView/GradientsViewController.swift) for your reference.

## Author

KeepWorks, ios@keepworks.com

## Credits

KWGradientView is owned and maintained by [KeepWorks](http://www.keepworks.com/).

[![N|Solid](http://www.keepworks.com/assets/logo-800bbf55fabb3427537cf669dc8cd018.png)](http://www.keepworks.com/)

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/keepworks/KWGradientView.

## License

KWGradientView is available under the [MIT License](http://opensource.org/licenses/MIT). See the [License](https://github.com/keepworks/KWGradientView/blob/master/LICENSE) file for more info.
