# json2yaml

Command to convert from JSON to YAML

## Installation

Add this line to your application's Gemfile:

    gem 'json2yaml'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install json2yaml

## Usage

### Read from files

```
$ json2yaml file1.json file2.json
```

### Read from STDIN

```
$ tail -F access.json | json2yaml
```

## Contributing

1. Fork it ( https://github.com/yuya-takeyama/json2yaml/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
