# Java Language Basics

## Syntax
Java syntax is similar to C and C++. It uses semicolons to end statements and curly braces `{}` to define blocks of code.

## Printing in Java
Printing output in Java is typically done using `System.out.println()` or `System.out.print()` methods.

  ```java
    public class HelloWorld {
        public static void main(String[] args) {
            System.out.println("Hello, World!");
        }
    }
  ```

## Variables in Java
Java variables must be declared with a specific type. Common types include `int`, `double`, `boolean`, `String`, etc.

  ```java
    int age = 25;
    double price = 19.99;
    boolean isActive = true;
    String name = "John";
  ```

## Loops
Java supports `for`, `while`, and `do-while` loops.

  ```java
    // For loop
    for (int i = 1; i <= 5; i++) {
        System.out.println(i);
    }
    
    // While loop
    int count = 1;
    while (count <= 5) {
        System.out.println(count);
        count++;
    }
    
    // Do-while loop
    int num = 1;
    do {
        System.out.println(num);
        num++;
    } while (num <= 5);
```

## Functions (Methods)
Functions in Java are called methods. They are defined within classes and can be `static` (class-level) or instance methods

  ```java
    public class MyClass {
        // Static method
        public static void sayHello() {
            System.out.println("Hello, World!");
        }
    
        // Instance method
        public void greet(String name) {
            System.out.println("Hello, " + name);
        }
    
        public static void main(String[] args) {
            sayHello(); // Calling a static method
            MyClass obj = new MyClass();
            obj.greet("John"); // Calling an instance method
        }
    }
```

## Returning Values
Methods in Java can return values using the `return` keyword.

  ```java
    public class Calculator {
        public int add(int a, int b) {
            return a + b;
        }
    
        public static void main(String[] args) {
            Calculator calc = new Calculator();
            int result = calc.add(5, 3);
            System.out.println("Sum: " + result);
        }
    }
  ```

## Use of Lists (Arrays and ArrayLists)
Java arrays are fixed-size collections of elements of the same type. ArrayLists are dynamically resizable lists.
  ```java
    // Arrays
    int[] numbers = {1, 2, 3, 4, 5};
    System.out.println("First number: " + numbers[0]);
    
    // ArrayLists
    import java.util.ArrayList;
    ArrayList<String> names = new ArrayList<>();
    names.add("Alice");
    names.add("Bob");
    System.out.println("First name: " + names.get(0));
  ```



