# Elm Bootstrap

Taking inspiration from this
[comment](https://github.com/elm-lang/elm-reactor/issues/138#issuecomment-240945527),
elm bootstrap runs a local server that serves an index.html that you can add
custom CSS and markup to. Your elm code compiled on each change to any file
contained in `src/`, and the resultant javascript file is embedded within the
served document.

## Requirements

- Go installed (https://golang.org/dl/)
- Elm is installed (https://guide.elm-lang.org/get_started.html)

## Setup

- Run `go get github.com/stuartnelson3/elm-bootstrap`
- Run `elm package install -y` to install the elm dependencies listed in `elm-package.json`
- Run `elm-bootstrap`
- Make a change in `src/Main.elm` and save (the elm code is only compiled when a file change is detected)
- Go to `localhost:8080`
