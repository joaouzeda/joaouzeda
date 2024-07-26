
 ```C
public class SoftwareEngineer {
    private String name;
    private String role;
    private String[] languageSpoken;

    public SoftwareEngineer() {
        this.name = "Bruna Markowisk";
        this.role = "Software Engineer Student";
        this.languageSpoken = new String[]{"pt_BR", "en_US"};
    }

    public void sayHi() {
        System.out.println("Thanks for dropping by. Contact me to code together and build something new :)");
    }

    public static void main(String[] args) {
        SoftwareEngineer me = new SoftwareEngineer();
        me.sayHi();
    }
}

 ```
