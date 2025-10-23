SwiftSoup is a pure Swift library designed for seamless HTML parsing and manipulation across multiple platforms, including macOS, iOS and Linux. It offers an intuitive API that leverages the best aspects of DOM traversal, CSS selectors, and jQuery-like methods for effortless data extraction and transformation. Built to conform to the **WHATWG HTML5 specification**, SwiftSoup ensures that parsed HTML is structured just like modern browsers do.

### Key Features:
- **Parse and scrape** HTML from a URL, file, or string.
- **Find and extract** data using DOM traversal or CSS selectors.
- **Modify HTML** elements, attributes, and text dynamically.
- **Sanitize user-submitted content** using a safe whitelist to prevent XSS attacks.
- **Generate clean and well-structured HTML** output.

SwiftSoup is designed to handle all types of HTML—whether perfectly structured or messy tag soup—ensuring a logical and reliable parse tree in every scenario.

---

## Swift
Swift 5 ```>=2.0.0```

Swift 4.2 ```1.7.4```

## Installation

### Cocoapods
SwiftSoup is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'SwiftSoup'
```

```ruby
github "scinfu/SwiftSoup"
```
### Swift Package Manager
SwiftSoup is also available through [Swift Package Manager](https://github.com/apple/swift-package-manager).
To install it, simply add the dependency to your Package.Swift file:

```swift
...
dependencies: [
    .package(url: "https://github.com/scinfu/SwiftSoup.git", from: "2.6.0"),
],
targets: [
    .target( name: "YourTarget", dependencies: ["SwiftSoup"]),
]
...
```
---

