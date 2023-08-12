# HyperText Markup Builder

[![Package Version](https://img.shields.io/hexpm/v/htmb)](https://hex.pm/packages/htmb)
[![Hex Docs](https://img.shields.io/badge/hex-docs-ffaff3)](https://hexdocs.pm/htmb/)

A tiny HTML builder for Gleam.

```gleam
let html = 
  h("h1", [], [text("Hello, Joe!")])
 |> render
 |> string_builder.to_string
assert html == "<h1>Hello, Joe!</h1>"
```

This package doesn't do much. If you'd like more features, check out these
alternatives:

- [Glemplate](https://hex.pm/packages/glemplate)
- [Lustre](https://hex.pm/packages/lustre)
- [Nakai](https://hex.pm/packages/nakai)
- [React Gleam](https://hex.pm/packages/react_gleam)


## Installation

```sh
gleam add htmb
```

The documentation can be found at <https://hexdocs.pm/htmb>.
