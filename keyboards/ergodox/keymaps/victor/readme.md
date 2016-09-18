# Victor's ErgoDox EZ Config

Based on the default keymap.
Goal is to optimize for osx + tmux + vim

## TODO
- make it easier to hop into coding layer
- caps lock?
- switch ; and : (for vim)

## Changelog
* Sep 17, 2016 (V1.0):
  * Forked from default keymap (V1.1)
  * Left pinky backspace changed to ctrl on hold, esc on tap
  * hyper and meh keys changed to my tmux prefix (CTRL-S)

## Docker Instructions
To compile victor/keymap.c with docker:
`docker run -e keymap=victor -e keyboard=ergodox --rm -v $('pwd'):/qmk:rw edasque/qmk_firmware`

