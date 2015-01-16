# twty

A command-line twitter client

## Install

1. Install golang environment.

 see: http://golang.org/doc/install.html
 for japanese: http://golang.jp/install
 for windows user: http://code.google.com/p/gomingw/downloads/list

2. get twty

    $ go get github.com/mattn/twty

Thanks all!

## Usage

    $ twty -h

At the first, you can see the opening web-browser.  And you'll see pin-code is
shown on twitter.com.  Please copy it and type in console like following.

    PIN: XXXXXX

Configuration file is stored in: ~/.config/twty/settings.json
For windows user: %USERPROFILE%/Application Data/twty/settings.json

## FAQ

Do you use proxy? then set environment variable `HTTP_PROXY` like below.

    HTTP_PROXY=http://myproxy.example.com:8080

## License

under the MIT License: http://mattn.mit-license.org/2015

## Author

Yasuhiro Matsumoto <mattn.jp@gmail.com>

Have Fan!
