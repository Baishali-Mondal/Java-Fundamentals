package CodeTheConcepts.Encapsulation;

public class BankAccount {
    private double balance;

    public BankAccount(double balance){
        this.balance = balance;
    }
    public void deposit(double amount){
        if(amount < 0){
            System.out.println("Error:Amount must be positive");
        }else {
            balance += amount;
            System.out.println("Deposited : " + amount + " Available balance: " + balance);
        }

    }
    public void withdraw(double amount){
        if(amount >balance){
            System.out.println("Error:Insufficient balance");
        }
        else if(amount < 0){
            System.out.println("Error:Amount to be withdrawn should be positve");
        }
        else {
            balance -= amount;
            System.out.println("Withdrawn " + amount + " Available Balance " + balance);
        }
    }
}
