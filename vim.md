### VIM
:w !sudo tee %

#### buffers
* selection
+ cut buffer

#### cheat sheet
http://www.catonmat.net/download/bash-vi-editing-mode-cheat-sheet.pdf

#### mapping tutorial
http://vim.wikia.com/wiki/Mapping_keys_in_Vim_-_Tutorial_(Part_1)

#### folding
http://vim.wikia.com/wiki/Folding

#### other
:g/search_string/norm @q # run macro on search results (global + normal command)

/>\_.\{-}< # ???

:let @a='hello' . @a . 'world' # change register a
