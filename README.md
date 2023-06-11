# Java-Expt-6
# Method Creation
# Aim:
To write a Java program to create a method to calculate power of a number raised to other.

# Algorithm
Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class called "Power" and create a method.

Step 3 : Create a main class,called the "Solution".

Step 4 : Calll the method from the Power class in Solution.

Step 5 : Display the result using Solution Class in the terminal.

# Program

import java.util.Scanner;<br>
class Power {<br>
public static void main(String[] args) {<br>
int base , powerRaised;<br>
Scanner s =new Scanner(System.in);<br>
System.out.println("Enter the Base value:");<br>
base=s.nextInt();<br>
System.out.println("Enter the value of power:");<br>
powerRaised=s.nextInt();<br>
int result = power(base, powerRaised);<br>
System.out.println(base + "^" + powerRaised + "=" + result);<br>
}<br>
public static int power(int base, int powerRaised) {<br>
if (powerRaised != 0) {<br>
// recursive call to power()<br>
return (base * power(base, powerRaised - 1));<br>
}<br>
else {<br>
return 1;<br>
}<br>
}<br>
}<br>

# Output
![image](https://github.com/Anuayshh/Java-Expt-6/assets/127651217/9f4947a0-9ece-45a5-b7b7-8552d14f7e87)


# Result
We have successfully created a Java program to calculate power of a number raised to other using method

