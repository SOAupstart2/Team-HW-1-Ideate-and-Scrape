# soa_codeschool [![Build Status](https://travis-ci.org/pengyuchen/Team-HW-1-Ideate-and-Scrape.svg?branch=master)](https://travis-ci.org/pengyuchen/Team-HW-1-Ideate-and-Scrape)[![Gem Version](https://badge.fury.io/rb/soa_codeschool.svg)](https://badge.fury.io/rb/soa_codeschool)

https://rubygems.org/gems/soa_codeschool

A simple Ruby Gem to scrap the website codeschool and to get courses and its instructors.


## Usage

Run the following command:

```
gem install soa_codeschool
```
### Command line usage

```
codeschool  # Puts JSON array of code school courses and teachers to command line
```

### Usage in ruby code
```
require 'scrape'

code_school = SiteScraper.new
code_school.course_names  # Returns array of course names
code_school.code_school_data  # Returns JSON array of code school courses and teachers
code_school.code_school_output  # Puts JSON array of code school courses and teachers
```

## License

Distributed under the [MIT License](LICENSE).
