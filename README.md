[![Build Status](https://travis-ci.org/jozw/tutum-api.svg)](https://travis-ci.org/jozw/tutum-api)
[![Gem Version](https://badge.fury.io/rb/tutum-api.svg)](http://badge.fury.io/rb/tutum-api)


Ruby API for Tutum
======================

This library implements [Tutum's API](https://docs.tutum.co/v2/api/). It was spawned from the [ruby-tutum](https://github.com/255BITS/ruby-tutum) gem.

## Installation

```
$ gem install tutum-api
```
##Configuration

In order to make requests, you must secure your username and [API key](https://dashboard.tutum.co/account/).

```ruby
  require 'tutum'
  session = Tutum.new(username, api_key)
```
##Testing

Testing locally is simple. Just bundle and run the tests.

```
$ bundle
$ rake
```

##Contributing

If you find any issues or want to add functionality, feel free to fork or report.
