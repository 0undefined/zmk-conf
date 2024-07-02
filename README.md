# My zmk configuration

I have qwerty available on the master branch, and colemak-dh on its own branch.
The firmware files are unfortunately named identically, but the layouts beyond
the alphas are almost identical, so it should not be too hard to enter
bootloader mode and download the correct one.

* [qwerty downloads](https://github.com/0undefined/zmk-conf/actions?query=is%3Acompleted+branch%3Amaster)
* [colemak-dh downloads](https://github.com/0undefined/zmk-conf/actions?query=branch%3Acolemak-dh+is%3Acompleted)
* [engram downloads](https://github.com/0undefined/zmk-conf/actions?query=branch%3Aengram+is%3Acompleted)

This branch contains [Arnos Engram (2.0) layout](https://github.com/binarybottle/engram).

Engram is designed for a slightly higher quantity of keys, I've therefore tried
to accomodate for that, by moving the Q and Z keys to the center, replacing the
quotes, similarly with the backspace and enter key.

This causes some weidness in the number layer, as I want my punctuation and
other symbols, that are commonly used in conjunction with numbers, available on
the number layer.

_todo: add visualization of the layout(s)_
