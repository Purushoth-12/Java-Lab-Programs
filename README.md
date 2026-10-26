☕ Java Interface Lab Program

👨‍💻 Language: Java
📚 Topic: Interface
🎓 Purpose: College Laboratory Experiment

---

🎯 Aim

To write and execute a Java program to demonstrate the concept of an Interface.

📝 Algorithm

1. 🚀 Start the program.
2. 🏗️ Create an interface named "Animal" with a method "sound()".
3. 🔗 Create a class "Dog" that implements the "Animal" interface.
4. ⚙️ Implement the "sound()" method to print ""Dog barks"".
5. ▶️ Create the "main()" method.
6. 🐶 Create an object of the "Dog" class and call the "sound()" method.
7. 🏁 Stop the program.

💻 Program

interface Animal {
    void sound();
}

class Dog implements Animal {
    public void sound() {
        System.out.println("Dog barks");
    }
}

public class Main {
    public static void main(String[] args) {
        Dog d = new Dog();
        d.sound();
    }
}

🖥️ Output

Dog barks

📖 Explanation

- 🔹 Interface: "Animal" declares the "sound()" method.
- 🔹 Implements: The "Dog" class implements the "Animal" interface.
- 🔹 Method Implementation: The "Dog" class defines the "sound()" method.
- 🔹 Object Creation: An object of "Dog" is created in the "main()" method.

⚡ How to Run

1. 📁 Save the code as "Main.java".
2. 🛠️ Compile the program:
   javac Main.java
3. ▶️ Execute the program:
   java Main

✅ Result

Thus, the Java program demonstrating an interface was  executed, and the expected output was obtained successfully.

---

⭐ Learning Java | Practicing OOP Concepts | Building My Coding Portfolio 🚀

#Java #Programming #OOP #Interface #CSE #GitHub #LearningToCode
