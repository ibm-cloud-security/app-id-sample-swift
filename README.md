<img src="https://bluemixassets.eu-gb.mybluemix.net/api/Products/image/logos/authentication.svg?key=[starter-authentication]&event=readme-image-view" alt="Authentication Logo" width="200px"/>

## AppId
AppId sample in Swift

[![](https://img.shields.io/badge/ibm%20cloud-powered-blue.svg)](https://www.ibm.com/cloud/)
[![Platform](https://img.shields.io/badge/platform-ios_swift-lightgrey.svg?style=flat)](https://developer.apple.com/swift/)

### Table of Contents
* [Summary](#summary)
* [Requirements](#requirements)
* [Configuration](#configuration)
* [Run](#run)
* [License](#license)

### Summary

Appid sample is a sample that uses default values to login to application on the IBM Cloud Mobile services.

### Requirements

* iOS 10.0 or higher
* Xcode 9.0 or above
* Swift 4.0

### Configuration
* [IBM Cloud Mobile services Dependency Management](#bluemix-mobile-services-dependency-management)

#### IBM Cloud Mobile services Dependency Management

This starter uses the IBM Cloud Mobile services SDKs to use the functionality of the Mobile Analytics and Push Notifications services.

The IBM Cloud Mobile services SDK uses [CocoaPods](https://cocoapods.org/) to manage and configure dependencies. To use our latest SDKs, you need version 1.1.0.rc.2.

You can install CocoaPods using the following command:

```bash
$ sudo gem install cocoapods --pre
```

If the CocoaPods repository is not configured, run the following command:

```bash
$ pod setup
```

For this starter, a pre-configured `Podfile` is included in the **ios_swift/Podfile** location. To download and install the required dependencies, run the following command in the **ios_swift** directory:

```bash
$ pod install
```
Open the Xcode workspace: `{APP_Name}.xcworkspace`. Continue to open the `.xcworkspace` file as it contains all the dependencies and configurations.

If you run into any issues during the pod install, it is recommended to run a pod update by using the following commands:

```bash
$ pod update
$ pod install
```

> [View configuration](#configuration)

### Run

Click **Product > Run** to start the app in Xcode.

<img src="README_Images/basic.png" alt="Basic App Screenshot" width="250px"/>

The application has built in integration points for the Mobile Analytics and Push Notifications services.

### License
This package contains code licensed under the Apache License, Version 2.0 (the "License"). You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0 and may also view the License in the LICENSE file within this package.
