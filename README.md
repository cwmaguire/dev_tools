# dev_tools

Various tools I use for development.

Grep tools:
(ignore certain directories, only include certain files)

erlgrep_notest - grep within .src files but not test files

erlgrep_test   - grep within .src files including test files

confgrep       - grep for something in *.app.src files and .config files

defgrep        - grep for -define(FOO) statements

sqlgrep        - grep within SQL files

grepmake       - run make and grep for errors

Other tools:

fdate          - print out the data as an _ separated string

                 (for unique file names)

getlogs        - download lately modified logs and gunzip if nec.

ptest          - delete old logs and output and run make
