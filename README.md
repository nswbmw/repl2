## repl2

Load third-party modules into REPL from `~/.noderc`.

### Install

```sh
$ npm i repl2 -g
```

### Usage

Step 1:

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

Step 2:

```sh
$ npm i lodash moment validator -g
```

Step 3:

```sh
$ noder
> moment()
> validator.isEmail('xxx')
```

### License

MIT
