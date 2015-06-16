DaData API JS client for Rails Asset Pipeline
=============================================

[JS client for DaData API servise as jQuery plugin] [plugin] by [@gordienko] [author] packaged for Ruby on Rails asset pipeline.

Installation
------------

Add this line to your application's Gemfile:

    gem 'jquery-dadata-rails'

And then execute:

    $ bundle

Add this line to `app/assets/stylesheets/application.css`:

    *= require jquery.suggestions

Add this line to `app/assets/javascripts/application.js`:

    //= require jquery.suggestions.js

Usage
-----

See the original [plugin] README and official [examples].

Contributing
------------

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

### Version policy

This gem version number is in form of **X.Y.Z.P**, where **X.Y.Z** is a version of original [plugin] and **P** is a gem-specific patch level.

[plugin]: https://github.com/gordienko/jquery-dadata-rails
[author]: https://github.com/gordienko
