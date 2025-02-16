1..
import java.util.Scanner;

public class Main {

     
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter three numbers
        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();

        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();

        System.out.print("Enter the third number: ");
        int num3 = scanner.nextInt();

        // Close the scanner to avoid resource leak
        scanner.close();
        
        int largest=0 ;

        if (num1 >= num2 && num1 >= num3) {
            largest = num1;
        } 
        else if (num2 >= num1 && num2 >= num3) {
            largest = num2;
        } 
        else {
            largest = num3;
        }

        // Display the largest number
        System.out.println("The largest number is: " + largest);
    }
}




2..
import java.util.Scanner;

public class Main {
    String Name;
    int Age =0;
    double Salary =0;

    public static void main(String[] args) {
        Main employee = new Main(); 
        Scanner scanner = new Scanner(System.in);

        //  enter employee details
        System.out.print("Enter Name: ");
        employee.Name = scanner.nextLine();

        System.out.print("Enter Age: ");
        employee.Age = scanner.nextInt();

        System.out.print("Enter Salary: ");
        employee.Salary = scanner.nextDouble();

        // Close the scanner 
        scanner.close();

        // Display the employee details
        System.out.println("Employee Name: " + employee.Name);
        System.out.println("Employee Age: " + employee.Age);
        System.out.println("Employee Salary: " + employee.Salary);
    }
}



3..
import java.util.Scanner;

public class Main {
    String Name;
    int Age =0;
    double Salary =0;
    final int id = 232;
    public static void main(String[] args) {
        Main employee = new Main(); 
        Scanner scanner = new Scanner(System.in);

        //  enter employee details
        System.out.print("Enter Name: ");
        employee.Name = scanner.nextLine();

        System.out.print("Enter Age: ");
        employee.Age = scanner.nextInt();

        System.out.print("Enter Salary: ");
        employee.Salary = scanner.nextDouble();

       //System.out.print("Enter Vale of id : ");
        //employee.id = scanner.nextInt(); 
        
        // Close the scanner 
        scanner.close();

        // Display the employee details
        System.out.println("Employee Name: " + employee.Name);
        System.out.println("Employee Age: " + employee.Age);
        System.out.println("Employee Salary: " + employee.Salary);
        System.out.println("Employee id   : " + employee.id);
    }
}



4....
import java.util.Scanner;

public class Main {
    String Name;
    int Age ;
    double Salary;
    final int id = 232;
   public static void display(String Name, int Age, double Salary, final int id){
        System.out.println("Employee Name: " + Name);
        System.out.println("Employee Age: " + Age);
        System.out.println("Employee Salary: " + Salary);
        System.out.println("Employee id   : " + id);
   }
    
     public static void main(String[] args) {
        Main employee = new Main(); 
        Scanner scanner = new Scanner(System.in);

        //  enter employee details
        System.out.print("Enter Name: ");
        employee.Name = scanner.nextLine();

        System.out.print("Enter Age: ");
        employee.Age = scanner.nextInt();

        System.out.print("Enter Salary: ");
        employee.Salary = scanner.nextDouble();

       //System.out.print("Enter Vale of id : ");
        //employee.id = scanner.nextInt(); 
        
       // Close the scanner 
        scanner.close();

        // Display the employee details
        System.out.println("Employee Name: " + employee.Name);
        System.out.println("Employee Age: " + employee.Age);
        System.out.println("Employee Salary: " + employee.Salary);
        System.out.println("Employee id   : " + employee.id);
        
     display(employee.Name, employee.Age, employee.Salary, employee.id);
    }
}

5..
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Input length and height
        System.out.print("Enter length: ");
        double length = scanner.nextDouble();

        System.out.print("Enter height: ");
        double height = scanner.nextDouble();

        // Calculate area
        double area = length * height;

        // Display the area
        System.out.println("The area of the rectangle is: " + area);

        // Close the scanner
        scanner.close();
    }
}
