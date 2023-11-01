pex makes piping easier.

## Demo

[![asciicast](https://asciinema.org/a/618544.svg)](https://asciinema.org/a/618544)

Or with audio, [a narrated pex demo on YouTube](https://youtu.be/84e2zmZ9Dv8).

### Installation

```
go install github.com/josharian/pex@latest
```

### Usage

```
pex [files...]
```

or

```
command | pex
```

pex will then give you an interactive environment for simple shell-based processing.

Press escape to exit pex. It'll print the pipeline you worked out.

### Status

This is still very much a "I hacked it together" toy. It has rough edges and missing features. And no doubt plenty of bugs.

If you want to improve it, great. Please see todo.md. Note that I am not the world's speediest reviewer.

If you hate it, that's fine too, but don't bother telling me about it.
