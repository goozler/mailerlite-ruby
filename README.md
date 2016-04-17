# MailerLite API Ruby wrapper

A Ruby gem which helps to communicate with [MailerLite][mailerlite] API.

[![Gem Version](http://img.shields.io/gem/v/mailerlite.svg?style=flat-square)][rubygems]
[![Build Status](http://img.shields.io/travis/jpalumickas/mailerlite-ruby.svg?style=flat-square)][travis]
[![Dependency Status](http://img.shields.io/gemnasium/jpalumickas/mailerlite-ruby.svg?style=flat-square)][gemnasium]
[![Coverage Status](http://img.shields.io/coveralls/jpalumickas/mailerlite-ruby/master.svg?style=flat-square)][coveralls]
[![Code Climate](http://img.shields.io/codeclimate/github/jpalumickas/mailerlite-ruby.svg?style=flat-square)][codeclimate]

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'mailerlite'
```

## Usage

### Authentication

```ruby
client = MailerLite::Client.new(api_key: 'my-secret-api-key')
```

Or create file under `config/initializers/mailerlite.rb`

```ruby
MailerLite.configure do |config|
  config.api_key = 'my-secret-api-key'
end
```

## Supported Ruby Versions

This library aims to support and is [tested against][travis] the following Ruby
implementations:

* Ruby 1.9.3
* Ruby 2.0.0
* Ruby 2.1.0
* Ruby 2.2.0
* Ruby 2.3.0

[rubygems]: https://rubygems.org/gems/mailerlite
[travis]: http://travis-ci.org/jpalumickas/mailerlite-ruby
[gemnasium]: https://gemnasium.com/jpalumickas/mailerlite-ruby
[coveralls]: https://coveralls.io/r/jpalumickas/mailerlite-ruby
[codeclimate]: https://codeclimate.com/github/jpalumickas/mailerlite-ruby

[mailerlite]: https://www.mailerlite.com
