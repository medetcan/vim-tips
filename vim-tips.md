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
* **Count <C-a>** increments the number by a **Count** 
* **Count <C-x>** decrements the number by a **Count**
* **cW** you can use this command to change the first word.
* **gcc** you can use this command to comment out the selected line.
* **gcap** will comment out the current paragraph.
* **g{G** will comment out to the begining of the selected line to the end of the file.
* **gg=G** indents the whole file accordingly the specified language rules.
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