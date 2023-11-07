# Ex-8-Using-Inheritance-one-class-can-acquire-the-properties-of-others.
```

class Animal {
    void eat() {
        System.out.println("This animal eats food.");
    }
}

class Dog extends Animal {
    void bark() {
        System.out.println("The dog barks.");
    }
}

public class InheritanceExample {
    public static void main(String[] args) {
        Dog myDog = new Dog();
        myDog.eat();
        myDog.bark();
    }
}

```
#Output
![Screenshot (73)](https://github.com/21002624/Ex-8-Using-Inheritance-one-class-can-acquire-the-properties-of-others./assets/113762183/b0805c3b-b02f-4262-abc1-e59a0d1ebbf9)
