 Lab Report 5: Lab7 Bash File
=====================================

Run Commands
----------------------

ssh cs15lwi23(last three characters of username)@ieng6.ucsd.edu

bash runLab7.sh
```


runLab7.sh
—----------------------

git clone git@github.com:RyanC1681/lab7.git

javac *.java

javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java 

java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples

vim ListExamples.java
  i (vim insertion)
  change "index1" to "index2" on line 43 in the last while loop
  :wq (vim save and close)

javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java  

java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore 

git add ListExamples.java 

git commit -m "fixed ListExamples bug"

git push origin main
```

Result ListExamples.java 



![lab5 1](https://user-images.githubusercontent.com/40802485/224199103-6fab3660-d321-4f16-a1a8-346df04ec46f.jpg)

![lab5 2](https://user-images.githubusercontent.com/40802485/224200285-26c12e6e-ff11-4845-aff1-dbbecc1b797f.jpg)

![lab5 3](https://user-images.githubusercontent.com/40802485/224200350-d28c2c99-0220-4706-8373-e77e3219d1d0.jpg)

![lab5 4](https://user-images.githubusercontent.com/40802485/224200387-e08929a7-a169-4354-abd9-3846975724c5.jpg)

First test needs to fail:

![lab5 5](https://user-images.githubusercontent.com/40802485/224200564-3de78ee2-d162-41b5-9073-b01a8589cc11.jpg)

1. ssh cs15lwi23(last three characters of username)@ieng6.ucsd.edu

2. git clone git@github.com:RyanC1681/lab7.git

3. javac *.java

4. javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java 

5. java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples

6. vim ListExamples.java
  i (vim insertion)
  change "index1" to "index2" on line 43 in the last while loop
  :wq (vim save and close)

7. javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java  

8. java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore 

9. git add ListExamples.java 

10. git commit -m "fixed ListExamples bug"

11. git push origin main

[Visit CSE 15L Lab Report 5 website page](https://ryanc1681.github.io/cse15l-lab-reports/LabReport5.html)

