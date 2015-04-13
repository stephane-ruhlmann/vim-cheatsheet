# vim-cheatsheet
A quick and dirty Vim cheatsheet

## Useful Commands
### Basic
- 'h' : go one character left
- 'j' : go one character down
- 'k' : go one character up
- 'l' : go one character right
- 'o' : insert new line

### Line/word movements
- '0          : reach the beginning of the line
- '$'         : reach the end of the line
- 'b'         : go to the beginning of the word
- 'e'         : go the end of the word
- 'w'         : go the beginning of next word
- '$'         : jump to the matching bracket/parenthesis
- 'gg'        : jump to the beginning of the file
- 'G'         : jump to the end of the file
- 'g'nb        : jump to line number 'nb' (e.g. : 'g15' will jump to the 15th line)

### Repeat
- nb 'command'          : repeat following command any_number times (e.g. : '3k' will go 3 characters up)
- nb [i] word [ESC] : insert 'word' nb times

### Find
- 'f' : find following character
- '/' : find following word, use 'n' to go to next occurence
- '*' : find next occurence of word under cursor
- '#' : find previous occurence of word under cursor
