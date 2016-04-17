[![GPL License](http://darrienglasser.com/gpl-v3-logo.jpg)](GPL License)

Powerlint is a simple set of scripts that is set up to test all .cpp and .h
files against Google's coding guidelines.

When run, Powerlint will check every file, and every sub-directory for .cpp,
and .h files, run Google's linter for them, and output it to a file: output.dat

Powerlint needs 3 all three scripts to run. Without lineReader, powerlint, and
cpplint.py, the run will fail.

To run the script, use:

```
./powerlint
```

And to see the outputted file:

```
cat debug.dat
```

Work still needs to be done to sanitize output, and make it cleaner, but it
is in a fully working state, and does its job as it is. 

_

Please note, cpplint is property of Google, and subject to the Creative
Commons License. [Link to Google's License](https://github.com/google/styleguide/blob/gh-pages/README.md).