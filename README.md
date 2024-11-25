## Hi there 👋

```java 
public class Klixxs {
    private String name;
    private String username;
    private int age;
    private String location;
    private String instagram;
    private String discord;

    public Klixxs() {
        this.name = "Jonathan";
        this.username = "klixxs";
        this.age = 18;
        this.location = "Berlin, Germany";
        this.instagram = "@jonathan.hfn";
        this.discord = "@klixxs";
    }

    public static void main(String[] args) {
        Klixxs me = new Klixxs();
	System.out.println(me);
    }
}
