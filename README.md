[![CocoaPods](https://img.shields.io/badge/platforms-iOS-orange.svg?maxAge=2592000)](https://cocoapods.org/pods/TTPaymentsOTP)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)

# 3DS-iOS

## Installation

Touchtech 3DS for iOS supports iOS 9 and above.

### CocoaPods
Add the Touchtech 3DS-iOS pod into your Podfile and run `pod install`.
```ruby
    target :YourTargetName do
      pod 'TTPaymentsOTP'
    end
```

### Carthage
1. Add `github "Touch-Tech-Payments/3DS-iOS"` to your Cartfile.
2. Run carthage update.
3. Go to your Xcode project's "General" settings. Drag `TTPaymentsOTP.framework` from `Carthage/Build/iOS` to the "Embedded Binaries" section. Make sure “Copy items if needed” is selected and click Finish.