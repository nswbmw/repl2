## repl2

Load third-party modules into REPL from `~/.noderc`.

### Install

```sh
$ npm i repl2 -g
```

### Usage

```sh
$ noder
```

First:

```sh
$ vim ~/.noderc
```

```json
{
  "lodash": "__",
  "moment": "moment",
  "validator": "validator"
}
```

Second:

```sh
$ npm i lodash moment validator -g
```

Three:

```sh
$ noder
```

### License

MIT