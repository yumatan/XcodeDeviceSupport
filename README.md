# XcodeDeviceSupport
Xcode DeviceSupport files (iPhoneOS / AppleTVOS / WatchOS)

* iPhoneOS
  * iOS 8.0 ~ 16.4

* AppleTVOS
  * tvOS 9.0 ~ 16.4

* WatchOS
  * watchOS 2.0 ~ 9.4

## Topic

* [Missing iOS 17 device support files @Apple Developer Forum](https://developer.apple.com/forums/thread/730947)
  * > "Please use Xcode 15 beta to work with iOS 17 beta."
  * If you would like to use Xcode 14 to work with iOS 17 beta,
    1. `$ defaults write com.apple.dt.Xcode DVTEnableCoreDevice enabled`
    2. Restart Xcode 14