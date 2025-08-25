# Java-Notew
Java Notes
📌 1. Introduction to Java

Java is a high-level, object-oriented, platform-independent language developed by Sun Microsystems (now owned by Oracle).

WORA: Write Once, Run Anywhere – due to the Java Virtual Machine (JVM).

📌 2. Java Basics
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }
}

Basic Syntax

Class name must match the file name.

main() is the entry point.

Statements end with a semicolon (;).

📌 3. Data Types
🔹 Primitive Types:
Type	Size	Example
int	4 bytes	10
float	4 bytes	3.14f
double	8 bytes	3.14159
char	2 bytes	'A'
boolean	1 bit	true / false
🔹 Non-Primitive:

String, Arrays, Classes, Interfaces.

📌 4. Variables
int age = 25;
String name = "John";

📌 5. Operators

Arithmetic: + - * / %

Comparison: == != > < >= <=

Logical: && || !

Assignment: = += -= *= /=

📌 6. Control Structures
🔸 if-else
if (age > 18) {
    System.out.println("Adult");
} else {
    System.out.println("Minor");
}

🔸 switch-case
switch (day) {
    case 1: System.out.println("Monday"); break;
    default: System.out.println("Other Day");
}

🔸 Loops
for (int i = 0; i < 5; i++) {}
while (condition) {}
do {} while (condition);

📌 7. Arrays
int[] numbers = {1, 2, 3, 4};
String[] names = new String[3];

📌 8. Object-Oriented Programming (OOP)
🔹 Class & Object
class Car {
    String color;
    void drive() {
        System.out.println("Driving");
    }
}
Car myCar = new Car();
myCar.drive();

🔹 Inheritance
class Animal {
    void eat() {}
}
class Dog extends Animal {
    void bark() {}
}

🔹 Polymorphism, Abstraction, Encapsulation

Polymorphism: method overriding/overloading

Abstraction: abstract class or interface

Encapsulation: private fields with getters/setters

📌 9. Access Modifiers
Modifier	Scope
public	Everywhere
private	Within class only
protected	Same package + subclass
default	Same package
📌 10. Exception Handling
try {
    int result = 10 / 0;
} catch (ArithmeticException e) {
    System.out.println("Error: " + e.getMessage());
} finally {
    System.out.println("Finally block");
}

📌 11. Java Collections

List: ArrayList, LinkedList

Set: HashSet, TreeSet

Map: HashMap, TreeMap

List<String> list = new ArrayList<>();
Map<String, Integer> map = new HashMap<>();

📌 12. Multithreading
class MyThread extends Thread {
    public void run() {
        System.out.println("Thread running");
    }
}
MyThread t1 = new MyThread();
t1.start();

📌 13. File I/O
File file = new File("data.txt");
Scanner sc = new Scanner(file);
while (sc.hasNextLine()) {
    System.out.println(sc.nextLine());
}

📌 14. Java Keywords

static, final, this, super, new, return, throw, throws, try, catch, finally, implements, extends, etc.

📌 15. Java Development Tools

JDK: Java Development Kit

JRE: Java Runtime Environment

JVM: Java Virtual Machine

IDEs: IntelliJ IDEA, Eclipse, NetBeans
