package CodeTheConcepts;

import CodeTheConcepts.Abstraction.CreditCardPayment;
import CodeTheConcepts.Abstraction.PaymentProcessor;
import CodeTheConcepts.Abstraction.UPIPayment;

public class main {
    static void main() {
//        //Player Class Instantiation
//        Player player1 = new Player("John");
//        Player player2 = new Player("Mike");
//
//        player1.displayStats();
//        player2.displayStats();

//        //BankAccount
//        BankAccount bankAccount = new BankAccount(1000);
//        bankAccount.deposit(5000);
//        bankAccount.withdraw(-1000);
//        bankAccount.withdraw(7000);
//        bankAccount.deposit(-200);
//        bankAccount.withdraw(6000);

//        //Employee
//        Employee emp1 =new Employee("John",8000);
//        Employee emp2 =new Developer("Mike",100000,"Java");
//        Employee emp3 =new Manager("Charlie",170000, 10);
//
//        emp1.displayInfo();
//        emp2.displayInfo();
//        emp3.displayInfo();

//        //SmartDevice
//        SmartDevice[] deviceList = {  new SmartDevice(),
//                                new SmartLight(),
//                                new SmartDevice(),
//                                new SmartSpeaker(),
//                                new SmartLight()};
//        for (SmartDevice device : deviceList){
//            device.turnOn();
//    }

        //PaymentProcessor

        PaymentProcessor pay1 = new UPIPayment();
        PaymentProcessor pay2 = new CreditCardPayment();
        PaymentProcessor pay3 = new UPIPayment();

        pay1.pay(5000);
        pay2.pay(9000);
        pay3.pay(200);

    }
}
