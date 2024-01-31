# Changelog

## v2.0.0 - 2024-01-31

- **[BREAKING]** The package now exclusively targets HTML5 and `render_page` no
  longer accepts the `doctype` parameter
  ([#2](https://github.com/lpil/htmb/pull/2))
- [Void elements](https://www.w3.org/TR/2011/WD-html-markup-20110113/syntax.html#void-element)
  are now rendered correctly ([#2](https://github.com/lpil/htmb/pull/2))

## v1.1.0 - 2023-11-06

- Updated for Gleam v0.32.0.

## v1.0.1 - 2023-08-12

- The `escape` function now takes a single argument, while before it erroneously
  took two arguments.

## v1.0.0 - 2023-08-12

- Initial release.
