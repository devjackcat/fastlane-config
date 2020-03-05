fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## iOS
### ios test
```
fastlane ios test
```
打生产包并上传至AppStore
### ios adhocdebug
```
fastlane ios adhocdebug
```
打 adhoc debug 测试包
### ios adhoc
```
fastlane ios adhoc
```
打 adhoc 内侧包
### ios release
```
fastlane ios release
```
打生产包并上传至AppStore

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
