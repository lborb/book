# The Little Book of Rust Books

A catalogue of Rust mdbooks.

## Pull Requests

Please note that each entry is of the form:
```
* [The Literal Title of The Book](https://a-link-to-the/book/)
```

## Viewing

See the [rendered book](https://lborb.github.io/book/).

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

### Conventions

Basic conventions around source files formatting are captured in the `.editorconfig` file.
Many editors support that file natively. Others (such as VS code) require a plugin, see https://editorconfig.org/.

Please note that the default branch is called `main`. See https://github.com/github/renaming for more about this convention.

## Deployment

The book is deployed to the `gh-pages` branch by CI on a push to the `main` branch.
