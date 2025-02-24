[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/EV9E9T0q)
# tJavaModule03spr25
tJavaModule03spr25 

Code up these three or four programs and submit source code to your remote repo in GitHub Classroom. Please use the java class file names as specified here. If you know how to zip files, you may also do that as well.

1) package: mystudent; class files: App.java, Student.java - Watch the video "Classes and Objects" and code up everything in the video

2) package: mystuff; class files: Driver.java, MyStuff.java - This is the challenge at the end of "Classes and Objects." Your choice of what "object in everyday life" you want to use for this program. 

3) package: myanimals; class files: Animal.java, Cat.java, Dog.java - Watch the video "Static and the Cat Class" and code up everything to create two subclasses (Cat.java and Dog.java) from the Animal class. Note how the static variable numOfAnimals works in your program. Create an output statement that outputs the current number of animals objects you have whenever a new Dog or Cat object is created. This is how you will know your program is working properly.

4) Advanced (extra credit) - Code up the card game program at the end of Chapter 5 in our textbook.

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

