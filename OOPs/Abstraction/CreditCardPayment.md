package CodeTheConcepts.Abstraction;

public class CreditCardPayment implements PaymentProcessor {
    @Override
    public void pay(double amount) {
        System.out.println("Paying Rs. " + amount + " using CrediCard");
    }
}
