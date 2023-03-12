 [Lab Report 5: Lab7 Bash File ](https://ryanc1681.github.io/cse15l-lab-reports/LabReport5.html)
=====================================

Run Commands
----------------------

```
ssh cs15lwi23(last three characters of username)@ieng6.ucsd.edu

bash runLab7.sh
```

![lab5 1](https://user-images.githubusercontent.com/40802485/224199103-6fab3660-d321-4f16-a1a8-346df04ec46f.jpg)

![lab5 2](https://user-images.githubusercontent.com/40802485/224200285-26c12e6e-ff11-4845-aff1-dbbecc1b797f.jpg)


runLab7.sh Bash File
-----------------------
```
git clone git@github.com:RyanC1681/lab7.git

javac *.java

javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java 

java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples

#modify ListExamples to fix error
echo “modifying ListExamples”

sed -i ‘43 s/index1/index2/’ ListExamples.java

javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java  

java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore 

git add ListExamples.java 

git commit -m "fixed ListExamples bug"

git push origin main
```

![lab5 4](https://user-images.githubusercontent.com/40802485/224200387-e08929a7-a169-4354-abd9-3846975724c5.jpg)

Resulting ListExamples.java 
----------------------------

![lab5 3](https://user-images.githubusercontent.com/40802485/224200350-d28c2c99-0220-4706-8373-e77e3219d1d0.jpg)



[Visit CSE 15L Lab Report 5 website page](https://ryanc1681.github.io/cse15l-lab-reports/LabReport5.html)

