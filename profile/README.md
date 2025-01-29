# Gost-DOM - Headless browser for Go

Your go-to solution for a TDD workflow

## About

This is the home of go-dom, a headless browser for Go build for testing web
applications with JavaScript. It is specifically written with Go/HTMX in mind, a
tech combination gaining in popularity.

This is created by me, Peter Strøiman, a software developer with 25+ years of
experience in software development, primarily web development.

The project itself has spawned a few related side projects, all collected here
under the gost-dom organisation.

## Repositories

- [browser](https://github.com/gost-dom/browser) The browser itself
- [code-gen](https://github.com/gost-dom/code-gen) Code generator for code-dom
- [generators](https://github.com/gost-dom/generators) Generic Go code generation layer
- [webref](https://github.com/gost-dom/webref) Exposes Go structs representin web standards specifications

Many parts of the browser code can be generated from Web IDL specifications. The
`code-gen` repository contains the code to generate browser code. The other two
projects, `generators` and `webref` started as part of the code generator, but
were extracted to separate projects as they could be useful on their own in
other projects

`generators` contains code to help generate Go code. It is a layer on top of
[jennifer](https://github.com/dave/jennifer) to provide an interface better
designed for composition.

`webref` exposes web specs as native go types. It is based on data from
[github/w3c/webref](https://github.com/w3c/webref)

## Looking for sponsors.

I am looking for sponsors, else I will have to abandon the project, to make time
for paying work.

Github sponsors is not enabled for this organisation (yet), but I have sponsors
enabled on my private profile.

- [Peter's github profile](https://github.com/stroiman)
- [Peter's github sponsors page](https://github.com/sponsors/stroiman)

## Looking for contributors

This is a massive undertaking, and having people helping out t
would be amazing.

## Attribution

Logo is based on the Gopher mascot by Renee French and is licensed under the [Creative Commons 4.0 Attribution License](https://creativecommons.org/licenses/by/4.0/).

The artwork was based on an svg file by Takuya Ueda (https://twitter.com/tenntenn). Licensed under the Creative Commons 3.0 Attributions license. The svg was fetched from https://github.com/golang-samples/gopher-vector?tab=readme-ov-file
