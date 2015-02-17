# IOToastInputSwift

[![CI Status](http://img.shields.io/travis/ibeneb/IOToastInputSwift.svg?style=flat)](https://travis-ci.org/ibeneb/IOToastInputSwift)
[![Version](https://img.shields.io/cocoapods/v/IOToastInputSwift.svg?style=flat)](http://cocoadocs.org/docsets/IOToastInputSwift)
[![License](https://img.shields.io/cocoapods/l/IOToastInputSwift.svg?style=flat)](http://cocoadocs.org/docsets/IOToastInputSwift)
[![Platform](https://img.shields.io/cocoapods/p/IOToastInputSwift.svg?style=flat)](http://cocoadocs.org/docsets/IOToastInputSwift)


<img src="https://github.com/ibeneb/IOToastInputSwift/blob/master/Preview/Screen%20Shot%201.png" width=320>

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Prerequisites

IOToastInputSwift advantages of recent Swift runtime advances. It requires:

- iOS 7 or later.

## Installation

IOToastInputSwift is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

    pod "IOToastInputSwift"

## Example of usage

````objc
[IOToastInputManager showNotificationWithMessage:@"You can insert your text" completionBlock:^ (NSInteger index, NSString *text) {

}];
````

## Author

Benjamin Prieur

## License

IOToastInputSwift is available under the MIT license. See the LICENSE file for more info.

