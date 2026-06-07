package CodeTheConcepts.ClassesObjects;

public class Player {
    private String username;
    private int level;
    private int health;

    public Player(String username){
        this.username = username;
        this.level = 1;
        this.health = 100;
    }
    public void displayStats(){
        System.out.println("Player " + username + " has level " +level + " with health rate of  " + health);
    }
}
