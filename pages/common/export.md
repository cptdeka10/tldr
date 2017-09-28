# Export

>Sets the environment variable on the left side of the assignment to the value on the right side of the assignment.

- The command:

`export PATH=~/.composer/vendor/bin:$PATH`

- Explanation 1:

`$PATH` is the default PATH assignment.

- Explanation 2:

`~/.composer/vendor/bin` is going to expand to `/home/username/.composer/vendor/bin` , 
where `.composer` is hidden folder due to the leading dot.

- Explanation 3:

`~/.composer/vendor/bin:$PATH` have now transformed into long list of folders, separated by `:`.
