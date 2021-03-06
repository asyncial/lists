lists
=====
a simple reference implementation of a new way to store lists in the file system.

file system structure
---------------------
example:
```
$ tree -a
.
 shopping list                  -> folders as lists
    apples                      -> files as list items
    bananas
    eggs
    milk
    .pie                        -> dotfiles as finished list items
 todo
     buy a boat
     get some stuff done
     .learn for the test
     visit parents
```
### advantages:
- simple navigation with standard unix tools
- platform compatible
- easily usable even without any special tools
- room for comments, notes or more sophisticated informations(JSON ?) in the list items/files themselves
- easily extendable
- should be simple enough to parse it for usage with different languages, platform and so on
- can be synced via dropbox or similar, or even git/VCS

### DONE:
- create list folder
- create new list
- create new list item
- delete list
- delete list item
- show all lists
- show all unfinished list items of a specific list
- finish a list item
- show all list items
- show list items of a specific list
- show all unfinished list items
- edit list item content
- rename list item
- rename list
- a simple html representation of the whole thing

### TODO:
- man page
- bash/zsh completion
- maybe error handling
