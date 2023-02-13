# Researching Commands 

The command I chose to research for this lab is the "grep" command. The grep argument is a command-line function that searches for a string in a group of files. 

## The first instance of grep method: 

This instance goes like:

```
grep -c "String" path

```
Now implementing this in the written_2 directory:

Command
```
grep -c "war" written_2/*/*/*.txt
```
This command above will print all the text files in the written_2 directory along with an integer value displayed next to it that shows how many times the specified string("war") appears in each file. The results of this command can be seen below:

Output

```
written_2/travel_guides/berlitz1/HandRHawaii.txt:0
written_2/travel_guides/berlitz1/HandRHongKong.txt:0
written_2/travel_guides/berlitz1/HandRIbiza.txt:0
written_2/travel_guides/berlitz1/HandRIsrael.txt:2
written_2/travel_guides/berlitz1/HandRIstanbul.txt:0
written_2/travel_guides/berlitz1/HandRJamaica.txt:2
written_2/travel_guides/berlitz1/HandRJerusalem.txt:0
written_2/travel_guides/berlitz1/HandRLakeDistrict.txt:0
written_2/travel_guides/berlitz1/HandRLasVegas.txt:0
written_2/travel_guides/berlitz1/HandRLisbon.txt:0
written_2/travel_guides/berlitz1/HandRLosAngeles.txt:0
written_2/travel_guides/berlitz1/HandRMadeira.txt:0
written_2/travel_guides/berlitz1/HandRMadrid.txt:1
written_2/travel_guides/berlitz1/HandRMallorca.txt:1
written_2/travel_guides/berlitz1/HistoryDublin.txt:4
written_2/travel_guides/berlitz1/HistoryEdinburgh.txt:20
written_2/travel_guides/berlitz1/HistoryEgypt.txt:9
written_2/travel_guides/berlitz1/HistoryFWI.txt:7
written_2/travel_guides/berlitz1/HistoryFrance.txt:22
written_2/travel_guides/berlitz1/HistoryGreek.txt:11
written_2/travel_guides/berlitz1/HistoryHawaii.txt:6
written_2/travel_guides/berlitz1/HistoryHongKong.txt:3
written_2/travel_guides/berlitz1/HistoryIbiza.txt:7
written_2/travel_guides/berlitz1/HistoryIndia.txt:18
written_2/travel_guides/berlitz1/HistoryIsrael.txt:4
written_2/travel_guides/berlitz1/HistoryIstanbul.txt:9
written_2/travel_guides/berlitz1/HistoryItaly.txt:20
written_2/travel_guides/berlitz1/HistoryJamaica.txt:6
written_2/travel_guides/berlitz1/HistoryJapan copy.txt:41
written_2/travel_guides/berlitz1/HistoryJapan.txt:41
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:7
written_2/travel_guides/berlitz1/HistoryLakeDistrict.txt:2
written_2/travel_guides/berlitz1/HistoryLasVegas.txt:8
written_2/travel_guides/berlitz1/HistoryMadeira.txt:5
written_2/travel_guides/berlitz1/HistoryMadrid.txt:10
written_2/travel_guides/berlitz1/HistoryMalaysia.txt:16
written_2/travel_guides/berlitz1/HistoryMallorca.txt:11
written_2/travel_guides/berlitz1/IntroDublin.txt:1
written_2/travel_guides/berlitz1/IntroEdinburgh.txt:1
written_2/travel_guides/berlitz1/IntroEgypt.txt:2
written_2/travel_guides/berlitz1/IntroFWI.txt:1
written_2/travel_guides/berlitz1/IntroFrance.txt:1
written_2/travel_guides/berlitz1/IntroGreek.txt:5
written_2/travel_guides/berlitz1/IntroHongKong.txt:0
written_2/travel_guides/berlitz1/IntroIbiza.txt:2
written_2/travel_guides/berlitz1/IntroIndia.txt:2
written_2/travel_guides/berlitz1/IntroIsrael.txt:1
written_2/travel_guides/berlitz1/IntroIstanbul.txt:1
written_2/travel_guides/berlitz1/IntroItaly.txt:3
written_2/travel_guides/berlitz1/IntroJamaica.txt:2
written_2/travel_guides/berlitz1/IntroJapan.txt:12
written_2/travel_guides/berlitz1/IntroJerusalem.txt:0
written_2/travel_guides/berlitz1/IntroLakeDistrict.txt:4
written_2/travel_guides/berlitz1/IntroLasVegas.txt:3
written_2/travel_guides/berlitz1/IntroLosAngeles.txt:0
written_2/travel_guides/berlitz1/IntroMadeira.txt:3
written_2/travel_guides/berlitz1/IntroMadrid.txt:3
written_2/travel_guides/berlitz1/IntroMalaysia.txt:3
written_2/travel_guides/berlitz1/IntroMallorca.txt:1
written_2/travel_guides/berlitz1/JungleMalaysia.txt:0
written_2/travel_guides/berlitz1/WhatToDublin.txt:3
written_2/travel_guides/berlitz1/WhatToEdinburgh.txt:8
written_2/travel_guides/berlitz1/WhatToEgypt.txt:3
written_2/travel_guides/berlitz1/WhatToFWI.txt:1
written_2/travel_guides/berlitz1/WhatToFrance.txt:0
written_2/travel_guides/berlitz1/WhatToGreek.txt:2
written_2/travel_guides/berlitz1/WhatToHawaii.txt:1
written_2/travel_guides/berlitz1/WhatToHongKong.txt:2
written_2/travel_guides/berlitz1/WhatToIbiza.txt:6
written_2/travel_guides/berlitz1/WhatToIndia.txt:6
written_2/travel_guides/berlitz1/WhatToIsrael.txt:8
written_2/travel_guides/berlitz1/WhatToIstanbul.txt:7
written_2/travel_guides/berlitz1/WhatToItaly.txt:8
written_2/travel_guides/berlitz1/WhatToJamaica.txt:17
written_2/travel_guides/berlitz1/WhatToJapan.txt:15
written_2/travel_guides/berlitz1/WhatToLakeDistrict.txt:3
written_2/travel_guides/berlitz1/WhatToLasVegas.txt:7
written_2/travel_guides/berlitz1/WhatToLosAngeles.txt:3
written_2/travel_guides/berlitz1/WhatToMadeira.txt:4
written_2/travel_guides/berlitz1/WhatToMalaysia.txt:5
written_2/travel_guides/berlitz1/WhatToMallorca.txt:2
written_2/travel_guides/berlitz1/WhereToDublin.txt:14
written_2/travel_guides/berlitz1/WhereToEdinburgh.txt:13
written_2/travel_guides/berlitz1/WhereToEgypt.txt:17
written_2/travel_guides/berlitz1/WhereToFWI.txt:21
written_2/travel_guides/berlitz1/WhereToFrance.txt:38
written_2/travel_guides/berlitz1/WhereToGreek.txt:12
written_2/travel_guides/berlitz1/WhereToHawaii.txt:0
written_2/travel_guides/berlitz1/WhereToHongKong.txt:15
written_2/travel_guides/berlitz1/WhereToIbiza.txt:13
written_2/travel_guides/berlitz1/WhereToIndia.txt:42
written_2/travel_guides/berlitz1/WhereToIsrael.txt:7
written_2/travel_guides/berlitz1/WhereToIstanbul.txt:9
written_2/travel_guides/berlitz1/WhereToItaly.txt:36
written_2/travel_guides/berlitz1/WhereToJapan.txt:58
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:19
written_2/travel_guides/berlitz1/WhereToLakeDistrict.txt:19
written_2/travel_guides/berlitz1/WhereToLosAngeles.txt:7
written_2/travel_guides/berlitz1/WhereToMadeira.txt:23
written_2/travel_guides/berlitz1/WhereToMadrid.txt:12
written_2/travel_guides/berlitz1/WhereToMalaysia.txt:55
written_2/travel_guides/berlitz1/WhereToMallorca.txt:13
written_2/travel_guides/berlitz2/Algarve-History.txt:7
written_2/travel_guides/berlitz2/Algarve-Intro.txt:3
written_2/travel_guides/berlitz2/Algarve-WhatToDo.txt:2
written_2/travel_guides/berlitz2/Algarve-WhereToGo.txt:22
written_2/travel_guides/berlitz2/Amsterdam-History.txt:9
written_2/travel_guides/berlitz2/Amsterdam-Intro.txt:4
written_2/travel_guides/berlitz2/Amsterdam-WhatToDo.txt:2
written_2/travel_guides/berlitz2/Amsterdam-WhereToGo.txt:12
written_2/travel_guides/berlitz2/Athens-History.txt:12
written_2/travel_guides/berlitz2/Athens-Intro.txt:2
written_2/travel_guides/berlitz2/Athens-WhatToDo.txt:3
written_2/travel_guides/berlitz2/Athens-WhereToGo.txt:15
written_2/travel_guides/berlitz2/Bahamas-History.txt:9
written_2/travel_guides/berlitz2/Bahamas-Intro.txt:3
written_2/travel_guides/berlitz2/Bahamas-WhatToDo.txt:4
written_2/travel_guides/berlitz2/Bahamas-WhereToGo.txt:10
written_2/travel_guides/berlitz2/Bali-History.txt:4
written_2/travel_guides/berlitz2/Bali-WhatToDo.txt:5
written_2/travel_guides/berlitz2/Bali-WhereToGo.txt:22
written_2/travel_guides/berlitz2/Barcelona-History.txt:5
written_2/travel_guides/berlitz2/Barcelona-WhatToDo.txt:1
written_2/travel_guides/berlitz2/Barcelona-WhereToGo.txt:12
written_2/travel_guides/berlitz2/Beijing-History.txt:4
written_2/travel_guides/berlitz2/Beijing-WhatToDo.txt:4
written_2/travel_guides/berlitz2/Beijing-WhereToGo.txt:7
written_2/travel_guides/berlitz2/Berlin-History.txt:6
written_2/travel_guides/berlitz2/Berlin-WhatToDo.txt:1
written_2/travel_guides/berlitz2/Berlin-WhereToGo.txt:20
written_2/travel_guides/berlitz2/Bermuda-WhatToDo.txt:6
written_2/travel_guides/berlitz2/Bermuda-WhereToGo.txt:14
written_2/travel_guides/berlitz2/Bermuda-history.txt:5
written_2/travel_guides/berlitz2/Boston-WhereToGo.txt:15
written_2/travel_guides/berlitz2/Budapest-History.txt:10
written_2/travel_guides/berlitz2/Budapest-WhatToDo.txt:4
written_2/travel_guides/berlitz2/Budapest-WhereoGo.txt:13
written_2/travel_guides/berlitz2/California-History.txt:5
written_2/travel_guides/berlitz2/California-WhatToDo.txt:3
written_2/travel_guides/berlitz2/California-WhereToGo.txt:9
written_2/travel_guides/berlitz2/Canada-History.txt:16
written_2/travel_guides/berlitz2/Canada-WhereToGo.txt:61
written_2/travel_guides/berlitz2/CanaryIslands-History.txt:7
written_2/travel_guides/berlitz2/CanaryIslands-WhatToDo.txt:1
written_2/travel_guides/berlitz2/CanaryIslands-WhereToGo.txt:11
written_2/travel_guides/berlitz2/Cancun-History.txt:5
written_2/travel_guides/berlitz2/Cancun-WhatToDo.txt:8
written_2/travel_guides/berlitz2/Cancun-WhereToGo.txt:12
written_2/travel_guides/berlitz2/China-History.txt:7
written_2/travel_guides/berlitz2/China-WhatToDo.txt:5
written_2/travel_guides/berlitz2/China-WhereToGo.txt:43
written_2/travel_guides/berlitz2/Costa-History.txt:7
written_2/travel_guides/berlitz2/Costa-WhatToDo.txt:2
written_2/travel_guides/berlitz2/Costa-WhereToGo.txt:12
written_2/travel_guides/berlitz2/CostaBlanca-History.txt:7
written_2/travel_guides/berlitz2/CostaBlanca-WhatToDo.txt:7
written_2/travel_guides/berlitz2/Crete-History.txt:5
written_2/travel_guides/berlitz2/Crete-WhatToDo.txt:2
written_2/travel_guides/berlitz2/Crete-WhereToGo.txt:29
written_2/travel_guides/berlitz2/CstaBlanca-WhereToGo.txt:9
written_2/travel_guides/berlitz2/Cuba-History.txt:3
written_2/travel_guides/berlitz2/Cuba-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Cuba-WhereToGo.txt:17
written_2/travel_guides/berlitz2/Nepal-History.txt:3
written_2/travel_guides/berlitz2/Nepal-WhatToDo.txt:12
written_2/travel_guides/berlitz2/Nepal-WhereToGo.txt:19
written_2/travel_guides/berlitz2/NewOrleans-History.txt:9
written_2/travel_guides/berlitz2/Paris-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Paris-WhereToGo.txt:6
written_2/travel_guides/berlitz2/Poland-History.txt:10
written_2/travel_guides/berlitz2/Poland-WhatToDo.txt:5
written_2/travel_guides/berlitz2/Portugal-History.txt:3
written_2/travel_guides/berlitz2/Portugal-WhatToDo.txt:2
written_2/travel_guides/berlitz2/Portugal-WhereToGo.txt:28
written_2/travel_guides/berlitz2/PuertoRico-History.txt:5
written_2/travel_guides/berlitz2/PuertoRico-WhatToDo.txt:1
written_2/travel_guides/berlitz2/PuertoRico-WhereToGo.txt:24
written_2/travel_guides/berlitz2/Vallarta-History.txt:3
written_2/travel_guides/berlitz2/Vallarta-WhatToDo.txt:3
written_2/travel_guides/berlitz2/Vallarta-WhereToGo.txt:7
```

Another instance of the grep -c method can be seen below:

Command

```
grep -c "invade" written_2/*/*/*.txt
```
This command searches for the string, "invade" in the written_2 directory and returns all the files along with an integer value assigned to it to represent the number of times the string appears in those files. 

Output
```
written_2/travel_guides/berlitz1/HandRHawaii.txt:0
written_2/travel_guides/berlitz1/HandRHongKong.txt:0
written_2/travel_guides/berlitz1/HandRIbiza.txt:0
written_2/travel_guides/berlitz1/HandRIsrael.txt:0
written_2/travel_guides/berlitz1/HandRIstanbul.txt:0
written_2/travel_guides/berlitz1/HandRJamaica.txt:0
written_2/travel_guides/berlitz1/HandRJerusalem.txt:0
written_2/travel_guides/berlitz1/HandRLakeDistrict.txt:0
written_2/travel_guides/berlitz1/HandRLasVegas.txt:0
written_2/travel_guides/berlitz1/HandRLisbon.txt:0
written_2/travel_guides/berlitz1/HandRLosAngeles.txt:0
written_2/travel_guides/berlitz1/HandRMadeira.txt:0
written_2/travel_guides/berlitz1/HandRMadrid.txt:0
written_2/travel_guides/berlitz1/HandRMallorca.txt:0
written_2/travel_guides/berlitz1/HistoryDublin.txt:3
written_2/travel_guides/berlitz1/HistoryEdinburgh.txt:3
written_2/travel_guides/berlitz1/HistoryEgypt.txt:1
written_2/travel_guides/berlitz1/HistoryFWI.txt:0
written_2/travel_guides/berlitz1/HistoryFrance.txt:1
written_2/travel_guides/berlitz1/HistoryGreek.txt:3
written_2/travel_guides/berlitz1/HistoryHawaii.txt:0
written_2/travel_guides/berlitz1/HistoryHongKong.txt:1
written_2/travel_guides/berlitz1/HistoryIbiza.txt:3
written_2/travel_guides/berlitz1/HistoryIndia.txt:9
written_2/travel_guides/berlitz1/HistoryIsrael.txt:3
written_2/travel_guides/berlitz1/HistoryIstanbul.txt:5
written_2/travel_guides/berlitz1/HistoryItaly.txt:7
written_2/travel_guides/berlitz1/HistoryJamaica.txt:0
written_2/travel_guides/berlitz1/HistoryJapan copy.txt:0
written_2/travel_guides/berlitz1/HistoryJapan.txt:0
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:1
written_2/travel_guides/berlitz1/HistoryLakeDistrict.txt:1
written_2/travel_guides/berlitz1/HistoryLasVegas.txt:0
written_2/travel_guides/berlitz1/HistoryMadeira.txt:0
written_2/travel_guides/berlitz1/HistoryMadrid.txt:2
written_2/travel_guides/berlitz1/HistoryMalaysia.txt:1
written_2/travel_guides/berlitz1/HistoryMallorca.txt:0
written_2/travel_guides/berlitz1/IntroDublin.txt:0
written_2/travel_guides/berlitz1/IntroEdinburgh.txt:0
written_2/travel_guides/berlitz1/IntroEgypt.txt:0
written_2/travel_guides/berlitz1/IntroFWI.txt:0
written_2/travel_guides/berlitz1/IntroFrance.txt:0
written_2/travel_guides/berlitz1/IntroGreek.txt:0
written_2/travel_guides/berlitz1/IntroHongKong.txt:0
written_2/travel_guides/berlitz1/IntroIbiza.txt:0
written_2/travel_guides/berlitz1/IntroIndia.txt:0
written_2/travel_guides/berlitz1/IntroIsrael.txt:0
written_2/travel_guides/berlitz1/IntroIstanbul.txt:0
written_2/travel_guides/berlitz1/IntroItaly.txt:0
written_2/travel_guides/berlitz1/IntroJamaica.txt:0
written_2/travel_guides/berlitz1/IntroJapan.txt:0
written_2/travel_guides/berlitz1/IntroJerusalem.txt:0
written_2/travel_guides/berlitz1/IntroLakeDistrict.txt:0
written_2/travel_guides/berlitz1/IntroLasVegas.txt:0
written_2/travel_guides/berlitz1/IntroLosAngeles.txt:0
written_2/travel_guides/berlitz1/IntroMadeira.txt:1
written_2/travel_guides/berlitz1/IntroMadrid.txt:0
written_2/travel_guides/berlitz1/IntroMalaysia.txt:0
written_2/travel_guides/berlitz1/IntroMallorca.txt:2
written_2/travel_guides/berlitz1/JungleMalaysia.txt:0
written_2/travel_guides/berlitz1/WhatToDublin.txt:0
written_2/travel_guides/berlitz1/WhatToEdinburgh.txt:0
written_2/travel_guides/berlitz1/WhatToEgypt.txt:0
written_2/travel_guides/berlitz1/WhatToFWI.txt:0
written_2/travel_guides/berlitz1/WhatToFrance.txt:0
written_2/travel_guides/berlitz1/WhatToGreek.txt:0
written_2/travel_guides/berlitz1/WhatToHawaii.txt:0
written_2/travel_guides/berlitz1/WhatToHongKong.txt:0
written_2/travel_guides/berlitz1/WhatToIbiza.txt:0
written_2/travel_guides/berlitz1/WhatToIndia.txt:0
written_2/travel_guides/berlitz1/WhatToIsrael.txt:0
written_2/travel_guides/berlitz1/WhatToIstanbul.txt:0
written_2/travel_guides/berlitz1/WhatToItaly.txt:0
written_2/travel_guides/berlitz1/WhatToJamaica.txt:0
written_2/travel_guides/berlitz1/WhatToJapan.txt:0
written_2/travel_guides/berlitz1/WhatToLakeDistrict.txt:0
written_2/travel_guides/berlitz1/WhatToLasVegas.txt:0
written_2/travel_guides/berlitz1/WhatToLosAngeles.txt:0
written_2/travel_guides/berlitz1/WhatToMadeira.txt:0
written_2/travel_guides/berlitz1/WhatToMalaysia.txt:0
written_2/travel_guides/berlitz1/WhatToMallorca.txt:0
written_2/travel_guides/berlitz1/WhereToDublin.txt:0
written_2/travel_guides/berlitz1/WhereToEdinburgh.txt:1
written_2/travel_guides/berlitz1/WhereToEgypt.txt:1
written_2/travel_guides/berlitz1/WhereToFWI.txt:2
written_2/travel_guides/berlitz1/WhereToFrance.txt:4
written_2/travel_guides/berlitz1/WhereToGreek.txt:1
written_2/travel_guides/berlitz1/WhereToHawaii.txt:0
written_2/travel_guides/berlitz1/WhereToHongKong.txt:0
written_2/travel_guides/berlitz1/WhereToIbiza.txt:0
written_2/travel_guides/berlitz1/WhereToIndia.txt:5
written_2/travel_guides/berlitz1/WhereToIsrael.txt:0
written_2/travel_guides/berlitz1/WhereToIstanbul.txt:0
written_2/travel_guides/berlitz1/WhereToItaly.txt:1
written_2/travel_guides/berlitz1/WhereToJapan.txt:0
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:1
written_2/travel_guides/berlitz1/WhereToLakeDistrict.txt:0
written_2/travel_guides/berlitz1/WhereToLosAngeles.txt:0
written_2/travel_guides/berlitz1/WhereToMadeira.txt:0
written_2/travel_guides/berlitz1/WhereToMadrid.txt:0
written_2/travel_guides/berlitz1/WhereToMalaysia.txt:2
written_2/travel_guides/berlitz1/WhereToMallorca.txt:0
written_2/travel_guides/berlitz2/Algarve-History.txt:1
written_2/travel_guides/berlitz2/Algarve-Intro.txt:0
written_2/travel_guides/berlitz2/Algarve-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Algarve-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Amsterdam-History.txt:0
written_2/travel_guides/berlitz2/Amsterdam-Intro.txt:0
written_2/travel_guides/berlitz2/Amsterdam-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Amsterdam-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Athens-History.txt:2
written_2/travel_guides/berlitz2/Athens-Intro.txt:0
written_2/travel_guides/berlitz2/Athens-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Athens-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Bahamas-History.txt:1
written_2/travel_guides/berlitz2/Bahamas-Intro.txt:0
written_2/travel_guides/berlitz2/Bahamas-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Bahamas-WhereToGo.txt:1
written_2/travel_guides/berlitz2/Bali-History.txt:4
written_2/travel_guides/berlitz2/Bali-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Bali-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Barcelona-History.txt:1
written_2/travel_guides/berlitz2/Barcelona-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Barcelona-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Beijing-History.txt:4
written_2/travel_guides/berlitz2/Beijing-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Beijing-WhereToGo.txt:2
written_2/travel_guides/berlitz2/Berlin-History.txt:1
written_2/travel_guides/berlitz2/Berlin-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Berlin-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Bermuda-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Bermuda-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Bermuda-history.txt:0
written_2/travel_guides/berlitz2/Boston-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Budapest-History.txt:0
written_2/travel_guides/berlitz2/Budapest-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Budapest-WhereoGo.txt:1
written_2/travel_guides/berlitz2/California-History.txt:0
written_2/travel_guides/berlitz2/California-WhatToDo.txt:0
written_2/travel_guides/berlitz2/California-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Canada-History.txt:1
written_2/travel_guides/berlitz2/Canada-WhereToGo.txt:1
written_2/travel_guides/berlitz2/CanaryIslands-History.txt:0
written_2/travel_guides/berlitz2/CanaryIslands-WhatToDo.txt:0
written_2/travel_guides/berlitz2/CanaryIslands-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Cancun-History.txt:1
written_2/travel_guides/berlitz2/Cancun-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Cancun-WhereToGo.txt:0
written_2/travel_guides/berlitz2/China-History.txt:4
written_2/travel_guides/berlitz2/China-WhatToDo.txt:0
written_2/travel_guides/berlitz2/China-WhereToGo.txt:1
written_2/travel_guides/berlitz2/Costa-History.txt:2
written_2/travel_guides/berlitz2/Costa-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Costa-WhereToGo.txt:1
written_2/travel_guides/berlitz2/CostaBlanca-History.txt:1
written_2/travel_guides/berlitz2/CostaBlanca-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Crete-History.txt:4
written_2/travel_guides/berlitz2/Crete-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Crete-WhereToGo.txt:0
written_2/travel_guides/berlitz2/CstaBlanca-WhereToGo.txt:1
written_2/travel_guides/berlitz2/Cuba-History.txt:1
written_2/travel_guides/berlitz2/Cuba-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Cuba-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Nepal-History.txt:1
written_2/travel_guides/berlitz2/Nepal-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Nepal-WhereToGo.txt:0
written_2/travel_guides/berlitz2/NewOrleans-History.txt:0
written_2/travel_guides/berlitz2/Paris-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Paris-WhereToGo.txt:1
written_2/travel_guides/berlitz2/Poland-History.txt:7
written_2/travel_guides/berlitz2/Poland-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Portugal-History.txt:3
written_2/travel_guides/berlitz2/Portugal-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Portugal-WhereToGo.txt:2
written_2/travel_guides/berlitz2/PuertoRico-History.txt:0
written_2/travel_guides/berlitz2/PuertoRico-WhatToDo.txt:0
written_2/travel_guides/berlitz2/PuertoRico-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Vallarta-History.txt:0
written_2/travel_guides/berlitz2/Vallarta-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Vallarta-WhereToGo.txt:0
```

This command could be useful when you want a quick count of the number of occurrences of a string pattern, without having to view the full contents of the matching lines. The source for this command is the youtube video below.

[Grep commands Video](https://www.youtube.com/watch?v=EQLFr8uC44k&ab_channel=FactorPad)


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

Another instance can be seen below

Command

```
grep -l "bharat" written_2/*/*/*.txt
```

Output
```
written_2/travel_guides/berlitz1/HistoryIndia.txt
written_2/travel_guides/berlitz1/HistoryMalaysia.txt
written_2/travel_guides/berlitz1/WhereToIndia.txt
written_2/travel_guides/berlitz2/Nepal-History.txt
written_2/travel_guides/berlitz2/Nepal-WhereToGo.txt
```
This option can be useful when you want to find which files contain a specific piece of information, without having to view the contents of each file. The source I used for this command is the youtube video below:


[Grep commands Video](https://www.youtube.com/watch?v=EQLFr8uC44k&ab_channel=FactorPad)

## The Third instance of grep method

The next command we will be looking at is "grep-n". The "-n" displays the line number for each match and displays the matching text. The example below will make it more clear. 

Command

```
grep -n "Benfica" written_2/*/*/*.txt
```

Output
```
written_2/travel_guides/berlitz2/Portugal-WhatToDo.txt:48:Soccer (football). As in most European countries, futébol draws big crowds in Portugal. Lisbon’s two major teams are Benfica and Sporting Clube de Portugal. FC Porto is the top club in Portugal’s second city. The Algarve has a team in Farense, from the regional capital. Check with local tourism offices for a schedule of matches.
```

Another instance

Command
```
grep -n "Lucayans" written_2/*/*/*.txt
```

Output
```
written_2/travel_guides/berlitz2/Bahamas-History.txt:6:Centuries before the arrival of Columbus, a peaceful Amerindian people who called themselves the Luccucairi had settled in the Bahamas. Originally from South America, they had traveled up through the Caribbean islands, surviving by cultivating modest crops and from what they caught from sea and shore. Nothing in the experience of these gentle people could have prepared them for the arrival of the Pinta, the Niña, and the Santa Maria at San Salvador on 12 October 1492. Columbus believed that he had reached the East Indies and mistakenly called these people Indians. We know them today as the Lucayans. Columbus claimed the island and others in the Bahamas for his royal Spanish patrons, but not finding the gold and other riches he was seeking, he stayed for only two weeks before sailing towards Cuba.
written_2/travel_guides/berlitz2/Bahamas-History.txt:7:The Spaniards never bothered to settle in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports. On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which was used to replenish the supplies of water on their ships before they began the long journey back to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.
```
This option can be useful when you want to quickly locate the exact location of a specific piece of information within a file. The source I used for this command is the youtube video below


[Grep commands Video](https://www.youtube.com/watch?v=EQLFr8uC44k&ab_channel=FactorPad)


## The fourth instance of grep method

The fourth and final instance of the grep command for this lab report is "grep --color" which just highlights the selected text in a different color. 

Command
```
grep --color "Benfica" written_2/*/*/*.txt
```
Output
```
written_2/travel_guides/berlitz2/Portugal-WhatToDo.txt:Soccer (football). As in most European countries, futébol draws big crowds in Portugal. Lisbon’s two major teams are Benfica and Sporting Clube de Portugal. FC Porto is the top club in Portugal’s second city. The Algarve has a team in Farense, from the regional capital. Check with local tourism offices for a schedule of matches.
```

This command highlights Benfica in a color and displays the file that contains the string "Benfica"

Another instance of the grep --color method can be seen below.

Command
```
grep --color "Hispaniola" written_2/*/*/*.txt
```
 Output 
 ```
written_2/travel_guides/berlitz1/HistoryJamaica.txt:        of the Spanish. They were repulsed at Hispaniola by a strong Spanish
written_2/travel_guides/berlitz2/Bahamas-History.txt:The Spaniards never bothered to settle in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports. On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which was used to replenish the supplies of water on their ships before they began the long journey back to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.
written_2/travel_guides/berlitz2/Cuba-History.txt:In 1511 Diego de Velázquez sailed from neighboring Hispaniola with some 300 conquistadores (conquerors). Baracoa became the first of seven settlements across Cuba. Velázquez and his followers enslaved the native peoples and in the process exposed them to European diseases. Whole villages committed suicide, and by the mid-1500s the Indian population had declined from over 100,000 to 3,000.
```

Note that in the terminal, "Hispaniola" is printed in color which cannot be seen in the code block above. This option can be useful when you want to quickly identify the matching lines within a file, especially when you are working with large files with many lines of text. 
The sources I used for this command is chatGPT and the youtube video below:

[Grep commands Video](https://www.youtube.com/watch?v=EQLFr8uC44k&ab_channel=FactorPad)

 
