QN 1 1.YES we can overload a method with same return type by changing the number of parameters.Take the case if we want to find the performance of student in 2 main subjects and suppose we want to find the total of other subjects also. In this case we can use two sum methods with different parameters and find the students' performance 2.If we overlad with different return type it will be confusing for the compiler to call which method 
import java.util.Scanner;
public class acad {
public static void main(String[] args) { 
Scanner in=new Scanner(System.in);//scanner used for getting input from user through keybaord 
System.out.println("Enter name"); 
String name=in.next(); 
System.out.println("Enter marks"); 
int n1=in.nextInt();//getting input at runtime 
int n2=in.nextInt();//getting input at runtime 
int n3=in.nextInt();
acad a=new acad();//creating object a to call non staic method sum inside static method acad a1=new acad(); a.sum(n1,n2);//calling the static method sum which accepts 2 parameters(n1,n2) 
a1.sum(n1,n2,n3);//calling the method which accepts 3 parameters
}
// Overloading – Different Number of parameters
public void sum(int a,int b) { int sum=a+b;
System.out.println("Sum of 2 main subject:"+sum);
} public void sum(int a,int b,int c) { int sum=a+b+c; System.out.println("Sum of 3 subjects(including optional subject):"+sum);

QN 2. Write a program in Java using Arrays, that sorts the element in a descending order.
import java.util.Arrays; 
import java.util.Scanner;
public class acad {
public static void main(String[] args) { 
Scanner in=new Scanner(System.in); 
System.out.println("Enter the no of elements in the array "); 
int x=in.nextInt(); 
int[] y=new int[n]; 
System.out.println("Enter the numbers"); 
for(int i=0;i=0;i--)
{ System.out.println(y[i]);
} } }

