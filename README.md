
# PJSIP

PJSIP is a free and open source multimedia communication library written in C language implementing standard based protocols such as SIP, SDP, RTP, STUN, TURN, and ICE.

## Features

- Supported platforms: iOS7, iOS8
- Supported architectures: armv7, armv7s, arm64, i386, x86_64
- OpenSSL support provided by the [OpenSSL-for-iPhone](https://github.com/x2on/OpenSSL-for-iPhone) build script and the [OpenSSL-Universal](https://github.com/krzyzanowskim/OpenSSL) pod
- Video support provided by the [OpenH264](https://github.com/cisco/openh264)

## Installation

Add the following line to your `Podfile` and run `pod install` command.

```
pod 'pjsip', :git => 'https://github.com/mgkdev/pjsip.git'
```

## Example

See [example](example/ipjsystest) folder for integration example

## Build manually

1. Download and run [build.sh](build.sh) script.
2. Drag generated libraries and headers files into your xcode project.

## Build enviroment

NASM needed to be installed for OpenH264.

```
brew install nasm
```

Xcode needed to be installed on '/Applications/Xcode.app' for OpenH264.
Use multiple versions of Xcode with care.
