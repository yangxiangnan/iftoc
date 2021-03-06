# Iftoc

![](http://img.shields.io/travis/CocoaPods/CocoaPods/master.svg?style=flat)
![](http://img.shields.io/gem/v/cocoapods.svg?style=flat)

Converts SVG or CSS StyleSheets for IconFont like [iconfont.css](https://github.com/panghaijiao/iftoc/blob/master/iconfont.css) to [OC or Swift](https://github.com/panghaijiao/iftoc/tree/master/iconfont) code file automatically

## Example

- Input: [iconfont.css](https://github.com/panghaijiao/iftoc/blob/master/iconfont.css) or [iconfont.svg](https://github.com/panghaijiao/iftoc/blob/master/iconfont.svg)
- Output: [Iconfont.h](https://github.com/panghaijiao/iftoc/blob/master/iconfont/Iconfont.h)  [Iconfont.m](https://github.com/panghaijiao/iftoc/blob/master/iconfont/Iconfont.m) or [Iconfont.swift](https://github.com/panghaijiao/iftoc/blob/master/iconfont/Iconfont.swift)

## Installation

Install it yourself as:

	$ gem install iftoc
	
Update it yourself as:

	$ gem update iftoc

## Usage

Usage: iftoc \<svgfile | cssfile> [--out \<outpath>] [--lang \<language>]

## e.g.
 	
	$ iftoc iconfont.svg

or

	$ iftoc iconfont.css

or

	$ iftoc iconfont.svg -o /iconfont
	
or

	$ iftoc iconfont.svg -o /iconfont -l swift

## iconfont.svg & iconfont.css

Iconfont.svg or Iconfont.css can be created automatically from [http://www.iconfont.cn](http://www.iconfont.cn/)

.

├── **iconfont.css**

├── **iconfont.svg**

├── iconfont.ttf

└── iconfont.woff
    
## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/panghaijiao/iftoc. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

