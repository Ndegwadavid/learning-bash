## How to execute commands with back ticks
If you need to include the output of a complex command in your script, you can write the statement inside back ticks.

Syntax:
var= ` commands `

Example: Suppose we want to get the output of a list of mountpoints with tmpfs in their name. We can craft a statement like this: df -h | grep tmpfs.

To include it in the bash script, we can enclose it in back ticks.

#!/bin/bash

var=`df -h | grep tmpfs`
echo $var