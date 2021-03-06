# libwebsock

C library for easy WebSockets servers.

This library allows a developer to quickly develop WebSocket servers by focusing
on the actual logic of your WebSocket implementation instead of the details
of the WebSocket protocol or even specifics of C sockets.

Installation instructions can be found [here][6].

API reference & usage instructions can be found [here][7].

To get started, have a look at [echo.c][1] in the examples directory of the package.  A
simple echo server is implemented.

Current Travis CI Build Status:

[![Build Status][3]][5]

## Features

* Callbacks for events
* SSL Support
* Easy to use
* Uses [libevent][2] for portability (tested on Linux/FreeBSD)
* IPv6 support
* No failures on Autobahn Test suite

 [1]: https://github.com/nilsenmiotto/libwebsock/blob/master/examples/echo.c
 [2]: http://libevent.org
 [3]: https://travis-ci.org/nilsenmiotto/libwebsock.svg?branch=master
 [4]: https://travis-ci.org/nilsenmiotto/libwebsock.png
 [5]: https://travis-ci.org/nilsenmiotto/libwebsock
 [6]: https://github.com/nilsenmiotto/libwebsock/wiki/Installation
 [7]: https://github.com/nilsenmiotto/libwebsock/wiki/API
