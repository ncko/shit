# Shit
Pronounced *sheet*, as in cheat**sheet**.

Store and retrieve snippets and cheatsheets from the command line.

https://user-images.githubusercontent.com/7889247/194994345-a7d49e89-3ad7-4346-a20d-54f15e00c129.mov

## Requirements
You can install these requirements using your favorite package manager (apt, homebrew, pacman, etc)
- jq
- fzf

## Usage

```console
  shit <command> [flags]
```

### Commands
- **add:**    add a new shit
- **delete:** delete an existing shit
- **edit:**   edit an existing shit
- **dump:**   print shits file
- **direct:** open shits file directly

### Flags
- **-h**        show usage information

### Examples

Find an existing shit
```console
$ shit
```

Add a new shit by passing a category and item title
```console
$ shit add -c bash -i "display hello world message"
```

Delete a shit
```console
$ shit delete
```

Edit an existing shit
```
$ shit edit
```

### Feedback
Open an issue at github.com/ncko/shit

## Inspired by
- [This TIL repo](https://github.com/jbranchaud/til)
- [cht.sh](https://cht.sh/)
- [ThePrimeagen](https://github.com/ThePrimeagen)


