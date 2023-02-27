Lab Report 4
---------------------

ieng6 Login
--------------------------
```
Using local bash history
<up> <Enter>
```

![ieng6Login](https://user-images.githubusercontent.com/40802485/221347128-62d76f50-8f1d-46b8-98eb-ec9cb35fa4f6.jpg)


Cloning fork of the lab7 Repository
--------------------------------------
```
<Ctrl + R> git cl <Tab> <Enter>
cd l <Tab><Enter>
```

![github cloning](https://user-images.githubusercontent.com/40802485/221347145-3a0e7124-b568-45e1-b923-7d621a23983d.jpg)


Running Tests for Failure
-----------------------------
```
Compiling all files:
<Ctrl + R> <Ctrl + V or Rclick> (paste in “javac”) * <Tab> <Enter>

Compiling and running Junit tests:
<Ctrl + R> <Ctrl + V or Rclick> (paste in “javac”) - <Tab> <Enter>
<Ctrl + R> <Ctrl + V or Rclick> (paste in “javac”) <backspace> <Tab> <Enter>
```

![java tests1-1](https://user-images.githubusercontent.com/40802485/221347188-b5fa54c2-26d8-46c8-8868-c38b693d281e.jpg)
![java tests1-2](https://user-images.githubusercontent.com/40802485/221347192-79fc6438-f65a-4d30-abe4-e5ee55a69b80.jpg)


Fixing Failure-Causing Error
----------------------------

```
vim L <Tab> <Enter>
i (insert mode)
<click on last instance of index1, line 43 13th index>
<backspace> 2
<ESC> :wq <Enter>
```

![vim](https://user-images.githubusercontent.com/40802485/221347205-d8d96f11-71cb-46be-ba35-a1911859cb88.jpg)
![vimFixError](https://user-images.githubusercontent.com/40802485/221347208-c80a2be1-1127-4108-943a-0e77ce473ed5.jpg)

Running Tests Checking for Error Fix
-----------------------------------

```
<up> <up> <Enter>
<up> <up> <Enter>
```

![java tests2](https://user-images.githubusercontent.com/40802485/221347217-802f1588-995a-4e10-bcdd-6dbf897b6732.jpg)


Committing and Pushing to Github
-------------------------------------
```
<Ctrl + R> <Ctrl + V or Rclick> (paste in “git”) a  <Tab> <Enter>
<Ctrl + R> <Ctrl + V or Rclick> (paste in “git”) c <Tab> <Enter>
<Ctrl + R> <Ctrl + V or Rclick> (paste in “git”) p <Tab> <Enter>
```

![git add](https://user-images.githubusercontent.com/40802485/221347222-2642a303-10d2-4329-86cf-04df5e69687d.jpg)
![git commitPush](https://user-images.githubusercontent.com/40802485/221347227-bceaec64-3fb3-4693-a0be-05a5b7b5d985.jpg)
![git commitPush](https://user-images.githubusercontent.com/40802485/221681422-d5f75007-0d7d-4b68-bcdd-24e9112ff446.jpg)


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
  change "index1" to "index2" on line 43 in the last while loop
  :wq (vim save and close)

7. javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java  

8. java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore 

9. git add ListExamples.java 

10. git commit -m "fixed ListExamples bug"

11. git push origin main
```

[Website link to Lab 4](https://ryanc1681.github.io/cse15l-lab-reports/LabReport4.html)
