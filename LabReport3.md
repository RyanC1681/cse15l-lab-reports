Lab Report 3: Variations of the `grep` Command
================================================

intial path setup for examples
----------------------------------
![pathFinding](https://user-images.githubusercontent.com/40802485/218430135-d92de774-6d7c-4295-a8cc-f11747f80cd7.jpg)


Non case-sensitive Search of Terms
----------------------------------
In the skill-demo1-data directory, execute the command `find ./written_2 -name WhatToJapan` to find the path to the file. Use `cd written_2/travel_guides/berlitz1` to move into the path that was found. The command `cat WhatToJapan.txt | grep  "tourist"`will find String matches of the word within the file, but would only strictly search for the exact String with all lowercase characters. The addition of “-i” to the command, `cat WhatToJapan.txt | grep -i  "tourist"`
allows grep to return both matches to upper and lowercase terms found in the file.

Normal search for term:
![nonCaseSensitive2](https://user-images.githubusercontent.com/40802485/218427945-a19d7da5-3ff7-4e72-b087-55f9ed549f2a.jpg)

inclusion of upper and lowercase terms in search
![nonCaseSensitive1](https://user-images.githubusercontent.com/40802485/218427920-059610a4-228b-4f27-8d46-2a4ff1cc5eba.jpg)



non case sentitve 2
![nonCaseSensitive3](https://user-images.githubusercontent.com/40802485/218428814-371651ec-d114-4f7f-bc32-26c31494e898.jpg)


![nonCaseSensitive4](https://user-images.githubusercontent.com/40802485/218428824-dcb4734d-b5a1-4ba6-830a-ba1f3e57cbe1.jpg)


specific word
-----------------
examples

EX1 tourists
![findSingleWord](https://user-images.githubusercontent.com/40802485/218429597-7beb1f41-bc00-4a7b-b094-71690a63149e.jpg)


![findSingleWord-2](https://user-images.githubusercontent.com/40802485/218429642-76c46bf6-cc06-4c42-a54b-09b5d19dd941.jpg)

EX2 order
![findSingleWordEX2](https://user-images.githubusercontent.com/40802485/218429683-cde3944a-63b7-452a-9d74-de21ac1589b1.jpg)

![findSingleWordEX2-2](https://user-images.githubusercontent.com/40802485/218429713-488f6cc7-ce37-41e6-b8b2-fe0cbf875d14.jpg)


Recursive search
------------------
EX1
![grepRecursiveSearchN1](https://user-images.githubusercontent.com/40802485/218429849-c5e63d93-b5f5-429f-99fa-ece41fab74c1.jpg)

EX2
![grepRecursiveSearchN2](https://user-images.githubusercontent.com/40802485/218429907-5bddd9ab-513d-49bf-bdc2-30bfcbb8aeb4.jpg)


count frquency of term
--------------------------
EX1
![grepCounting](https://user-images.githubusercontent.com/40802485/218430000-f32d1bfc-ef2e-4c16-91bb-5ed400cdd0eb.jpg)

EX2
![grepCounting2](https://user-images.githubusercontent.com/40802485/218430056-4ac4582a-8b49-4abe-8db6-c82abb73a0ae.jpg)

