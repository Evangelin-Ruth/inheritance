## EXPERIMENT 08: USING INHERITANCE ACQUIRE THE PROPERTIES OF OTHER CLASSES
## AIM:
To create a class that acquires properties of other class using inheritance.

## PROCEDURE:
1. Create a class named animal.
2. Add a method named walk.
3. Create a class named Bird.
4. Add methods like fly and sing.
5. Inherit the properties of class animal to class bird.
6. Create object for bird in main class and call the methods.
7. End the program.

## PROGRAM
### Main.java
```
public class Main {
    public static void main(String[] args)
    {
        Bird obj1=new Bird();
        obj1.walk();
        obj1.fly();
        obj1.sing();
    }
}
```

### Animal.java

```
public class Animal {
    void walk()
    {
        System.out.println("I am walking");
    }
}
```

### Bird.java

```
public class Bird extends Animal{
    void fly()
    {
        System.out.print("I am flying ");
    }
    void sing()
    {
        System.out.print("I am singing");
    }
}
```

## OUTPUT:
![image](https://github.com/Evangelin-Ruth/inheritance/assets/94219798/d8ff4078-a34a-47d2-a0ba-c385bcbf7415)
## RESULT:
Hence,a program to create a class that inherits properties of other class is done using inheritance.

