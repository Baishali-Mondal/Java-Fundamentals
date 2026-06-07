package CodeTheConcepts.Inheritance;

public class Developer extends Employee{
    String programmingLanguage;
    public Developer(String name, double baseSalary, String programmingLanguage){
        super(name, baseSalary);
        this.programmingLanguage = programmingLanguage;;
    }
    @Override
    public void displayInfo(){
        System.out.println("Developer Info --> ");
        super.displayInfo();
        System.out.println("Programming language: "+programmingLanguage);
    }

}
