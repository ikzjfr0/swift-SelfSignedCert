SelfSignedCert
==============

This project provides a Swift framework that allows you to create self-signed certificates on iOS, using Swift. Unfortunately, Apple does not provide this functionality in their security frameworks. Another way of doing it is using OpenSSL, but (especially when using Swift) that is downright horrible.

The code in this library is a (partial) port of [MYCrypto](https://github.com/snej/MYCrypto). That project contains unmaintained Objective-C code, which was difficult to use as a CocoaPod and especially also when using Swift. So I took that part that I needed and implemented that in Swift.

Please note that I'm not a security expert. This framework has not been reviewed by a security expert. Until it has, please use with caution! And in any case (reviewed or not), using it is always at your own risk of course.

If you are a security expert and you want to review this framework, please contact me.
