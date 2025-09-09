// 15)  Demonstrate how abstraction works using interfaces: Define an interface Drawable and implement it in Circle and Square. 

interface Drawable {
    void draw(); 
}

class Circle implements Drawable {
    @Override
    public void draw() {
        System.out.println("Drawing a Circle");
    }
}

class Square implements Drawable {
    @Override
    public void draw() {
        System.out.println("Drawing a Square");
    }
}

public class DrawableTest {
    public static void main(String[] args) {
        Drawable d;

        d = new Circle();
        d.draw();

        d = new Square();
        d.draw();
    }
}
