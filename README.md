# EmailComposer for Xcode 12

Compose and send emails in SwiftUI using a view modifier.

![EmailComposer code snippet](https://serialcoder.dev/misc/github_images/emailComposer.png)

## About EmailComposer

EmailComposer library makes it pretty easy to present the system provided controller for composing emails in SwiftUI based iOS applications. All it takes is to use a **view modifier**, providing a few arguments. The rest are handled automatically.

## Special Note

The EmailComposer Swift package in this repository makes use of the Swift tools version 5.4 *in order to be compatible with Xcode 12*. Original EmailComposer package implementation was done in Xcode 13 with Swift tools version 5.5, taking advantage of the new documentation features and Documentation Compiler (DocC).

If you are working in Xcode 12, then use the package of this repository. If you are working in Xcode 13 and above, then look at [this repository](https://github.com/gabrieltheodoropoulos/EmailComposer.git) in order to enjoy all those new documentation features.

## Integration

Copy this repository's URL, and in Xcode 12 go to *File > Swift Packages > Add Package Dependency...* menu. Follow the on-screen steps to finish adding the package. Do not forget to:

- Add EmailComposer library to the *Frameworks, Libraries, and Embedded Content* section in the General tab of your app's target.
- Import it in any source file you are going to use it:

```swift
import EmailComposer
```

## Documentation

[This short guide](https://github.com/gabrieltheodoropoulos/EmailComposer-Xcode12/wiki) demonstrates how to use EmailComposer library.

**Note:** There is a DocC archive (.doccarchive) available to download and open it with the Developer Documentation. However, this cannot be done in Xcode 12, as DocC archives require Xcode 13 and above. To find out more, look at the [original EmailComposer Swift package repository](https://github.com/gabrieltheodoropoulos/EmailComposer.git) made for Xcode 13+. 

## Author

Gabriel Theodoropoulos, Copyright © 2021 - Explore more content and material at [SerialCoder.dev](https://serialcoder.dev).

*Legal Note:
It is allowed to use EmailComposer library in both personal and commercial projects, as well as to modify it as neccesary. However, it is not allowed to sell it, or claim ownership.*

## License

EmailComposer is licensed under the MIT license.
