# NodeUp

## Badges

[![Docker Repository on Quay](https://quay.io/repository/12trip/chef-ci/status "Docker Repository on Quay")](https://quay.io/repository/12trip/chef-ci)
[![Travis build status](https://api.travis-ci.org/onetwotrip/chef-ci.svg?branch=master "Travis build status")](https://travis-ci.org/onetwotrip/chef-ci)
[![Code Climate](https://codeclimate.com/github/onetwotrip/chef-ci/badges/gpa.svg)](https://codeclimate.com/github/onetwotrip/chef-ci)
[![Test Coverage](https://codeclimate.com/github/onetwotrip/chef-ci/badges/coverage.svg)](https://codeclimate.com/github/onetwotrip/chef-ci/coverage)
[![Issue Count](https://codeclimate.com/github/onetwotrip/chef-ci/badges/issue_count.svg)](https://codeclimate.com/github/onetwotrip/chef-ci)

## Usage

Example:

bin/nodeup --role api-search -e do-sales

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/dshmelev/nodeup.

