# Raise Ergo
An ergonomic keyboard layout for the Dygma Raise keyboard, geared towards programming and the
command line.

## Benefits

* QWERTY-based for ease of learning.
* Reduces stress on your pinkies by moving many keys away from them and instead to your thumbs.
* Reduces discomfort from awkward key combinations by putting the modifier keys under your thumbs
  and having dedicated keys for skipping/deleting words and lines.
* Reduces hand movement and increases data entry speed by having <kbd>⇥</kbd> and
  <kbd>↩︎</kbd> under your thumbs, plus deletion and cursor movement keys under your finger tips
  (activated by your thumbs).
* Decreases finger travel and increases typing speed (especially when programming) by having all
  word separators (<kbd>␣</kbd>, <kbd>-</kbd>, <kbd>\_</kbd>) and quotation marks (<kbd>'</kbd>,
  <kbd>`</kbd>) under your thumbs.

## [Layer 0](layer0.json): Typing for macOS
![layer 0](img/layer0.svg)

### Thumb keys
| | <kbd>alt</kbd> | <kbd>•••</kbd> | <kbd>••</kbd> | <kbd>•</kbd> | <kbd>⏤</kbd> | <kbd>⏤</kbd> | <kbd>•</kbd> | <kbd>••</kbd> | <kbd>•••</kbd> | <kbd>alt</kbd> |
| --: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| When held | <kbd>⌥</kbd> | <kbd>⇧</kbd> | <kbd>⌃</kbd> | <kbd>⌘</kbd> | Layer 1 | Layer 1 | <kbd>⌘</kbd> | <kbd>⌃</kbd> | <kbd>⇧</kbd> | <kbd>⌥</kbd> |
| Otherwise | <kbd>⎋</kbd> | <kbd>'</kbd> | <kbd>`</kbd> | <kbd>↩︎</kbd> | <kbd>⇥</kbd> | <kbd>␣</kbd> | <kbd>-</kbd> | <kbd>=</kbd> | <kbd>[</kbd> | <kbd>]</kbd> |

### Special keys
| Key | Action |
| --: | :-- |
| <kbd>Scroll Lock</kbd> | Decrease Display Brightness |
| <kbd>Pause</kbd> | Increase Display Brightness |

## [Layer 1](layer1.json): Editing overlay for macOS
![layer 1](img/layer1.svg)

### Purple keys
| Key | Action |
| :-: | :-- |
| <kbd>/</kbd> | Menu Search |
| <kbd>\\</kbd> | Tabs Exposé |
| <kbd>Z</kbd> | Windows Exposé |
| <kbd>X</kbd> | Applications Exposé |
| <kbd>C</kbd> | Desktop Exposé |
| <kbd>V</kbd> | Maximize[<sup>*</sup>](#rectangle) |
| <kbd>B</kbd> | Center[<sup>*</sup>](#rectangle) |
| <kbd>W</kbd> | Left Half[<sup>*</sup>](#rectangle) |
| <kbd>T</kbd> | Right Half[<sup>*</sup>](#rectangle) |

<a id="rectangle"><sup>*</sup></a>Requires [Rectangle](https://rectangleapp.com).

## Author
© 2020 [Marlon Richert](https://github.com/marlonrichert)

## License
This project is licensed under the GPL-3.0 License. See the [LICENSE](LICENSE) file for details.
