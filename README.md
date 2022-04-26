# Uniq

This is a simple remake of the Linux "uniq" command. When uniq is called on a file here, it will print out the file omitting repeated lines. If uniq is called without a file, in which case it will read from standard input in the terminal using pipes. This implementation can also use the -c (count the number of occurrences of a line), -d (only print duplicate lines), and -i (ignore case differences in lines) functinalities that would work with a real Linux machine.
