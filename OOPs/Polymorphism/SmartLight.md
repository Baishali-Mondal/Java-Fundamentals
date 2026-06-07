package CodeTheConcepts.Polymorphism;

public class SmartLight extends SmartDevice {
    @Override
    public void turnOn(){
        System.out.println("SmartLight turned ON : Glowing ");
    }
}
