# lab-task2
//Q#1 Write a java program that declare the 5 floating number and calculate it sum and //the average?
class Hello{
public static void main(String [] args){
float num1=2.03f;
float num2=9.88f;
float num3=1.45f;
float num4=7.67f;
float num5=5.033f;
float sum,average;
sum=num1+num2+num3+num4+num5;
average=(sum)/5;
System.out.println("sum of numbers:" +sum);
System.out.println("Average of the numbers:"+average);
}
}


//Q#2 write a java code that define the radius of circle and print the circumference, diameter //and the area of circle??
class Hello{
public static void main(String [] args){
double radius=2.8;
double circumference,area,diameter;
circumference=2*3.142*radius;
area=3.142*radius*radius;
diameter=2*radius;
System.out.println("circumference of circle is:"+circumference);
System.out.println("area of the circle is:"+area);
System.out.println("diameter of the circle:"+diameter);
}}

//Q#3 write a java program that takes an amount as runtime argument and prints the number of bills and coins it will take to complete that amount
For example if the user enters Rs 5843. Then the output should look like this?
RS 5000=1;
Rs 1000=0;
Rs 500=1;
Rs 100=3;
Rs 50=0;
Rs 20=2;
Rs 10=0;
Rs 2=1;
RS 1=1;
*/
import java.util.Scanner;
class Hello{
public static void main(String []args){
Scanner s= new Scanner(System.in);
System.out.print("enter the amount: ");
int amount=s.nextInt();
int note_of_5000;
int note_of_1000;
int note_of_500;
int note_of_100;
int note_of_50;
int note_of_20;
int note_of_10;
int note_of_2;
int note_of_1;

 note_of_5000=amount/5000;
amount=amount%5000;
System.out.println("note of 5000: "+note_of_5000);
note_of_1000=amount/1000;
amount=amount%1000;
System.out.println("note of 1000: "+note_of_1000);
note_of_500=amount/500;
amount=amount%500;
System.out.println("note of 500: "+note_of_500);
note_of_100=amount/100;
amount=amount%100;
System.out.println("note of 100: "+note_of_100);
note_of_50=amount/50;
amount=amount%50;
System.out.println("note of 50: "+note_of_50);
note_of_20=amount/20;
amount=amount%20;
System.out.println("note of 20: "+note_of_20);
note_of_10=amount/10;
amount=amount%10;
System.out.println("note of 10: "+note_of_10);
note_of_2=amount/2;
amount=amount%2;
System.out.println("note of 2: "+note_of_2);
 
amount=amount%1;
System.out.println("note of 1: "+note_of_1);
}}
