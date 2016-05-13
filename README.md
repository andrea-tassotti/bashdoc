# bashdoc
Bash programs documentation companion

Bashdoc work for bash code as javadoc for java source code (or like other tools).
bashdoc is a simple AWK program.

Run as program (remember to set permission) with bash file you want to generate documentation as first (and last) line argument.

It search for comment before bash function declaration starting with ##.

The first line of comment will be summary for function documentation; other comment line will be used as full function description.

bashdoc search comment for the following special token:

@author
@see
@note
$1 .. $n  for parameters
$? return code


