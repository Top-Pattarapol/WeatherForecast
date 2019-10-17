# [Timeline](https://github.com/Top-Pattarapol/timeline)

## Requirements
 - iOS 13.0+
 - Xcode 11.0+
 - Swift 5+
 
## Dependency
 - [Alamofire](https://github.com/Alamofire/Alamofire) -  for call serveice
 - [Kingfisher](https://github.com/onevcat/Kingfisher) - for downloading and caching images
 - [OHHTTPStubs](https://github.com/AliSoftware/OHHTTPStubs) - for stub network requests fot unit test

## Installation

#### OHHTTPStubs
```sh
carthage update OHHTTPStubs --platform iOS
```

## Manually

We use Swift Package Manager and Carthage for dependency manage. If you don't have a Carthage yet, see the installation instructions below.

### Swift Package Manager

The [Swift Package Manager](https://swift.org/package-manager/) is a tool for automating the distribution of Swift code and is integrated into the `swift` compiler. It is in early development.

### Carthage

[Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks.

#### Installing Carthage
There are multiple options for installing Carthage:
* **Installer:** Download and run the `Carthage.pkg` file for the latest [release](https://github.com/Carthage/Carthage/releases), then follow the on-screen instructions. If you are installing the pkg via CLI, you might need to run `sudo chown -R $(whoami) /usr/local` first.

* **Homebrew:** You can use [Homebrew](http://brew.sh) and install the `carthage` tool on your system simply by running `brew update` and `brew install carthage`. (note: if you previously installed the binary version of Carthage, you should delete `/Library/Frameworks/CarthageKit.framework`).

* **MacPorts:** You can use [MacPorts](https://www.macports.org/) and install the `carthage` tool on your system simply by running `sudo port selfupdate` and `sudo port install carthage`. (note: if you previously installed the binary version of Carthage, you should delete `/Library/Frameworks/CarthageKit.framework`).

* **From source:** If you’d like to run the latest development version (which may be highly unstable or incompatible), simply clone the `master` branch of the repository, then run `make install`. Requires Xcode 9.4 (Swift 4.1).


# WeatherForecast
