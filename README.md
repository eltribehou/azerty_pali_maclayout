# Azerty Mac keyboard layout with Pāli diactritics

A Mac keyboard layout for Azerty keyboards, with Pāli diactritics available on Alt+letter.

## Installation

- Copy AzertyPali.layout and AzertyPali.icns to your `~/Library/Keyboard Layouts` directory (or `make install` in this directory from a terminal)
- Close and reopen your user session (or the layout won't be available in the next step)
- In system settings, under keyboard types click `+` and search for AzertyPali (it will be under the language 'Other')
- Enable "Show Input menu in menu bar" if you want to switch between layouts easily

## Mapping

| Key | Alt | Alt + Shift | Alt + Shift + Ctrl |
| :-: | :-: | :-------: | :-: |
| a   | ā   | Ā         | |
| t   | ṭ   | Ṭ         | |
| u   | ū   | Ū         | |
| d   | ḍ   | Ḍ         | |
| h   | ḥ   | Ḥ         | |
| l   | ḷ   | \| (pipe) | Ḷ |
| m   | ṃ   | Ṃ         | |
| n   | ~   | ṇ       | Ṇ |
| ,   | ṅ   |           | |

## Notes

I have kept the pipe `|` and tilde `~` characters as they were on the standard mapping, even if it would have made sense to replace them so that the mapping is the same everywhere. That's because I use those characters a lot, and replacing their bindings is a sure way to drive me crazy. Alternative bindings with Ctrl have been added for those cases.

You can easily adapt the mapping to your needs with [Ukelele](https://software.sil.org/ukelele/). It makes the process quite easy, you can also start from your own language mapping if you need.

The inspiration for this mapping comes from the [easyunicode](https://zenodo.org/records/3373473) mapping which did what i wanted, but had no Azerty version...  
I just used Ukelele, clicked "New from current input source" to create a new layout from Azerty and added the diactritics. 
