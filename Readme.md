*This repository is a mirror of the [component](http://component.io) module [component/title](http://github.com/component/title). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-title`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# title

  Manipulate the document title and reset.

## Installation

    $ component install component/title

## API

### title(str, ...)

  Set title to `str` with optional arguments,
  where `%o` represents the original title.

```js
title('%s% - %o', upload.percent);
```

### title.reset()

  Reset the title back to its original string.

## License

  MIT
