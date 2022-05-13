# Here are a list of commands I have learnt 

- `ls` : list items command 

`$ ls /Documents`

- to shutdown system

`$ shutdown -h now`
-- shutdown -h( halt ) now

- to `cp` a file from one to another. Be careful `cp` will overwrite a file if the destination file already exist.

USe `-i` flag if you want confirmation before executing a command.

- to know the numbe of text, characters and number of lines in a text file you can use `wc` - word count

- `ls -l` will list all items in a directory  with more information

- `ls -la` will list all items and hidden items in a directory  with more information
-  files starting with *d* are directories.

use `mv` to move an item one location to another.

Redirecting can be done with `>>` 
- you can create a new file by simply doing this:

`$ echo "I am a boy" >> boy.txt`

You can display a the content of a file by using the keyword `cat`.

`$ cat boy.txt`

Although cat is meant to concatenate of two files and print the out, but it does the job anyway.

`$ cat boy.txt text2.txt`

When displaying a file with large text, you can use the keyword `less`

`$ less large-text.txt`

`more` will do just like it says, a pageful