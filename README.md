## reset-jss

[JSS](https://github.com/cssinjs/jss) port of [reset.css](http://meyerweb.com/eric/tools/css/reset/).

#### Usage

```js
import jss from 'jss'
import reset from 'reset-jss'

jss.createStyleSheet(reset).attach()
```

#### You must know

Required JSS plugins for correct working:

  1. [jss-camel-case](https://github.com/cssinjs/jss-camel-case)
  1. [jss-global](https://github.com/cssinjs/jss-global)

Anyway, you can use a [preset](https://github.com/cssinjs/jss-preset-default) for a quick setup with default plugins.

### Issues

File a bug against [cssinjs/jss prefixed with \[reset-jss\]](https://github.com/cssinjs/jss/issues/new?title=[reset-jss]%20).

### License

MIT
