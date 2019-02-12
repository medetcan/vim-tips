* **.** command repeats the last change.
* **x** command deletes the character under the cursor
* **dd** command deletes the whole line.
* **>G** increases the indentation from the current line to until the end of the file.
* **o** command appends new line after the end of the current line and sets the cursor while changing mode to insert.
* **A** command goes the end of the immediate line sets cursor position there while changing current mode to insert.
* **s** command compounds two steps into one. It deletes the character under the cursor enter the insert mode.
* **f{char}** command tells vim to look ahead for the next occurence of the specified character and then if a match is found move the cursor directly into it.
    * **;** will repeat the last search going forward.
    * **,** will repeat the last search going backward.
* **cw** command deletes to the end of the word and drops us into insert mode.
* **daw** command deletes the selected word.
   * **aw**  command -a word- selects text object and it includes trailing white spaces!
* **Count \<C-a\>** increments the number by a **Count**
* **Count  \<C-x\>** decrements the number by a **Count**
* **cW** you can use this command to change the first word.
* **gcc** you can use this command to comment out the selected line.
* **gcap** will comment out the current paragraph.
* **g{G** will comment out to the begining of the selected line to the end of the file.
* **gg=G** indents the whole file accordingly the specified language rules.
* **\<C-o\>** switch from insert mode to insert normal mode.
* **zz** command redraws the screen with the current line in the middle.
* **J** command joins the current line and next line together.
* **\<C-w\>** command deletes one word backward in insert mode.
* **\<C-u\>** command deletes starting from the begining of the line to the end of the cursor. (??)
* **\<C-h\>** deletes one characterat a time going backward.
* **R** switch from normal mode to replace mode.
* **gR** switches to virtual replace mode and treats tab characters as though it consisted of spaces.
* **r{char}** single shot version of the replace mode. Switches back to normal mode after the execution of the command finishes.
* **gr{char}** single shot version of the virtual replace mode.
* **v** command switches to character wise visual mode.
* **V** command switches to line wise visual mode.
* **\<C-v\>** command switches to block wise visual mode.
* **\<C-g\>** command switches to select mode.
* **gv** reselect the last visual selection.
* **o** navigates to end of the highlighted text in visual mode.
* **gU{motion}** gU command combined with the motion changes every selected characters to their respective uppercase equivalents.
* **U** command in visual mode changes each selected characters to their respective uppercase equivalents.
* **r{char}** replace each selection with the char.
* **:[range]delete[reg{i}]** delete specified lines into register
* **:[range]yank[reg{i}]** yank specified lines into register
* **:[range]substitute/{original string}/{replacement string}** substitutes specified string with given replacement string in command mode
* **<C-r\>{register}** put contents of the specified register into command line
* **<C-v\>** inserts chracter that are not found on the keyboard
* **.** dot represents the current line in command mode
* **%** has special meaning in command mode, it means act upon whole file.
* **!** we can invoke external commands from vim prefixing commands with bang symbol in command mode
* **shell** and **terminal** you can use these two commands in command mode to start interactive shell session without leaving vim. **exit** commands kills the shell returns us to vim.
* **S** deletes the current line in normal mode and drops us into insert mode
* **gd** go to definition
# Operator Tables
   * **c** change
   * **d** delete
   * **y** yank into register
   * **g~** swap case
   *  **gu** make lowercase
   * **gU** make uppercase
   * **>** shift right
   * **<** shift left
   * **=** auto indent
   * **!** filter {motion} lines through on external program
       * When an operator command is invoked in duplicate. It avts upon the current line.
