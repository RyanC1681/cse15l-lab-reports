cse15L lab reports inital file
==============================
Author: Ryan C

test code
----------
```
java.util.Scanner;

boolean test;
String x = "original string";
String testCheck = "";

Scanner input = new Scanner(System.in);

System.out.println("test? (y/n)");
input.next().charAt (0);

if (input == 'y')
{
  test = true
}

else
{
  test = false;
  System.out.println("test not executed");
  return;
}


if (test)
{
  x = "new string";
  System.out.println(x);
  testCheck = x;
  
  if (testCheck.equals(x))
  {
    System.out.println("test sucessful");
  }
  
  else
  {
    System.out.println("test failed");
  }
}

```


