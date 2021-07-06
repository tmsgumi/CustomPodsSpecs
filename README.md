# Custom Cocoa Pods Repo

## Reason of existance :
Fix broken URL, blocking pod installs during compilation.
Like https://dl.bintray.com/ironsource-mobile/ios-adapters/ISAdColonyAdapter4.3.8.zip,
Is fixed by using https://github.com/ironsource-mobile/ios-adapters/ISAdColonyAdapter4.3.8.zip



## How-to :

- Clone this repository, set up the pod repo 
  ```pod repo add REPO_NAME https://github.com/tmsgumi/CustomPodsSpecs.git```
- Find inside github.com/CocoaPods/Specs the spec you are trying to fix
- Duplicate it in this repo, add the Suffix "Temp" to the
  - Spec Filename
  - Folder
  - Name (inside the file)



```
pod repo lint .
```

```
pod repo push REPO_NAME PATH_TO_YOUR.podspec.json
```

## About private Pods 
https://guides.cocoapods.org/making/private-cocoapods.html

----------

# Original Specs files :

## [IronsourceSDK](https://github.com/CocoaPods/Specs/blob/master/Specs/7/7/b/IronSourceSDK/)

### [7.1.0.0](https://github.com/CocoaPods/Specs/blob/master/Specs/7/7/b/IronSourceSDK/7.1.0.0/IronSourceSDK.podspec.json)


## [IronSourceAdMobAdapter](https://github.com/CocoaPods/Specs/blob/master/Specs/c/1/5/IronSourceAdMobAdapter/)
### [4.3.18.1](https://github.com/CocoaPods/Specs/blob/master/Specs/c/1/5/IronSourceAdMobAdapter/4.3.18.1/IronSourceAdMobAdapter.podspec.json)


## [IronSourceUnityAdsAdapter](https://github.com/CocoaPods/Specs/blob/master/Specs/a/e/4/IronSourceUnityAdsAdapter/)
### [4.3.7.1](https://github.com/CocoaPods/Specs/blob/master/Specs/a/e/4/IronSourceUnityAdsAdapter/4.3.7.1/IronSourceUnityAdsAdapter.podspec.json)


## [IronSourceVungleAdapter](https://github.com/CocoaPods/Specs/blob/master/Specs/f/6/9/IronSourceVungleAdapter/)

### [4.3.9.0](https://github.com/CocoaPods/Specs/blob/master/Specs/f/6/9/IronSourceVungleAdapter/4.3.9.0/IronSourceVungleAdapter.podspec.json)


## [IronSourceFacebookAdapter](https://github.com/CocoaPods/Specs/blob/master/Specs/a/d/c/IronSourceFacebookAdapter/)

### [4.3.22.1](https://github.com/CocoaPods/Specs/blob/master/Specs/a/d/c/IronSourceFacebookAdapter/4.3.22.1/IronSourceFacebookAdapter.podspec.json)


## [IronSourceAdColonyAdapter](https://github.com/CocoaPods/Specs/tree/master/Specs/e/f/7/IronSourceAdColonyAdapter)

### [4.3.8.0](https://github.com/CocoaPods/Specs/blob/master/Specs/e/f/7/IronSourceAdColonyAdapter/4.3.8.0/IronSourceAdColonyAdapter.podspec.json)


