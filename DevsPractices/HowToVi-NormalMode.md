## Normal mode

Allows to navigate in the file.

- Navigate char by char
    - `h` : left
    - `j` : down
    - `k` : up
    - `l` : right
- Navigate by word
    - `w` : next word
    - `e` : end of the word
    - `b` : beginning of the word

---

You can also add a number before the action !
Example :
<!-- .slide: style="text-align: left;"> -->
<pre><code data-line-numbers="1|2|4" data-noescape>Typing 3w is equal to pressing 3 times "w"
<b>M</b>oving within the text.

Moving within the <b>t</b>ext.
</pre></code>

---

### Find a character

Using `f` allows you to search for a specific character !
e.g. fo finds the next o

<!-- .slide: style="text-align: left;"> -->
<pre><code data-line-numbers="1|2|4" data-noescape>Once again, numbers can also be used !
"3fq" helps you to find the 3rd occurrence of 'q'.
<b>F</b>or example, you can find 3rd occurrence of 'q' with 3fq, que ?

For example, you can find 3rd occurrence of 'q' with 3fq, <b>q</b>ue ?
</pre></code>

---

### Start and end of line

- `0` allows you to go to the start of a line
- `$` allows you to go the end of a line

---

### Find other occurrence of a word

- `*` find the next occurrence of the current word
- `#` find the previous occurrence of the current word

--- 

### Start and end of file

- `gg` go to the start of the file
- `G` go to the end of the file
- Adding a number before `G` allows you to go to a specific line

--- 

### Search a text

- `/` + `the string you are looking for` + ENTER allows you to search for the given string
- `n` allows you to find the next occurrence
- `N` allows you to find the previous occurrence
- Adding a number before `G` allows you to go to a specific line