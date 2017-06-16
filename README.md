# Luhn::Validator

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/luhn/validator`. To experiment with that code, run `bin/console` for an interactive prompt.


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'luhn-validator'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install luhn-validator

## Usage

	number = '78345979-5'
	Luhn::Validator.valid? number
	# => true

	number = '78345979'
  	Luhn::Validator.checksum? number
  	# => 5

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

### Status

	Em produção

## Authors

* **Denis Nascimento**
