# Add-methods-and-properties-to-the-Class-after-digitizing-Object
The problem occurs when I add the toString method as follows
import java.io.Serializable;

public class Person implements Serializable {
   private String name;
   private Integer age;

   public Person(String name, int age) {
       this.name = name;
       this.age = age;
   }

   @Override
   public String toString() {
       return "Person{" +
               "name='" + name + '\'' +
               ", age=" + age +
               '}';
   }
}
