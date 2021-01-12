# bmk

  A simple, file-based bookmark manager written in POSIX shell.
Comes with a dmenu front-end (bmkmenu).

## Layout

```
bmk/bookmarks
|-- b1
|-- b2
...
```

## Functionality

  All base bmk commands can be run with bmkmenu.
  All arguments are optional.

* bmk list
  Lists all available bookmarks.

* bmk add <name> <value>
  Adds a bookmark with the given name and value.

* bmk del <name>
  Removes the bookmark. Will prompt for confirmation.

* bmk sel <name>
  Selects the bookmark. Value is returned through stdout.

## Requirements

### bmk
any POSIX-compliant shell

### bmkmenu
* [dmenu](\https://tools.suckless.org/dmenu) (Plus a few scripts)
* xclip
* libnotify
