# autocomplete+ package

View and insert possible completions in the editor while typing

![Autocomplete+](http://s14.directupload.net/images/140304/y7r7g5df.gif)

## Features

* Shows autocompletion suggestions while typing
* Two modes: Instant and delayed autocompletion (instant might slow down performance)
* Wordlist generation happens initially and on save (saves performance)
* Suggestions are calculated using `fuzzaldrin` (better results)

## Installation

Since this is still in beta, you'll have to install it manually (I'll add it to apm later):

```
$ cd ~/.atom/packages
$ git clone https://github.com/saschagehlich/autocomplete-plus.git
$ cd autocomplete-plus
$ npm install
```

## Known bugs

* Sometimes double completions appear (e.g. `DispDisplayObject` when entering `Disp` and selecting `DisplayObject`)
