# strings

Some string utilities for FANUC KAREL.

## Development

You must have ROBOGUIDE installed and the the WinOLPC bin directory
needs to be on your system $PATH.

1. Download [GnuWin](http://gnuwin32.sourceforge.net) if you don't
   already have it
2. Clone the repository
3. Run `make` to build the KAREL binary PC files
4. Run `make deploy` to upload to virtual robot at localhost
5. Run `make test` to test

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
