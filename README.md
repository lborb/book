# The Little Book of Rust Books

A catalogue of Rust mdbooks.

## Pull Requests

Pull requests are welcome. Please ensure they conform to the conventions described below.

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

Each entry is of the form:
```
* [The Literal Title of The Book](https://a-link-to-the/book/) - an optional comment if the title isn't self-explanatory
```

The `.editorconfig` file captures basic source files formatting conventions.
Many editors support this file natively; others (such as VS code) require a plugin, see https://editorconfig.org/.

The default branch is `main`. See [Renaming the default branch from master](https://github.com/github/renaming) for the rationale.

Commit logs should describe the specific changes made by a commit. See [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/).

## Deployment

The book is deployed to the `gh-pages` branch by CI on a push to the `main`
branch.
