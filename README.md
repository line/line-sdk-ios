# LINE SDK for iOS

You can reach a vast number of LINE users by using the LINE SDK for iOS to integrate your app with LINE.

## Available Features

These LINE features can be integrated into your iOS App

### User Authentication

The LINE SDK for iOS lets you authenticate users with LINE. The LINE SDK automatically launches LINE to authenticate and authorize users.

### Calling APIs

The LINE SDK for iOS includes methods for calling APIs. Using these methods, your iOS app can retrieve user profiles.

## Installing the SDK

### Manual Installation

To download and install the SDK from the Channel Console, please refer to the instructions in the link below:

https://developers.line.me/ios/development-with-sdk-v2#download

### Cocoapods Installation

To install the SDK using Cocoapods, add the following line to your Podfile:

```ruby
pod 'LineSDK', '~> 4.0.2'
```

If you are using Swift, make sure `use_frameworks!` has been specified in your Podfile.

After installing the LineSDK using Cocoapods, please follow our instructions for setting up the iOS SDK starting from the [Enable Keychain Sharing](https://developers.line.me/ios/development-with-sdk-v2#link_frameworks) section.
