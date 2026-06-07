package CodeTheConcepts.Abstraction;

public class UPIPayment implements PaymentProcessor {
    @Override
    public void pay(double amount) {
        System.out.println("Paying Rs. " + amount + " using UPI");
    }
}
