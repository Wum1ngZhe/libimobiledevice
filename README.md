# libimobiledevice

## About

A library to communicate with services of Apple iOS devices using native
protocols.

## Requirements

Development Packages of:
* OpenSSL or GnuTLS
* libplist
* libusbmuxd

Software:
* usbmuxd (OSS or Apple's version)
* make
* autoheader
* automake
* autoconf
* libtool
* pkg-config
* gcc or clang

Optional:
* cython (Python bindings)
* doxygen (Documentation)

## Installation

To compile run:
```bash
./autogen.sh
make
sudo make install
```

If you require a custom prefix or other option being passed to `./configure`
you can pass them directly to `./autogen.sh` like this:
```bash
./autogen.sh --prefix=/opt/local --enable-debug-code
make
sudo make install
```

By default, OpenSSL will be used. If you prefer GnuTLS, configure with
`--disable-openssl` like this:
```bash
./autogen.sh --disable-openssl
```

## Who/What/Where?

* Home: https://www.libimobiledevice.org/
* Code: `git clone https://git.libimobiledevice.org/libimobiledevice.git`
* Code (Mirror): `git clone https://github.com/libimobiledevice/libimobiledevice.git`
* Tickets: https://github.com/libimobiledevice/libimobiledevice/issues
* Mailing List: https://lists.libimobiledevice.org/mailman/listinfo/libimobiledevice-devel
* IRC: irc://irc.freenode.net#libimobiledevice
* Twitter: https://twitter.com/libimobiledev

## Credits

Apple, iPhone, iPod, and iPod Touch are trademarks of Apple Inc.
libimobiledevice is an independent software library and has not been
authorized, sponsored, or otherwise approved by Apple Inc.

README Updated on: 2019-06-21
