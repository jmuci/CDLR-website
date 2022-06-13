## Running the website locally

### Run CDLR in ubuntu 16: 


curl -sSL https://rvm.io/mpapis.asc | sudo gpg2 --import -
\curl -sSL https://get.rvm.io | bash -s stable --ruby

//For CDLR
/usr/local/rvm/bin/rvm install 2.5.6
/usr/local/rvm/wrappers/ruby-2.5.6/gem install bundler -v 2.0.2
/usr/local/rvm/wrappers/ruby-2.5.6/bundle _2.0.2_ install 
/usr/local/rvm/wrappers/ruby-2.5.6/gem install jekyll -v 3.8.7
/usr/local/rvm/wrappers/ruby-2.5.6/jekyll server


////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

### Run CLDR in Mac OS

Follow the Set Up steps from below this README to get all the dependencies for Jekyll and Airspace.
After that, go to the root folder of the CLDR web repo and run: 

`gem install jekyll bundler`

`bundle exec jekyll serve` -> you will see in the comment the localhost address were the site is being served.


Src: [https://jekyllrb.com/docs/](https://jekyllrb.com/docs/)

# _Airspace_ for Jekyll
![screenshot](screenshots/home.png "Description goes here")

This Jekyll theme is a port of ThemeFisher's Airspace template. It is released under ThemeFisher's free license, which requires attribution.

## Usage
To start your project, [fork this respository](https://github.com/ndrewtl/airspace-jekyll/fork), put in your content, and go!

## Examples
Here are some projects that have used this Jekyll Theme:
* [BOYUAN Open Source 博辕开源](https://boyuanitsm.github.io)
* [Campus VC](https://mrchildneo.github.io/mrchildneo/)
* [Mãos de amar](https://www.maosdeamar.com.br/)
* [ATK Team](http://www.atksec.com/)
* [Coding Club](https://ourcodingclub.github.io/)
* [Dev Empathy Book Club](http://www.devempathybook.club/)
* [DKAN Open Data Catalog](http://getdkan.com) (modified version of this theme)

## Steps for Setup:

### Make sure you have Ruby

First, make sure you have [Ruby](https://www.ruby-lang.org/en/) installed. You can confirm this by running `ruby -v` on the command line:

```sh
$ ruby -v
ruby [version number] (date) [your platform]
```

If you get something like `"Error, command not found"` visit the link above and
install Ruby for your platform.


### Make sure you have Bundler

Next, make sure you have [Bundler](https://bundler.io) installed. Just like
above, run `bundle -v` on the command line:

```sh
$ bundle -v
bundle [version number]
```

If you get `"Error, command not found"` run `gem install bundler` to install it
using RubyGems.

### Run this repository

Clone the repository, and `cd` into it:
```sh
$ git clone https://github.com/ndrewtl/airspace-jekyll.git
$ cd airspace-jekyll
```

Install dependencies locally:
```sh
$ bundle install --path vendor/bundle
```

This should install a local copy of jekyll.

Now run the server:
```sh
$ ./vendor/bundle/ruby/#{YOUR_RUBY_VERSION}/bin/jekyll server
```
