# Markdown notes

By default, Markdown doesn't respect line breaks unless there are two of them to form a new paragrap. In order to create a single line-break (as opposed to a new paragraph), you must end the line with two spaces. To quickly add two spaces at the end of every non-paragraph-ending line, replace `([^\n])\n([^\n])` with `$1  \n$2` using a text editor that supports regex pattern matching.
