# first-dummy
just a dummy
import java.util.Scanner;
@SuppressWarnings("resource")
public class dog {
 

String name = "Von";
String color = "Black";
String breed = "German";
int age = 2;
double price = 2000;

{
Scanner sc = new Scanner(System.in);


System.out.println("Enter name :");
name = sc.toString();
System.out.println("Enter color :");
color = sc.toString();
System.out.println("Enter age  :");
age = sc.nextInt();
}


void bark() {

	System.out.println("Barks loudly");
	
}
void run() {
	System.out.println("Runs fast");
}
}
