# statements
# if(), elseif(), else(), and endif()

# Unary keywords are prefixed before the value
if(DEFINED MY_VAR)

# The unary keywords to be used in conditions are as follows
COMMAND: True if the supplied value is a command
EXISTS: Checks whether a file or a path exists
DEFINED: True if the value is a defined variable
# there are unary filesystem conditions: 
EXISTS: True if the passed file or directory exits
IS_DIRECTORY: Checks whether the supplied path is a directory
IS_SYMLINK: True if the supplied path is a symbolic link
IS_ABSOULTE: Checks whether a supplied path is an absolute path
Binary

# Binary tests compare two values
if(MYVAR STREQUAL "FOO")
# The binary operators are as follows:
LESS, GREATER, EQUAL, LESS_EQUAL, and GREATER_EQUAL: These compare numeric values

