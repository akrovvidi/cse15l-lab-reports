# Researching Commands 

The command I chose to research for this lab is the "grep" command. The grep argument is a command-line function that searches for a string in a group of files. 

## The first instance of grep method: 

This instance goes like:
```
grep "name" "path"

```
Now implementing this in the written_2 directory:

```
grep "ch4.txt" find-results.txt
```
This command above will print the file with the name "ch4.txt" that resides in find-results.txt The results of this command can be seen below:

```
written_2//non-fiction/OUP/Kauffman/ch4.txt
```

Another instance of the grep method can be seen below:

```
grep "amsterdam" written_2/*/*/*.txt
```
This command searches for the string, "amsterdam" in the written_2 directory and returns the files where the string "amsterdam" is present and the sentence that contains it.  
```
written_2/travel_guides/berlitz2/Algarve-WhatToDo.txt:amsterdam for Children
written_2/travel_guides/berlitz2/Amsterdam-WhatToDo.txt:amsterdam for Children
```

## Second Instance of grep

The "grep-l" command works in a similar way to the grep command in that it also searches for specified patterns in text files. The "-l" is used to display the names of the files that contains the specified string pattern. To make this more clear, look at the example below:

Command
```
grep -l "Soccer" written_2/*/*/*.txt
```

Output
```
written_2/travel_guides/berlitz2/Algarve-WhatToDo.txt
written_2/travel_guides/berlitz2/Amsterdam-WhatToDo.txt
written_2/travel_guides/berlitz2/Berlin-WhatToDo.txt
written_2/travel_guides/berlitz2/Berlin-WhereToGo.txt
written_2/travel_guides/berlitz2/Portugal-WhatToDo.txt
```

The output just prints all the files in the written_2 directory that contains the string "Soccer". 

## The Third instance of grep method

The next command we will be looking at is "grep-n". The "-n" displays the line number for each match and displays the matching text. The example below will make it more clear. 


```
grep -n "Benfica" written_2/*/*/*.txt
```
```
written_2/travel_guides/berlitz2/Portugal-WhatToDo.txt:48:Soccer (football). As in most European countries, futébol draws big crowds in Portugal. Lisbon’s two major teams are Benfica and Sporting Clube de Portugal. FC Porto is the top club in Portugal’s second city. The Algarve has a team in Farense, from the regional capital. Check with local tourism offices for a schedule of matches.
```

## The fourth instance of grep method

The fourth and final instance of the grep command for this lab report is "grep --color" which just highlights the selected text in a different color. 
```
grep --color "Benfica" written_2/*/*/*.txt
```
Output
```
written_2/travel_guides/berlitz2/Portugal-WhatToDo.txt:Soccer (football). As in most European countries, futébol draws big crowds in Portugal. Lisbon’s two major teams are Benfica and Sporting Clube de Portugal. FC Porto is the top club in Portugal’s second city. The Algarve has a team in Farense, from the regional capital. Check with local tourism offices for a schedule of matches.
```
This command highlights Benfica in a color and displays the file that contains the string "Benfica"
