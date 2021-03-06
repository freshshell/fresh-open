# fresh-open

Open fresh sources in your `$EDITOR`.

## Installation

### Install fresh

Run the following line or follow the [manual install instructions].

``` sh
bash -c "`curl -sL get.freshshell.com`"
```

### Install fresh-open

Paste the following line into your shell or add it to your `~/.freshrc` file.

``` sh
fresh freshshell/fresh-open bin/fresh-open --bin
```

#### cdf

There is also a function you can use to change into the source directory.
To use it you will need to add the following line to your freshrc.

``` sh
fresh freshshell/fresh-open shell/cdf.sh
```

## Usage

``` sh
fresh open freshshell/fresh-open # will open this codebase in your $EDITOR
fresh open freshshell/fresh # will open the fresh codebase in your $EDITOR
```

[manual install instructions]: https://github.com/freshshell/fresh#manual-steps
