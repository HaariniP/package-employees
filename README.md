# package-employees
public class Employees {
   private String name;
   private int id;
   private double salary;
  public Employees(String name,int id, double salary) {
   this.name=name;
       this.id=id;
       this.salary=salary;
   }
  public void displayDetails(){
      System.out.println("Employee ID:" + id);
      System.out.println("Employee Name: " + name);
      System.out.println("Employee Salary: $" + salary);
  }
}
  class main{
    public static void main(String[] args) {
        // TODO code application logic here
        Employees emp1 = new Employees("John Doe", 101, 50000);
        Employees emp2 = new Employees("Jane Smith", 102, 60000);
        emp1.displayDetails();
        System.out.println();
        emp2.displayDetails();
    }
    
}
Output
Employee ID:101
Employee Name: John Doe
Employee Salary: $50000.0

Employee ID:102
Employee Name: Jane Smith
Employee Salary: $60000.0
