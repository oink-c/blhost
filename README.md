# blhost

#### Modified by Kristian Lauszus, 2018-2020
_________
[![Build Status](https://api.travis-ci.org/oink-c/blhost.svg?branch=master)](https://travis-ci.com/github/oink-c/blhost)


### Changes

* Can now compile the code using GCC on Mac
* Fixed setting the UART baudrate on Linux
* Ping 3 times with a delay of 1 s between the ping commands
* Allow to set a custom UART baudrate
* Fixed "get_string_property_utf8" on Mac thanks to Andrew Pines

The executables are automatically build using [Travis](https://travis-ci.org/) and [AppVeyor](https://www.appveyor.com/) for all major platforms including armv7l (Raspberry PI or similar). The executables can be found under the releases tab: <https://github.com/Lauszus/blhost/releases>.
