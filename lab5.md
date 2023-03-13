# *Lab Report 5*


For this final lab report, I will be following the format of my Lab Report 3, but instead of focusing on the "grep" command, I will be focusing on the "ls" command.

# What is the ls command?

In simple terms, it is a powerful tool in linux that enables practicioners to view all the all the files and directories in the current working directory. This command is especially useful for navigating file systems. 

## The first instance of "ls" command: 

This instance goes like:

```
ls --color

```

Now implementing the following method in written_2 directory produces the following output:

```
non-fiction  travel_guides
```

Another instance:

```
Algarve-History.txt      Bali-History.txt         Budapest-History.txt         China-WhereToGo.txt       NewOrleans-History.txt
Algarve-Intro.txt        Bali-WhatToDo.txt        Budapest-WhatToDo.txt        Costa-History.txt         Paris-WhatToDo.txt
Algarve-WhatToDo.txt     Bali-WhereToGo.txt       Budapest-WhereoGo.txt        Costa-WhatToDo.txt        Paris-WhereToGo.txt
Algarve-WhereToGo.txt    Barcelona-History.txt    California-History.txt       Costa-WhereToGo.txt       Poland-History.txt
Amsterdam-History.txt    Barcelona-WhatToDo.txt   California-WhatToDo.txt      CostaBlanca-History.txt   Poland-WhatToDo.txt
Amsterdam-Intro.txt      Barcelona-WhereToGo.txt  California-WhereToGo.txt     CostaBlanca-WhatToDo.txt  Portugal-History.txt
Amsterdam-WhatToDo.txt   Beijing-History.txt      Canada-History.txt           Crete-History.txt         Portugal-WhatToDo.txt
Amsterdam-WhereToGo.txt  Beijing-WhatToDo.txt     Canada-WhereToGo.txt         Crete-WhatToDo.txt        Portugal-WhereToGo.txt
Athens-History.txt       Beijing-WhereToGo.txt    CanaryIslands-History.txt    Crete-WhereToGo.txt       PuertoRico-History.txt
Athens-Intro.txt         Berlin-History.txt       CanaryIslands-WhatToDo.txt   CstaBlanca-WhereToGo.txt  PuertoRico-WhatToDo.txt
Athens-WhatToDo.txt      Berlin-WhatToDo.txt      CanaryIslands-WhereToGo.txt  Cuba-History.txt          PuertoRico-WhereToGo.txt
Athens-WhereToGo.txt     Berlin-WhereToGo.txt     Cancun-History.txt           Cuba-WhatToDo.txt         Vallarta-History.txt
Bahamas-History.txt      Bermuda-WhatToDo.txt     Cancun-WhatToDo.txt          Cuba-WhereToGo.txt        Vallarta-WhatToDo.txt
Bahamas-Intro.txt        Bermuda-WhereToGo.txt    Cancun-WhereToGo.txt         Nepal-History.txt         Vallarta-WhereToGo.txt
Bahamas-WhatToDo.txt     Bermuda-history.txt      China-History.txt            Nepal-WhatToDo.txt
Bahamas-WhereToGo.txt    Boston-WhereToGo.txt     China-WhatToDo.txt           Nepal-WhereToGo.txt
```

This above command was printed in GREEN as they are all executable files. 

The following command is basically used to display the output of the "ls" command in color. This color coding helps to differentiate between files and directories. As can be seen in the above examples, the directories are printed in blue while the executable files are printed in green. 

The sources I used for this command is chatGPT and the website below:

[ls commands Website](https://www.rapidtables.com/code/linux/ls.html)



## The second instance of "ls" command: 

Another way of using the "ls" command is:

```
ls -s

```

This command is useful to display the size of files and directories in the current working directory of a computer. Below, we can see some examples of how this method works: (*NOTE THAT ALL THESE EXAMPLES WERE DONE IN THE WRITTEN_2 DIRECTORY)


Output
```
total 16
8 berlitz1  8 berlitz2
```


Another Instance
```
total 3232
 16 Algarve-History.txt       20 Barcelona-WhatToDo.txt     16 CanaryIslands-History.txt     80 Cuba-WhereToGo.txt
  8 Algarve-Intro.txt         76 Barcelona-WhereToGo.txt    16 CanaryIslands-WhatToDo.txt    20 Nepal-History.txt
 16 Algarve-WhatToDo.txt      16 Beijing-History.txt        80 CanaryIslands-WhereToGo.txt   44 Nepal-WhatToDo.txt
 72 Algarve-WhereToGo.txt     28 Beijing-WhatToDo.txt       16 Cancun-History.txt            60 Nepal-WhereToGo.txt
 16 Amsterdam-History.txt     68 Beijing-WhereToGo.txt      20 Cancun-WhatToDo.txt           28 NewOrleans-History.txt
 12 Amsterdam-Intro.txt       28 Berlin-History.txt         72 Cancun-WhereToGo.txt          16 Paris-WhatToDo.txt
 16 Amsterdam-WhatToDo.txt    16 Berlin-WhatToDo.txt        36 China-History.txt             76 Paris-WhereToGo.txt
 64 Amsterdam-WhereToGo.txt   76 Berlin-WhereToGo.txt       16 China-WhatToDo.txt            20 Poland-History.txt
 28 Athens-History.txt        28 Bermuda-WhatToDo.txt      200 China-WhereToGo.txt           20 Poland-WhatToDo.txt
 12 Athens-Intro.txt          64 Bermuda-WhereToGo.txt      16 Costa-History.txt             16 Portugal-History.txt
 20 Athens-WhatToDo.txt       16 Bermuda-history.txt        16 Costa-WhatToDo.txt            20 Portugal-WhatToDo.txt
 76 Athens-WhereToGo.txt      76 Boston-WhereToGo.txt       76 Costa-WhereToGo.txt          124 Portugal-WhereToGo.txt
 20 Bahamas-History.txt       16 Budapest-History.txt       12 CostaBlanca-History.txt       16 PuertoRico-History.txt
 12 Bahamas-Intro.txt         20 Budapest-WhatToDo.txt      36 CostaBlanca-WhatToDo.txt      28 PuertoRico-WhatToDo.txt
 20 Bahamas-WhatToDo.txt      76 Budapest-WhereoGo.txt      16 Crete-History.txt             72 PuertoRico-WhereToGo.txt
 76 Bahamas-WhereToGo.txt     20 California-History.txt     20 Crete-WhatToDo.txt            16 Vallarta-History.txt
 20 Bali-History.txt          16 California-WhatToDo.txt    84 Crete-WhereToGo.txt           40 Vallarta-WhatToDo.txt
 20 Bali-WhatToDo.txt         76 California-WhereToGo.txt   52 CstaBlanca-WhereToGo.txt      56 Vallarta-WhereToGo.txt
 84 Bali-WhereToGo.txt        52 Canada-History.txt         12 Cuba-History.txt
 16 Barcelona-History.txt    236 Canada-WhereToGo.txt       20 Cuba-WhatToDo.txt
```

The total "16" and "3232" at the top of each of the outputs indicate that the size of all the files and directories are 16 and 3232 respectively.

The sources I used for this command is chatGPT and the website below:

[ls commands Website](https://www.rapidtables.com/code/linux/ls.html)


## The third instance of "ls" command: 

This instance goes like:

```
ls -S
```

It is similar to the previous command in that it relates to the sizes of the files, but instead of just printing the size it also sorts it for us. This will be especially useful in a situation for when we have to access the largest file in a give directory for instance. Below, we can see a couple of examples of the output when we run the command.

Output
```
berlitz1  berlitz2
```

Another instance
```
Canada-WhereToGo.txt         Bermuda-WhereToGo.txt     Barcelona-WhatToDo.txt      Bermuda-history.txt
China-WhereToGo.txt          Amsterdam-WhereToGo.txt   Nepal-History.txt           Costa-WhatToDo.txt
Portugal-WhereToGo.txt       Nepal-WhereToGo.txt       Cancun-WhatToDo.txt         Berlin-WhatToDo.txt
Crete-WhereToGo.txt          Vallarta-WhereToGo.txt    Bali-WhatToDo.txt           Portugal-History.txt
Bali-WhereToGo.txt           CstaBlanca-WhereToGo.txt  Cuba-WhatToDo.txt           Vallarta-History.txt
CanaryIslands-WhereToGo.txt  Canada-History.txt        Athens-WhatToDo.txt         CanaryIslands-History.txt
Cuba-WhereToGo.txt           Nepal-WhatToDo.txt        Portugal-WhatToDo.txt       Paris-WhatToDo.txt
Costa-WhereToGo.txt          Vallarta-WhatToDo.txt     Budapest-WhatToDo.txt       PuertoRico-History.txt
California-WhereToGo.txt     CostaBlanca-WhatToDo.txt  Bahamas-History.txt         Barcelona-History.txt
Budapest-WhereoGo.txt        China-History.txt         Crete-WhatToDo.txt          China-WhatToDo.txt
Bahamas-WhereToGo.txt        Bermuda-WhatToDo.txt      Bali-History.txt            Budapest-History.txt
Paris-WhereToGo.txt          Berlin-History.txt        California-WhatToDo.txt     Beijing-History.txt
Boston-WhereToGo.txt         Beijing-WhatToDo.txt      Costa-History.txt           CostaBlanca-History.txt
Barcelona-WhereToGo.txt      NewOrleans-History.txt    Algarve-WhatToDo.txt        Cuba-History.txt
Athens-WhereToGo.txt         PuertoRico-WhatToDo.txt   Amsterdam-WhatToDo.txt      Bahamas-Intro.txt
Berlin-WhereToGo.txt         Athens-History.txt        Crete-History.txt           Athens-Intro.txt
Algarve-WhereToGo.txt        Poland-History.txt        Amsterdam-History.txt       Amsterdam-Intro.txt
PuertoRico-WhereToGo.txt     Bahamas-WhatToDo.txt      CanaryIslands-WhatToDo.txt  Algarve-Intro.txt
Cancun-WhereToGo.txt         Poland-WhatToDo.txt       Algarve-History.txt
Beijing-WhereToGo.txt        California-History.txt    Cancun-History.txt
```

In the first example, both have the same size, hence on the same level. In the second example, these text files have various different sizes and from the output we can deduce that "Canada-WhereToGo.txt" is the text file with the largest size.

The sources I used for this command is chatGPT and the website below:

[ls commands Website](https://www.rapidtables.com/code/linux/ls.html)


## The fourth and final instance of "ls" command: 

This instance goes like:

```
ls -t
```

This command is used to sort the files and directories in the current working directory of a computer in order of modification time, with the more recent ones at the front. Below, we can see a couple of examples of the output when we run the command.

Output
```
berlitz2  berlitz1
```

Another instance
```
travel_guides  non-fiction
```

From the first example, we can deducde that "berlitz2" directory has been modifed more recently than "berlitz1" which is why it is listed earlier and in the second example, we can deduce that the "travel_guides" directory has been modified more recently than the "non-fiction" direcotry using similar reasoning. 

Therefore, this method proves extremely useful when we need to figure out files/directory that have been modified recently.

The sources I used for this command is chatGPT and the website below:

[ls commands Website](https://www.rapidtables.com/code/linux/ls.html)


# Vote Of Thanks

As this is the final lab report for the course, I would like to take this opporunity to thank the professor and all the TAs for their efforts in making this course seem smooth and reachable. I look forward to continuing to learn from you all in the future.

Aniruddh out.





