# appicon

[![](https://img.shields.io/badge/platform-macOS-brightgreen.svg?style=flat-square)](https://www.apple.com/macos/) [![](https://img.shields.io/github/downloads/joeblau/appicon/total.svg?style=flat-square)](https://github.com/joeblau/appicon/releases) [![](https://img.shields.io/github/license/joeblau/appicon.svg?style=flat-square)](https://github.com/joeblau/appicon/blob/master/LICENSE)


`appicon` creates app icons for iOS, iPadOS, macOS, and watchOS

## Install

```bash
brew tap joeblau/hb
brew install appicon
```

## Run

Navigate to an image that is at least 1024x1024

Generate icons for iOS
```bash
appicon -f image.png
```

### Advanced

Generate icons for iOS, iPadOS, macOS and watchOS

```bash
appicon -f image.png -p ios ipados macos watchos
```
