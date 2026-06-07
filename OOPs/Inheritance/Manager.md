package CodeTheConcepts.Inheritance;

public class Manager extends Employee{
    int teamSize;
    public Manager(String name, double baseSalary,int teamSize) {
        super(name, baseSalary);
        this.teamSize = teamSize;
    }

    public void displayInfo() {
        System.out.println("Manager Info --> ");
        super.displayInfo();
        System.out.println("Team Size : "+teamSize);
    }
}
