#include<stdio.h>

Class Rectangle{
public static void main(String[] args) {
int a = scan.nextInt;
int b = scan.nextInt;
int area;
int perimeter;
Scanner scan=new Scanner(System.in);

System.out.println(" Въведи A : ");
a=scan.nextInt;
while(a<=0){
System.out.println(" Грешка");
a=scan.nextInt; }
System.out.println(" Въвдеи B : ");
b=scan.nextInt;
while(b<=0){
System.out.println(" Грешка");
b=scan.nextInt; }

area = a * b;

perimeter=2*(a+b);

System.out.println("Area of Rectangle : %d", area);
System.out.println("Perimeter of Rectangle : %d", perimeter);

}
}
