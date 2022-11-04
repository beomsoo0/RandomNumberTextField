# RandomNumberTextField

[![CI Status](https://img.shields.io/travis/beomsoo0/RandomNumberTextField.svg?style=flat)](https://travis-ci.org/beomsoo0/RandomNumberTextField)
[![Version](https://img.shields.io/cocoapods/v/RandomNumberTextField.svg?style=flat)](https://cocoapods.org/pods/RandomNumberTextField)
[![License](https://img.shields.io/cocoapods/l/RandomNumberTextField.svg?style=flat)](https://cocoapods.org/pods/RandomNumberTextField)
[![Platform](https://img.shields.io/cocoapods/p/RandomNumberTextField.svg?style=flat)](https://cocoapods.org/pods/RandomNumberTextField)


## 📸 Preview
<img src="https://user-images.githubusercontent.com/73675540/199937967-98e03144-1511-47d6-8487-8316629cf39d.gif" width="40%" height="40%/"><br>

## 🏗 Installation
* [CocoaPods](https://guides.cocoapods.org/using/using-cocoapods.html):
```ruby
pod 'RandomNumberTextField'
```

## 🐒 Usage
* Storyboard  
just subclassing!
<br><img src="https://user-images.githubusercontent.com/73675540/198974933-b1c849b3-d37f-4743-9693-c901ca32ff61.png" width="60%" height="60%/"><br>

* Code-Base  
just init!
``` swift
let randomKeyboard = RandomNumberTextField()
```

## 🎨 Custom
you can change keyboard color and font
``` swift
func setKeyboardBackgroundColor(_ color: UIColor?)
func setKeyboardFont(_ font: UIFont) 
func setKeyboardTitleColor(_ color: UIColor?, for state: UIControl.State) 
```

## Author

beomsoo0, 73675540+beomsoo0@users.noreply.github.com

## License

RandomNumberTextField is available under the MIT license. See the LICENSE file for more info.
