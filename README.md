## repl2

Load third-party modules into REPL from `.noderc`.

### Install

    npm i repl2 -g

### Usage

```
$ noder
```

**NB**: repl2 will try to read `.noderc` from current directory and user directory (like: `~/.noderc`).

#### .noderc

Example:

```
{
  "lodash": "__",
  "moment": "moment",
  "validator": "validator"
}
```

### License

MIT