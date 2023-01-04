# Coding exercise

Given the following file

``` csv
## categoryID,categoryName,isParent,hasChildren ##
11111,DVD_Movies,1,22222|55555
33333,Books_Magazines,1,0
33333,Video_Games,1,66666|77777
55555,Comedy,0,0
77777,Nintendo,0,0
33333,Electronics,1,0
22222,Action,0,0
66666,Playstation,0,0
```

Write a program that will read the file and print out the following:

``` yaml
DVD_Movies:
    - Comedy
    - Action
Books_Magazines: []
Video_Games:
    - Nintendo
    - Playstation
Electronics: []
```

Use any programing language you like. The program should be able to read any file with the same format and print out the same output.

You can use [https://www.onlinegdb.com](https://www.onlinegdb.com) to run your code online.

Push the finished code back into the repository in this directory.

## Bonus

Have the option to output in either json or yaml format.

##

Add the code you have written to this repo or send it via email to guillerb@amdocs.com 