# Uniq Command in Linux

  This is a simple remake of the Linux "uniq" command for my operating systems class at NYU. When uniq is called on a file here, it will print out the file omitting repeated lines. If uniq is called without a file, it will read from standard input in the terminal using pipes. This implementation can also use the -c (count the number of occurrences of a line), -d (only print duplicate lines), and -i (ignore case differences in lines) flags that would work with a real Linux machine.
