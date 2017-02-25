# LaTremors

This gem uses the Haversine Formula to find earthquakes originating from cities outside of Los Angeles but were felt in Los Angeles.

It uses a simplified linear relationship between the magnitude of an earthquake and the distance it travels before it can be felt.

It assumes a magnitude-5 earthquake can be felt at up to a distance of 500 miles, magnitude-4 quake to 400 miles, magnitude-3 quake to 300 miles and so on.

You can find data of all earthquakes for the past 30 days [here](http://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_month.csv)

## Usage
la_tremors --start-date --end-date --first 10

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'la_tremors'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install la_tremors

## Usage

TODO: Write usage instructions here

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/la_tremors.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

