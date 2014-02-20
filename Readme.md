*This repository is a mirror of the [component](http://component.io) module [yields/redact-popover](http://github.com/yields/redact-popover). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-redact-popover`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# redact-popover

  medium inspired editor popover.

  [demo](http://yields.github.io/redact-popover/index.html)

## Installation

  Install with [component(1)](http://component.io):

    $ component install yields/redact-popover

## API

### RedactPopover

  Initialize `RedactPopover` with contenteditable `el`.

#### #add

  Add action `id` with optional `label`.
  the id will be the element class.

#### #remove

  Remove action `id`.

#### #get

  Get action `id`.

#### #refresh

  this method is called whenever you `add()` or `remove()`
  an option in order to cache the `<popover>` size.

  if you do something that will change the size (like hide individual actions) call this method.

#### .tip

  [`component/tip`](https://github.com/component/tip) instance.

#### .classes

  [`component/classes`](https://github.com/component/classes) instance.

#### .events

  [`component/events`](https://github.com/component/events) instance.

## License

  MIT
