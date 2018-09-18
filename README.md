OpenSSL for iOS
=================
Build openssl for iOS development  
This script will generate static library for armv7, arm64, i386, and x86_64.  
New Xcode7 bitcode feature supported.


Usage
=================
Copy the following lines to your Terminal.app
```
curl -O http://www.openssl.org/source/openssl-1.1.1.tar.gz
tar xf openssl-1.1.1.tar.gz
cd openssl-1.1.1
curl https://raw.githubusercontent.com/sinofool/build-openssl-ios/master/build_openssl_dist.sh |bash
```
Find the result folder openssl-ios-dist on your desktop.
