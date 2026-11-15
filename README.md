# Gigeresk Tap

Homebrew formulae maintained by @gigeresk.

## Formulae

| Formula | Description |
| --- | --- |
| [`tclreadline`](Formula/tclreadline.rb) | GNU Readline for interactive Tcl shells ([upstream](https://github.com/flightaware/tclreadline)). Handy for OpenROAD, Tiny Tapeout and other Tcl-driven EDA flows. |

```sh
brew install gigeresk/tap/tclreadline
```

Then add to `~/.tclshrc`:

```tcl
if {$tcl_interactive} {
    package require tclreadline
    ::tclreadline::Loop
}
```

## How do I install these formulae?

`brew install gigeresk/tap/<formula>`

Or `brew tap gigeresk/tap` and then `brew install <formula>`.

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "gigeresk/tap"
brew "<formula>"
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
