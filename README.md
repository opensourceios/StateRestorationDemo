# StateRestorationDemo

#### Swift app to demonstrate state preservation and restoration APIs.

![](https://raw.githubusercontent.com/shagedorn/StateRestorationDemo/master/Presentation/app_screenshot.png)

Created for a presentation at CocoaHeads Dresden on 09 July 2014. The Deckset presentation (rendered as PDF and the Markdown source) is included in the repository. Feel free to contact me for questions: [@hagidd](http://twitter.com/hagidd).

Verified with Xcode 7.3 and iOS 9.3. I regularily build & test the app with the latest Xcode betas, as well as Swift development snapshots.

The `swift_3_0` branch will be kept up to date to build with the latest [Swift 3.0 development snapshots](https://swift.org/download/).

## Tags 

Tags outline the various steps to enable state restoration in iOS apps:

+ `NO_STATE_RESTORATION`: The app without state restoration
+ `STATE_RESTORATION_OPT_IN`: The app generally enables state restoration, but does not implement it yet
+ `RESTORATION_IDENTIFIERS`: The app sets restoration identifiers on view controllers, but the controllers are not restored successfully yet
+ `BASIC_STATE_RESTORATION`: Initially created view controllers are restored successfully
+ `RESTORATION_CLASS`: Non-initial view controllers are restored, too
+ `STATE_ENCODING`: View controllers restore their views' state
+ `SIZE_CLASSES`: The window's size classes are preserved

**Note:** Both to improve the project and to support the current version of Swift, there have been major updates that are not reflected by the tagged commits. The tags are still helpful to follow the various steps, but you should use the latest commit on `master` for a working version.
