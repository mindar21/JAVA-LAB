// 12) Demonstrate instanceof keyword to check object types in an inheritance hierarchy.

class Animal {}

class Dog extends Animal {}

class Cat extends Animal {}

public class InstanceOfDemo {
    public static void main(String[] args) {
        Animal a1 = new Dog();
        Animal a2 = new Cat();

        // Checking object type
        if (a1 instanceof Dog) {
            System.out.println("a1 is an instance of Dog");
        }

        if (a1 instanceof Animal) {
            System.out.println("a1 is also an instance of Animal");
        }

        if (a2 instanceof Cat) {
            System.out.println("a2 is an instance of Cat");
        }

        if (a2 instanceof Dog) {
            System.out.println("a2 is an instance of Dog");
        } else {
            System.out.println("a2 is NOT a Dog");
        }
    }
}
