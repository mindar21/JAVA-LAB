// 13) Create an abstract class Appliance with abstract method start(). Create concrete classes Fan and WashingMachine to implement it.


abstract class Appliance {
    abstract void start();
}

class Fan extends Appliance {
    @Override
    void start() {
        System.out.println("Fan is starting... Spinning blades!");
    }
}

class WashingMachine extends Appliance {
    @Override
    void start() {
        System.out.println("Washing Machine is starting... Washing clothes!");
    }
}

public class ApplianceTest {
    public static void main(String[] args) {
        Appliance a;

        a = new Fan();
        a.start();

        a = new WashingMachine();
        a.start();
    }
}
