# IKIRxSwiftPlayground-v3

This project consists of a minimal workspace with a playground for testing macOS/iOS code with [RxSwift](https://github.com/ReactiveX/RxSwift).
Of course, you can also add other frameworks easily through Carthage.
Tested with Xcode 9.4.1, Swift 4.1.2 and RxSwift 4.2.0.

It has

* No code signing
* No property list
* There's not even an app here

It's just a _workspace_ that uses RxSwift installed by Carthage.

Install RxSwift using

    $ carthage build

Open `IKIRxSwiftPlayground-v3.xcworkspace`.

When changing schemes/platforms, do a **Product > Clean Builder Folder…** by holding down your option key.

Play, learn, test. Happy prototyping!

---

## Autocompletion

Sometimes auto completion does not work and this can be frustrating because it is not clear what causes the problem. Below, I've recorded what seems to have _no effect_ on autocompletion.

* Whether the platform is iOS or macOS
* Performing a successful build
