# init

If you copy the same boilerplate files (ex. LICENSE) to cwd number of times, then this small script might be useful to you.

You can initialize the boilerplate like:

```sh
init LICENSE
```

This copies LICENSE from `$HOME/.init/LICENSE` to `$PWD/LICENSE`. This script could be powerful for quickly starting up the project from the terminal.

# Usage

## Set up

Clone this repository

```sh
git clone https://github.com/kt3k/init ~/.init
```

Add $HOME/.init to `PATH` variable

```sh
export PATH="$HOME/.init:$PATH"
```

Add boilerplate files you often want to copy. e.g. `LICENSE`, `.gitignore`, `.editorconfig`, etc.

## Example

- [My own init](https://github.com/kt3k/my-init)

# LICENSE

MIT
