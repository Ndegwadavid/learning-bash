Using the find command
The find command helps to locate files based on certain patterns. As most of the scripts end with .sh, we can use the find script like this:

## find . -type f -name "*.sh"

Where,

. represents the current directory. You can change the path accordingly.
-type f indicates that the file type we are looking for is a text based file.
*.sh tells to match all files ending with .sh.