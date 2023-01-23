# gtk4_hello_world

TODO: Write a description here

## Installation

First install dependencies:

  $ brew install gobject-introspection gtk4
  $ export LIBRARY_PATH=/opt/homebrew/lib

Next install Crystal dependencies:

  $ shards install

Bind dependencies (do this after anytime you update/upgrade dependencies):

  $ bin/gi-crystal

And then you can build the project:

  $ shards build

## Usage

  $ bin/gtk4_hello_world

## Development

Edit `src/gtk4_hello_world.cr` like you no longer care.

See also
- [the API docs](https://hugopl.github.io/gtk4.cr/).
- [the repo for GTK4 Crystal Bindings](https://github.com/hugopl/gtk4.cr)
- [the hello world tutorial which inspired this](https://github.com/hugopl/gtk4.cr/blob/master/tutorial/hello_world.md)

## Contributing

1. Fork it (<https://github.com/joelhelbling/gtk4_hello_world/fork>)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Contributors

- [Joel Helbling](https://github.com/joelhelbling) - creator and maintainer
