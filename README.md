# vim-useful-commands

## Table of contents

1. [Motions](#motions)
2. [Regular expression tips](#regular-expression-tips)

### Motions
di( - delete all inside braces, try this wih {, [, ", '

da( - delete all including braces, try this wih {, [, ", '

dat - Delete around an HTML tag, including the tag

dit - Delete inside an HTML tag, excluding the tag

V - select current line

vaw - select word

vap - select paragraph

yaw - yank word 

yap - yank paragraph

`[ - jump to beginning of last yanked text

`] - jump to end of last yanked text

gf - jump to the file name under the cursor

gv - reselect the last visual selection

`< - jump to beginning of last visual selection

`> - jump to end of last visual selection

ctrl + o - go backwards in the jump list

ctrl + i - go forwards in the jump list

g; - go backwards in the change list

g, - go forwards in the change list


"+y - copy a selection to the system clipboard

"+p - paste from the system clipboard

**[⬆ back to top](#table-of-contents)**

### Regular expression tips

:g/pattern/d – remove lines matching pattern

:g!/pattern/d – remove lines that do NOT match the pattern

%s/pattern/replacement/ - replace pattern firs occurrence in line

%s/pattern/replacement/g - replace pattern (each occurrence in line)

%s/\(\d\),/\1 - remove commas followed by digit

**[⬆ back to top](#table-of-contents)**
