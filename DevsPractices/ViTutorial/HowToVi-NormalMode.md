## Normal mode

Allows to navigate in the file.

- Navigate char by char
    - <b><i>h</b></i>: left
    - <b><i>j</b></i> : down
    - <b><i>k</b></i> : up
    - <b><i>l</b></i> : right
- Navigate by word
    - <b><i>w</b></i> : next word
    - <b><i>e</b></i> : end of the word
    - <b><i>b</b></i> : beginning of the word

---

You can also add a number before the action !

<!-- .slide: style="text-align: left;"> -->
<pre><code data-line-numbers="1|2|4" data-noescape>Typing 3w is equal to pressing 3 times "w"
<ins>M</ins>oving within the text.

Moving within the <ins>t</ins>ext.
</code></pre>

---

## Find a character

Using <b><i>f</i></b> allows you to search for a specific character !
e.g. <b><i>fo</i></b> finds the next o

<!-- .slide: style="text-align: left;"> -->
<pre><code data-line-numbers="1|3|5" data-noescape>Once again, numbers can also be used !
"3fq" helps you to find the 3rd occurrence of 'q'.
<ins>F</ins>or example, you can find 3rd occurrence of 'q' with 3fq, que ?

For example, you can find 3rd occurrence of 'q' with 3fq, <ins>q</ins>ue ?
</code></pre>

---

## Start and end of line

- <b><i>0</b></i> : allows you to go to the start of a line
- <b><i>$</b></i> : allows you to go the end of a line

---

## Find other occurrence of a word

- `*` : find the next occurrence of the current word
- `#` : find the previous occurrence of the current word

---

## Start and end of file

- <b><i>gg</b></i> :  go to the start of the file
- <b><i>G</b></i> : go to the end of the file
- Adding a number before <b><i>G</b></i> allows you to go to a specific line

---

## Search a text

- `/` + `the string you are looking for` + ENTER allows you to search for the given string
- <b><i>n</b></i> :  allows you to find the next occurrence
- <b><i>N</b></i> : allows you to find the previous occurrence

---