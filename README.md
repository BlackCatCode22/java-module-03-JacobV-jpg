//1.
//myStudent.java
public class Main {
    public static void main(String[] args) {

        student student1 = new student();
        student1.firstname = "Joe";
        student1.lastname = "Mamia";
        student1.course = "Beginning Java";
        student1.age = 20;
        student1.GPA = 1.0;
        student1.probabation = true;

        student student2 = new student();
        student2.firstname = "Donkey";
        student2.lastname = "Kung";
        student2.course = "Beginning Java";
        student2.age = 43;
        student2.GPA = 4.0;
        student2.probabation = false;

        System.out.println(student1.firstname + " " + student1.lastname + " " + student1.course + " " + student1.age + " " + student1.GPA);
        System.out.println(student2.firstname + " " + student2.lastname + " " + student2.course + " " + student2.age + " " + student2.GPA);
    }
}
public class student {
    String firstname;
    String lastname;
    int age;
    double GPA;
    String course;
    Boolean probabation;
}


//2.
//myStuff.java
public class Main {

    public static void main(String[] args) {
        object artist1 = new object();
        artist1.Artist = "Timmy Well";
        artist1.Genre = "Comedy";
        artist1.Title = "The Hunt";
        artist1.Year = 31000;
        artist1.Medium = "Oil";

        object artist2 = new object();
        artist2.Artist = "Leonardo Da Vinci";
        artist2.Genre = "Renaissance";
        artist2.Title = "Mona Lisa";
        artist2.Year = 1503;
        artist2.Medium = "Oil";

        System.out.println(artist1.Artist);
        System.out.println(artist2.Artist);


    }
}
public class object {
    String Genre;
    String Title;
    int Year;
    String Artist;
    String Medium;



}


//3.
//myAnimals.java
public class Main {
    public static void main(String[] args) {

        System.out.println(cat.getCatCounter());
        cat cat1 = new cat();
        cat1.name = "El Gato";
        cat1.age = 2;
        System.out.println(cat.live);
        System.out.println(cat1.getCatCounter());

        System.out.println(cat1.name);

        System.out.println(dog.getCatCounter());
        dog dog1 = new dog();
        dog1.name = "GodZilra";
        dog1.age = 7;
        System.out.println(cat.live);
        System.out.println(dog1.getCatCounter());


        System.out.println(dog1.name);
    }
}

public class cat {
    public static final int live = 9;
    private static int catCounter = 0;

    String name;
    int age;
    int lives;

    public void eat() {
        System.out.println("munch munch");
    }

    public void meow() {
        System.out.println("meow meow");
    }

    public cat () {
        catCounter++;
        lives = live;
    }

    public static int getCatCounter() {
        return catCounter;
    }
}

public class dog {
    public static final int live = 1;
    private static int dogCounter = 0;

    String name;
    int age;
    int lives;

    public void bark(){
        System.out.println("bark");
    }

    public dog () {
        dogCounter++;
        lives = live;
    }

    public static int getCatCounter() {
        return dogCounter;
    }
}


