# skript

A command-line tool to bootstrap scripts according to [the normalized script pattern](https://github.blog/2015-06-30-scripts-to-rule-them-all/).

## Install

```shell
brew tap soulim/tools
brew install skript
```

or if you do not want to add the whole `soulim/tools` tap and interested only
in `skript` tool:

```shell
brew install soulim/tools/skript
```

## Usage

Bootstrap [`script/setup` script](https://github.com/github/scripts-to-rule-them-all#scriptsetup):

```shell
skript init setup
```

Other scripts according to the normalized script pattern could be bootstrapped
using `skript init <name>`. Following names are supported: `setup`,
`bootstrap`, `test`, `update`.

Use `skript help` to print the usage instructions at any time.

## Contributing

PRs accepted.

## License

SEE [LICENSE](LICENSE).
