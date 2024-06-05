# FaTaMa Publish

This repository contains all meeting notes and workshop journals from the conference of mechanical engineering student councils.

## Preconditions

Install dependencies.

```shell
cargo install mdbook
```

## Writing

Start a local webserver with a watcher for file changes.

```shell
mdbook serve --open
```

## Publish

Render files to finished book.

```shell
mdbook build
```
