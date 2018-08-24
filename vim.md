VIM for generic text manipulation
======

In addition to being ideal for editing code, VIM has over the past 4 years opened up the possibilities while editing text.  It's an investment in productivity, simply put.  

This list is a collection of my most-used features

# Indent multiple lines quickly in vi
@see https://stackoverflow.com/questions/235839/indent-multiple-lines-quickly-in-vi

Use the `>` command. To indent 5 lines, `5` `>` `>`. To mark a block of lines and indent it, `V` `j` `j` `>` to indent 3 lines (vim only). To indent a curly-braces block, put your cursor on one of the curly braces and use `>``%`.

# Comment / Uncomment a Range of Lines
@see https://unix.stackexchange.com/questions/120615/how-to-comment-multiple-lines-at-once


## To Comment:
`:66,70s/^/#`

## To: Un-Comment:
`:66,70s/^#/`