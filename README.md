## OrderPlaceUat

If you need to upload to itunnes connection, please integrate [OrderPlaceSdkPrd
](https://github.com/AigensTechnology/OrderPlaceSdkPrd)

## config params ref

https://docs.google.com/document/d/1YkTXzsdmWD7Q8BgLVWlekI6nyiS1wcU2Y6T2aHUKiJw/edit?usp=sharing

## Installation

OrderPlaceSdkUat is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

* This is core function, including (scan / gps / apple pay)

```ruby
platform :ios, '10.0'

target 'YourProjectName' do

  use_frameworks!

pod 'OrderPlaceSdkUat', '~> 0.2.0'

end

```

* If you want the alipay feature,pls

```rb
pod 'OrderPlaceSdkUat/Alipay', '~> 0.2.0'
```
## Requirements
* You must include the following key in info plist.
	- Info.plist must contain an NSCameraUsageDescription key with a string value explaining to the user how the app uses this data.
	- The app's Info.plist must contain an NSLocationWhenInUseUsageDescription key with a string value explaining to the user how the app uses this data
* set targets -> Build Setting -> search 'bitcode' -> Enable Bitcode: No

## Author

Aigens

## License

OrderPlaceSdkUat is available under the MIT license. See the LICENSE file for more info.

## update record

alipay , support WKWebview


