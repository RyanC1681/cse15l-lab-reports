Lab Report 3: Variations of the `grep` Command
================================================

Non case-sensitive Search of Terms
----------------------------------
In the skill-demo1-data directory, execute the command `find ./written_2 -name WhatToJapan` to find the path to the file. Use `cd written_2/travel_guides/berlitz1` to move into the path that was found. The command `cat WhatToJapan.txt | grep  "tourist"`will find String matches of the word within the file, but would only strictly search for the exact String with all lowercase characters. The addition of “-i” to the command, `cat WhatToJapan.txt | grep -i  "tourist"`
allows grep to return both matches to upper and lowercase terms found in the file.

Normal search for term:
![nonCaseSensitive2](https://user-images.githubusercontent.com/40802485/218427945-a19d7da5-3ff7-4e72-b087-55f9ed549f2a.jpg)

inclusion of upper and lowercase terms in search
![nonCaseSensitive1](https://user-images.githubusercontent.com/40802485/218427920-059610a4-228b-4f27-8d46-2a4ff1cc5eba.jpg)


