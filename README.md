# Most common grep commands

Here are some of the most common grep commands used in the Unix/Linux command line:

## Basic Text Search:

```grep 'pattern' file```


### Case-Insensitive Search:

```grep -i 'pattern' file```


### Recursive Search:

```grep -r 'pattern' /path/to/directory```


### Search for Whole Words:

```grep -w 'pattern' file```


### ow Line Numbers:

```grep -n 'pattern' file```


### Invert Match (ow Lines That Do Not Match):

```grep -v 'pattern' file```


### Count Matching Lines:

```grep -c 'pattern' file```


### Only Matching Part of the Line:

```grep -o 'pattern' file```


### Search Multiple Patterns:

```grep -e 'pattern1' -e 'pattern2' file```


### File Names with Matches:

grep -l 'pattern' file1 file2


### Exclude Certain Files:

grep --exclude=*.log 'pattern' /path/to/directory/*


### Use Extended Regular Expressions:

grep -E 'pattern' file


### Suppress Errors for Non-Existent or Unreadable Files:

grep -s 'pattern' file


### Print n Lines of Context Around Matches:

Before matches:

```grep -B n 'pattern' file```


### After matches:

```grep -A n 'pattern' file```


### Both before and after matches:

```grep -C n 'pattern' file```


### Only ow File Names (No Duplicate Names):

grep -L 'pattern' file1 file2

