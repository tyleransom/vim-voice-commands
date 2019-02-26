# vim-voice-commands
This is an attempt at integrating vim with Nuance's Dragon NaturallySpeaking.

Below is the list of functions that need to be programmed as custom commands in NaturallySpeaking. (I am hoping to share my NaturallySpeaking user profile on this repo. [It seems](http://nuance.custhelp.com/app/answers/detail/a_id/6874/~/how-to-export-and-import-a-user-profile-in-dragon-naturallyspeaking) that this requires the Pro edition of NaturallySpeaking.)

| Function  | Phrase  | Keystrokes  |
|---|---|---|
| enter insert mode  | "sert"  | `i`  |
| enter normal mode  | "skeep"  | `Esc`  |
| visual line mode  | "visual line"  | `Shift+v`  |
| visual block mode  | "visual block"  | `C+v`  |
| up `N` lines  | "oop `N`"  | `Nk`  |
| down `N` lines  | "doon `N`"  | `Nj`  |
| left `N` columns  | "eft `N`"  |  `Nh` |
| right `N` columns  | "ite `N`"  | `Nl`  |
| page up  | "page oop"  | `C+u`  |
| page down  |  "page doon" |  `C+d` |
| block insert  | "block insert"  | `Shift+i`  |
| block change  | "block change"  | `Shift+c`  |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
| save  | "save"  | `:w`  |
| open  | "tabedit"  | `:tabedit`  |
| refresh  | "refresh"  | `:e!`  |
| quit  | "quit"  | `:q`  |
| force quit  |  "really quit" | `:q!`  |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |

# To add
* "yank to ____"
* "next word"
* "previous word"
* "change in parent"
* "change around paren"
* ...
