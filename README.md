# Java Methods

## Method 1:

```java
public static void main(String args[]) {
    System.out.println("Hello World");
}
```
Answer: Valid
## Method 2:
```java
public String myMethod() {
    return "Something";
}
```
Answer: valid, missing modifier is ok, default as "instance".
## Method 3:
```java
public static int addNumbers(int x, int y) {
   System.out.println(x + y);
}
```
Answer: Invalid, the return type is not void, so it must have the return statement in the method body. 
## Method 4:
```java
public double subtractNums(double x, double y, double z) {
    return "The answer is : " + (x + y + z);
}
```
Answer: Invalid, return type is double, which mismatches the expression being returned. 
## Method 5:
```java
public static printMessage(String message) {
    System.out.println(message);
}
```
Answer: Invalid, missing return type. 
## Method 6:
```java
public static int() {
    return 5 + 5;
}
```
Answer: Invalid, missing return type and used the keyword as the name, or it missed the name.
## Method 7:
```java
public static int value(short num1, short num2) {
    int answer = num1 * num2;
    return answer;
}
```
Answer: Valid
## Bonus
Copy the 7 methods into a file named Methods.java and fix all the methods to make the code compile successfully. Submit your Methods.java file.

