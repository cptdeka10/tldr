# Export

>Sets the environment variable on the left side of the assignment to the value on the right side of the assignment.

`export PATH="~/.composer/vendor/bin:$PATH`

`$PATH` is the default PATH assignment.

`~/.composer/vendor/bin` is going to expand to `/home/username/.composer/vendor/bin` , 
where `.composer` is hidden folder due to the leading dot.

`~/.composer/vendor/bin:$PATH` have now transformed into long list of folders, separated by `:`.
