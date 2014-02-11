# HTML Scanner

A set of classes to help removing tags from HTML.

* HTML::Sanitizer
* HTML::FullSanitizer
* HTML::LinkSanitizer
* HTML::WhiteListSanitizer

## Installation

Add this line to your application's Gemfile:

    gem 'html-scanner'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install html-scanner

## History

Hidden deep inside Rails is a standalone project called html-scanner. It's
vendored in ActionView (and ActionPack before that).

I've needed to use just that part of Rails on its own. A quick search reveals
that other projects have had that need as well and have vendored html- scanner
on their own.

Thus, this project was extracted to a standalone gem.

## Contributing

1. Fork it ( http://github.com/koppen/html-scanner/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request


## Contributors

Plenty of people have contributed to HTML Scanner before it turned into its own
project.

* Aaron Patterson
* Alexey Vakhov
* AvnerCohen
* Bruno Michel
* Charlie Somerville
* David Heinemeier Hansson
* Emilio Tagua
* Evan Farrar
* Genadi Samokovarov
* Jamis Buck
* Jeffrey Chupp
* Jeffrey Hardy
* Jeremy Kemper
* Jimmy Baker
* Joost Baaij
* Josh Kalderimis
* Joshua Ballanco
* Lauro Caetano
* Manu
* Marcel Molina
* Michael Koziarski
* Piotr Sarnacki
* Pratik Naik
* Rick Olson
* Santiago Pastorino
* Sebastian Martinez
* Sergey Nartimov
* Thiago Pradi
* Timothy N. Tsvetkov
* Vipul A M
* Xavier Noria
* misfo
* wycats

## License

Licensed under the MIT License. See LICENSE for details.
