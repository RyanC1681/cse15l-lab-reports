Lab Report 4
---------------------

ieng6 Login
--------------------------
```
Using local bash history
<up> <Enter>
```
Cloning fork of the lab7 Repository
-------------------------
```
<Ctrl + R> git cl <Tab> <Enter>
cd l <Tab><Enter>
```

Running Tests for Failure
-------------------
```
Compiling all files:
<Ctrl + R> <Ctrl + V or Rclick> (paste in “javac”) * <Tab> <Enter>

Compiling and running Junit tests:
<Ctrl + R> <Ctrl + V or Rclick> (paste in “javac”) - <Tab> <Enter>
<Ctrl + R> <Ctrl + V or Rclick> (paste in “javac”) <backspace> <Tab> <Enter>
```
Fixing Failure-Causing Error
--------------------------
```
vim L <Tab> <Enter>
i (insert mode)
<click on last instance of index1, line 43 13th index>
<backspace> 2
<ESC> :wq <Enter>
```

Running Tests Checking for Error Fix
-----------------------------------
```
<up> <up> <Enter>
<up> <up> <Enter>
```

Committing and Pushing to Github
-------------------------------------
```
<Ctrl + R> <Ctrl + V or Rclick> (paste in “git”) a  <Tab> <Enter>
<Ctrl + R> <Ctrl + V or Rclick> (paste in “git”) c <Tab> <Enter>
<Ctrl + R> <Ctrl + V or Rclick> (paste in “git”) p <Tab> <Enter>
```

Full command List:
---------------------------
```
1. ssh cs15lwi23(last three characters of username)@ieng6.ucsd.edu

2. git clone git@github.com:RyanC1681/lab7.git

3. javac *.java

4. javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java 

5. java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples

6. vim ListExamples.java
  i (vim insertion)
  :wq (vim save and close)

7. javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java  

8. java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore 

9. git add ListExamples.java 

10. git commit -m "fixed ListExamples bug"

11. git push origin main
```
