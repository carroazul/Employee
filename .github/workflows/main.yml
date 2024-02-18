package employee;

public class Employee {
	String firstName;
	String lastName;
	String positionTitle;
	int employeeID;
	double salary;

	//	constructor method -   initialize salary field to zero.
	
	public Employee() {
		salary = 0.0;
	}
	
//	setters and getters for firstName and lastName
	
	public String getFirstName() {
		return firstName;
	}
	public void setFirstName(String fname) {
		this.firstName = fname;
	}
	
    public String getLastName() {
		return lastName;
	}
	
	public void setLastName(String lname) {
		this.lastName = lname;
	}
	
	public String getPositionTitle() {
		return positionTitle;
	}
 	
	public void setPositionTitle(String title) {
		this.positionTitle = title;
	}
	

	public int getEmployeeID() {
		return employeeID;
	}
	
	public void setEmployeeID(int employeeID) {
		this.employeeID = employeeID;
	}
	
    public double getEmployeeSalary() {
		return salary;
	}
	
	public void setEmployeeSalary(double employeeSalary) {
		this.salary = employeeSalary;
	}
	
//	employeeSummary method - prints all account attributes
	
	public void employeeSummary() {
		String emp = "Employee Name: " + firstName + " " + lastName + "\n"; 
		String emp_id = "Employee_id: " + employeeID + "\n"; 
		String pos = "Title: " + positionTitle + "\n"; 
		String sal = "Salary: " + salary + "\n";
		
		System.out.print(emp + emp_id + pos + sal);
		
	}
	
     public class Manager extends Employee {
	String department;
	
	public Manager() {
// Invoking class constructor
		super();
	}
	
//	getters and setters for department
	
	public String getDepartment() {
		return department;
	}
	
	public void setDepartment(String deptName) {
		this.department = deptName;
	}
	
	public void employeeSummary() {
		super.employeeSummary();
		System.out.println("Employee Department: " + department);
	}
	
    public class TestClass {
    Manager manager = new Manager();
	public static void main(String[] args) {
	Manager manager = new Manager();
		manager.setFirstName("Carlos");
		manager.setLastName("Delgado");
		manager.setEmployeeID(154794);
		manager.setEmployeeSalary(70000);
		manager.setPositionTitle("Software Engineer");
		
		manager.employeeSummary();
		
    }
} 
