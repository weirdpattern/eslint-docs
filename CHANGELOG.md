# v0.1.x

## v0.1.3
🐛 install `regenerator-runtime` for `async function` support

## v0.1.2 (💀)
* Use the documentation file’s predominant newline style when inserting newlines ([#7])
* Remove `babel-polyfill` and fix the tests on Node v4

[#7]: https://github.com/j-f1/eslint-docs/issues/7

## v0.1.1
Properly support the CLI on older versions of Node

## v0.1.0
Add Babel to enable support for older Node versions.

# v0.0.6
Allow specifying an `Array` for the `extraDescription` key;
it will be `.join(', ')`ed before being added to the README.

# v0.0.5
✨ Add support for an `extraDescription` key in the rule metadata
specifying content that should go in () after the rule description in the README.

# v0.0.4
✨ prefix the rule names with `PLUGINNAME/` in the README

# v0.0.3
🐛 unwrap Promise properly

# v0.0.2
Actually publish the source code

# v0.0.1
Initial release 🚀
