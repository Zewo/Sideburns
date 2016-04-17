Sideburns
=========

[![Swift 2.2](https://img.shields.io/badge/Swift-3.0-orange.svg?style=flat)](https://swift.org)
[![Platforms Linux](https://img.shields.io/badge/Platforms-Linux-lightgray.svg?style=flat)](https://swift.org)
[![License MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](https://tldrlegal.com/license/mit-license)
[![Slack Status](http://slack.zewo.io/badge.svg)](http://slack.zewo.io)

**Sideburns** is a mustache template responder for swift 2.2.

## Usage

```swift
let templateData: TemplateData = [
    "foo": "bar"
]

let response = Response(templatePath: "index.html", templateData: templateData)
```

## Installation

- Add `Sideburns` to your `Package.swift`

```swift
import PackageDescription

let package = Package(
	dependencies: [
		.Package(url: "https://github.com/Zewo/Sideburns.git", majorVersion: 0, minor: 1)
	]
)
```

## Community

[![Slack](http://s13.postimg.org/ybwy92ktf/Slack.png)](http://slack.zewo.io)

Join us on [Slack](http://slack.zewo.io).

License
-------

**Sideburns** is released under the MIT license. See LICENSE for details.
