# Count all lines in a git directory from files with .java, .c, or .h extensions.
> git ls-files | grep '\.java$\|\.c$\|\.h$' | xargs wc -l
