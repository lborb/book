# `kw-fn`'s Book of Rust Books

A catalogue of Rust mdbooks.

## Viewing

See the [rendered book](https://kw-fn.github.io/book/).

## Development

Install [`mdbook`](https://github.com/rust-lang/mdBook):
```
cargo install mdbook
```

Build the book:
```
mdbook build
```
The generated files are in the `book` directory.

View the built book:
```
mdbook serve
```
This will launch a local web server to serve the book. Navigate to
[localhost:3000](http://localhost:3000/) in a web browser. While the web server
is running, the rendered book will automatically update if the source files
change.

## Deployment

The book is deployed to the `gh-pages` branch by CI on a push to the `main`
branch.
