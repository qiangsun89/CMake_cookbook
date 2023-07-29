set(MYLIST abc def ghi)
# set(MYLIST "abc;def;ghi")

# Manipulating lists by modifying their contents, reordering, 
# or finding things can be done using the list command

# The following code will query MYLIST for the index of the abc value and then retrieve the value and 
# store it in the variable called ABC

list(FIND MYLIST abc ABC_INDEX)
list(GET MYLIST ${ABC_INDEX} ABC)
