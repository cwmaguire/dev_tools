# dev_tools

Various tools I use for development.

Grep tools:
(ignore certain directories, only include certain files)

erlgrep_notest - grep within .src files but not test files

erlgrep        - link to erlgrep_notest

erlgrep_test   - grep within .src files including test files

erltgrep       - link to erlgrep_test

erlgrep_deps   - grep within .src files in dependencies only

erldgrep       - link to erlgrep_deps

confgrep       - grep for something in *.app.src, .config files and Make files

defgrep        - grep for -define(FOO) statements

sqlgrep        - grep within SQL files

grepmake       - run make and grep for errors

Other tools:

fdate          - print out the data as an _ separated string \(for unique file names\)

getlogs        - download lately modified logs and gunzip if nec.

ptest          - delete old logs and output and run make
