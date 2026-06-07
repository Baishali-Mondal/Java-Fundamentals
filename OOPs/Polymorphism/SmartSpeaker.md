package CodeTheConcepts.Polymorphism;

public class SmartSpeaker extends SmartDevice {

    @Override
    public void turnOn(){
        System.out.println("Smart Speaker turned On : Playing music");
    }
}
